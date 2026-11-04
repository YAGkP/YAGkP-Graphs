# YAGkP-Graphs

Graph sets for testing and benchmarking [Yet Another Graph k-Partition Library (YAGkP)](https://github.com/Quaha/YAGkP-Lib).

Every set is a `<set>.tar.gz` archive attached to a [release](../../releases) of this repository, with one Matrix Market (`.mtx`) file per graph. The graphs are not stored in the repository itself.

## Graph sets

### [1/1] walshaw

All 34 graphs of [The Graph Partitioning Archive](https://chriswalshaw.co.uk/partition/) by Chris Walshaw, the standard benchmark for graph partitioning with tables of the best known cuts for k = 2, 4, …, 64 and imbalance of 0%, 1%, 3% and 5%.

Many download links of the archive are outdated (FTP servers, old addresses), so the graphs were taken from sources that are still available:

- 32 graphs come from the [SuiteSparse Matrix Collection](https://sparse.tamu.edu); 4elt is stored there as Pothen/barth5, the matrix the archive itself refers to;
- fe_pwt comes from the archive's own link to wotug.org and was converted from the SCOTCH graph format to Matrix Market;
- wave comes from [Network Repository](https://networkrepository.com), since it is not in SuiteSparse and the archive's FTP link is dead.

| graph | n | m | source | how obtained |
|---|---:|---:|---|---|
| add20 | 2,395 | 7,462 | SuiteSparse, [Hamm/add20](https://sparse.tamu.edu/Hamm/add20) | as is |
| data | 2,851 | 15,093 | SuiteSparse, [DIMACS10/data](https://sparse.tamu.edu/DIMACS10/data) | as is |
| 3elt | 4,720 | 13,722 | SuiteSparse, [AG-Monien/3elt](https://sparse.tamu.edu/AG-Monien/3elt) | as is |
| uk | 4,824 | 6,837 | SuiteSparse, [DIMACS10/uk](https://sparse.tamu.edu/DIMACS10/uk) | as is |
| add32 | 4,960 | 9,462 | SuiteSparse, [Hamm/add32](https://sparse.tamu.edu/Hamm/add32) | as is |
| bcsstk33 | 8,738 | 291,583 | SuiteSparse, [HB/bcsstk33](https://sparse.tamu.edu/HB/bcsstk33) | as is |
| whitaker3 | 9,800 | 28,989 | SuiteSparse, [AG-Monien/whitaker3](https://sparse.tamu.edu/AG-Monien/whitaker3) | as is |
| crack | 10,240 | 30,380 | SuiteSparse, [AG-Monien/crack](https://sparse.tamu.edu/AG-Monien/crack) | as is |
| wing_nodal | 10,937 | 75,488 | SuiteSparse, [DIMACS10/wing_nodal](https://sparse.tamu.edu/DIMACS10/wing_nodal) | as is |
| fe_4elt2 | 11,143 | 32,818 | SuiteSparse, [DIMACS10/fe_4elt2](https://sparse.tamu.edu/DIMACS10/fe_4elt2) | as is |
| vibrobox | 12,328 | 165,250 | SuiteSparse, [Cote/vibrobox](https://sparse.tamu.edu/Cote/vibrobox) | as is |
| bcsstk29 | 13,992 | 302,748 | SuiteSparse, [HB/bcsstk29](https://sparse.tamu.edu/HB/bcsstk29) | as is |
| 4elt | 15,606 | 45,878 | SuiteSparse, [Pothen/barth5](https://sparse.tamu.edu/Pothen/barth5) | as is, renamed |
| fe_sphere | 16,386 | 49,152 | SuiteSparse, [DIMACS10/fe_sphere](https://sparse.tamu.edu/DIMACS10/fe_sphere) | as is |
| cti | 16,840 | 48,232 | SuiteSparse, [DIMACS10/cti](https://sparse.tamu.edu/DIMACS10/cti) | as is |
| memplus | 17,758 | 54,196 | SuiteSparse, [Hamm/memplus](https://sparse.tamu.edu/Hamm/memplus) | as is |
| cs4 | 22,499 | 43,858 | SuiteSparse, [DIMACS10/cs4](https://sparse.tamu.edu/DIMACS10/cs4) | as is |
| bcsstk30 | 28,924 | 1,007,284 | SuiteSparse, [HB/bcsstk30](https://sparse.tamu.edu/HB/bcsstk30) | as is |
| bcsstk31 | 35,588 | 572,914 | SuiteSparse, [HB/bcsstk31](https://sparse.tamu.edu/HB/bcsstk31) | as is |
| fe_pwt | 36,519 | 144,794 | [wotug.org](https://wotug.org/parallel/libraries/communication/scotch/Graphs/fe_pwt.src.gz) | converted from SCOTCH format |
| bcsstk32 | 44,609 | 985,046 | SuiteSparse, [HB/bcsstk32](https://sparse.tamu.edu/HB/bcsstk32) | as is |
| fe_body | 45,087 | 163,734 | SuiteSparse, [DIMACS10/fe_body](https://sparse.tamu.edu/DIMACS10/fe_body) | as is |
| t60k | 60,005 | 89,440 | SuiteSparse, [DIMACS10/t60k](https://sparse.tamu.edu/DIMACS10/t60k) | as is |
| wing | 62,032 | 121,544 | SuiteSparse, [DIMACS10/wing](https://sparse.tamu.edu/DIMACS10/wing) | as is |
| brack2 | 62,631 | 366,559 | SuiteSparse, [AG-Monien/brack2](https://sparse.tamu.edu/AG-Monien/brack2) | as is |
| finan512 | 74,752 | 261,120 | SuiteSparse, [Mulvey/finan512](https://sparse.tamu.edu/Mulvey/finan512) | as is |
| fe_tooth | 78,136 | 452,591 | SuiteSparse, [DIMACS10/fe_tooth](https://sparse.tamu.edu/DIMACS10/fe_tooth) | as is |
| fe_rotor | 99,617 | 662,431 | SuiteSparse, [DIMACS10/fe_rotor](https://sparse.tamu.edu/DIMACS10/fe_rotor) | as is |
| 598a | 110,971 | 741,934 | SuiteSparse, [DIMACS10/598a](https://sparse.tamu.edu/DIMACS10/598a) | as is |
| fe_ocean | 143,437 | 409,593 | SuiteSparse, [DIMACS10/fe_ocean](https://sparse.tamu.edu/DIMACS10/fe_ocean) | as is |
| 144 | 144,649 | 1,074,393 | SuiteSparse, [DIMACS10/144](https://sparse.tamu.edu/DIMACS10/144) | as is |
| wave | 156,317 | 1,059,331 | [Network Repository](https://networkrepository.com/wave.php), misc/wave | as is |
| m14b | 214,765 | 1,679,018 | SuiteSparse, [DIMACS10/m14b](https://sparse.tamu.edu/DIMACS10/m14b) | as is |
| auto | 448,695 | 3,314,611 | SuiteSparse, [DIMACS10/auto](https://sparse.tamu.edu/DIMACS10/auto) | as is |
