# ccs
Centroid Comparison Script make a comparison of geometries using their centroid-point as a reference.

Benefits:
- CCS fixes all disadvantages of ESS
- The central point 𝐶𝑥𝑦𝑧 does not change its position during rotation or displacement of the
molecule and depends only on the position of the atoms relative to each other.
- Takes into account the difference between structures even when only one atom is shifted along
one coordinate. Example: tautomerism, where a proton can move from one oxygen to its neighbor
along only one x/y/z axis).
- Takes into account that the mirror images are the same (because the absolute distances from 𝐶𝑥𝑦𝑧
to each atom are the same).

Disadvantages:
- running CCS takes more time in compare to ESS. To reduce the CCS-search time, it is
recommended to reduce the number of structures under consideration, using first ESS and then
CCS. In this case, CCS uses results obtained from ESS to find geometrically individual structures.



© 2020 - 2022 Vasily N. Korotenko
Please report all suggestion, changes, improvements, and usage to
<vakoch@cup.uni-muenchen.de>
