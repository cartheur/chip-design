## CHIP-v1.0

This is the starting point of _cartheur-mini_ a take on a new build of the NTC C.H.I.P. including new branding.

# The target

* The target OS for the new design is <a href="https://debian.org" target="_blank">Debian 11</a> with Linux kernel <a href="https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.14.1.tar.xz" target="_blank">5.14.1</a>. We have the option as well to keep it in the version 4.4.13 kernel according to b149. This would be the path of least-resistance.
* For the time-being, only focus on the board itself and not the accessories such as cabling and DIPs.
* Can we leverage the <a href="https://github.com/GoogleContainerTools/distroless" target="_blank">distroless-bazel</a> toolset? I think so.

# The source
The _project_ directory contains the correct <a href="http://www.orcad.com/" target="_blank">OrCAD</a> file. However, it seems to be missing footprints. They are found as a *.lbr file, which is for <a href="https://www.autodesk.com/products/eagle/free-download" target="_blank">Eagle</a>.

c
