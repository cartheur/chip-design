## The project where we are designing a new chip

This is the starting point of _cartheur-mini_ a take on a new build of the NTC C.H.I.P. including new branding.

# The target

* The target OS for the new design is <a href="https://debian.org" target="_blank">Debian 11</a> with Linux kernel <a href="https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.14.1.tar.xz" target="_blank">5.14.1</a>. We have the option as well to keep it in the version 4.4.13 kernel according to b149. This would be the path of least-resistance.
* The entire board will have to be proofed in order to obtain a rather assured estimate of the costs-per-unit of manufacture. There are anticipated issues with finding replacement parts. There is a question of upgrading. The focus is only on the main board.
* Can we leverage the <a href="https://github.com/GoogleContainerTools/distroless" target="_blank">distroless-bazel</a> toolset? Perhaps.

# The source
The _project_ directory contains the correct <a href="http://www.orcad.com/" target="_blank">OrCAD</a> file. However, it seems to be missing footprints. They are found as a *.lbr file, which is for <a href="https://www.autodesk.com/products/eagle/free-download" target="_blank">Eagle</a>.

In the historic version, there was no linkage between the design files meaning the entire project needed to be rebuilt in OrCad. 
The new project is in the subdirectory 'novo/cartheur-mini'.

c
