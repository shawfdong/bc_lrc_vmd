# Batch Connect - LRC VMD

A Batch Connect app for Open OnDemand that launches VMD within an LRC
batch job. It is based on and adapted from the [OSC VMD] app.

## Prerequisites

This Batch Connect app requires the following software be installed on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand node):

- [VMD] 1.9.4+
- [Xfce Desktop] 4+

For VNC server support:

- [TurboVNC] 2.1+
- [websockify] 0.8.0+

For hardware rendering support:

- [X server]
- [VirtualGL] 2.3+

**Optional** software:

- [Lmod] 6.0.1+ or any other `module purge` and `module load <modules>` based
  CLI used to load appropriate environments within the batch job

[OSC VMD](https://github.com/OSC/bc_osc_vmd)
[VMD]: http://www.ks.uiuc.edu/Research/vmd/
[Xfce Desktop]: https://xfce.org/
[TurboVNC]: http://www.turbovnc.org/
[websockify]: https://github.com/novnc/websockify
[X server]: https://www.x.org/
[VirtualGL]: http://www.virtualgl.org/
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod

## License

* Documentation, website content, and logo is licensed under
  [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
* Code is licensed under MIT (see LICENSE.txt)o
* VMD and its logo are intellectual property owned by the University of Illinois, and all right, 
title and interest, including copyright, remain with the University.
