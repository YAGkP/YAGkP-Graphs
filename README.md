# YAGkP-Graphs

Graph sets for testing and benchmarking [Yet Another Graph k-Partition Library (YAGkP)](https://github.com/YAGkP/YAGkP-Lib).

Every set is a `<set>.tar.gz` archive attached to a [release](../../releases) of this repository, with one Matrix Market (`.mtx`) file per graph. The graphs are not stored in the repository itself.

## Graph sets

### [1/3] [walshaw](https://github.com/YAGkP/YAGkP-Graphs/releases/tag/walshaw)

All 34 graphs of [The Graph Partitioning Archive](https://chriswalshaw.co.uk/partition/) by Chris Walshaw, the standard benchmark for graph partitioning with tables of the best known cuts for k = 2, 4, …, 64 and imbalance of 0%, 1%, 3% and 5%.

The graphs of the archive are unweighted; numerical values in some SuiteSparse files (e.g. bcsstk*) are matrix entries, not edge weights, and should be ignored.

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

### [2/3] [large8](https://github.com/YAGkP/YAGkP-Graphs/releases/tag/large8)

8 graphs with 0.5-1.1M vertices from different domains. All graphs are undirected and connected, without self-loops.

Two graphs, tx2010 and ca2010, have natural integer edge weights; their total edge weight is about 10^11. The other six graphs are unweighted (all edge weights are 1).

The graphs come from the [SuiteSparse Matrix Collection](https://sparse.tamu.edu) and from [Network Repository](https://networkrepository.com). The graphs themselves were not changed. The files from Network Repository start with a non-standard header `%MatrixMarket`, which was corrected to `%%MatrixMarket`.

| graph | n | m | what it is | edge weights | source | how obtained |
|---|---:|---:|---|---|---|---|
| tx2010 | 914,231 | 2,228,136 | 2010 US Census blocks of Texas: an edge joins blocks with a common border | integer, length of the common border (14 - 1.0·10^7) | SuiteSparse, [DIMACS10/tx2010](https://sparse.tamu.edu/DIMACS10/tx2010) | as is |
| ca2010 | 710,145 | 1,744,683 | 2010 US Census blocks of California, same as tx2010 | integer, length of the common border (9 - 1.25·10^7) | SuiteSparse, [DIMACS10/ca2010](https://sparse.tamu.edu/DIMACS10/ca2010) | as is |
| roadNet-PA | 1,087,562 | 1,541,514 | road network of Pennsylvania: intersections and roads | unweighted | [Network Repository](https://networkrepository.com/road-roadNet-PA.php), road/road-roadNet-PA | header fixed, renamed |
| soc-flickr | 513,969 | 3,190,452 | friendships of Flickr users (photo sharing) | unweighted | [Network Repository](https://networkrepository.com/soc-flickr.php), soc/soc-flickr | header fixed |
| soc-FourSquare | 639,014 | 3,214,986 | friendships of Foursquare users (location-based network); one vertex has degree 106,218 | unweighted | [Network Repository](https://networkrepository.com/soc-FourSquare.php), soc/soc-FourSquare | header fixed |
| web-it-2004 | 509,338 | 7,178,413 | hyperlinks between pages of the .it domain, without direction | unweighted | [Network Repository](https://networkrepository.com/web-it-2004.php), web/web-it-2004 | header fixed |
| NACA0015 | 1,039,183 | 3,114,818 | 2D mesh around a NACA 0015 airfoil (computational fluid dynamics) | unweighted | SuiteSparse, [DIMACS10/NACA0015](https://sparse.tamu.edu/DIMACS10/NACA0015) | as is |
| delaunay_n20 | 1,048,576 | 3,145,686 | Delaunay triangulation of 2^20 random points in the unit square | unweighted | SuiteSparse, [DIMACS10/delaunay_n20](https://sparse.tamu.edu/DIMACS10/delaunay_n20) | as is |

### [3/3] [kahip9](https://github.com/YAGkP/YAGkP-Graphs/releases/tag/kahip9)

9 graphs with 0.7-2.2M vertices from different domains, taken from the benchmark sets of the KaHIP group: all of them are in Set A of [KaMinPar](https://arxiv.org/abs/2105.02022) (`instances.csv` on its [page](https://ae.iti.kit.edu/documents/research/deep_mgp)), and belgium_osm and netherlands_osm are also the graphs bel and nld of [KaFFPa](https://arxiv.org/abs/1210.0477).

All graphs are undirected, unweighted (as in the KaHIP benchmarks) and without self-loops.

The graphs come from the [SuiteSparse Matrix Collection](https://sparse.tamu.edu) and [SNAP](https://snap.stanford.edu/data/). Graphs stored there as matrices with numerical values were converted to the pattern format: every stored entry (explicit zeros too) is an edge, the values and the diagonal are dropped. The number of vertices and edges is the same as in the KaMinPar table, except com-youtube (see below).

| graph | n | m | what it is | source | how obtained |
|---|---:|---:|---|---|---|
| amazon-2008 | 735,323 | 3,523,472 | links between similar books in the Amazon store | SuiteSparse, [LAW/amazon-2008](https://sparse.tamu.edu/LAW/amazon-2008) | direction removed |
| ecology1 | 1,000,000 | 1,998,000 | 1000 x 1000 grid of a landscape connectivity model (circuit theory in ecology) | SuiteSparse, [McRae/ecology1](https://sparse.tamu.edu/McRae/ecology1) | values and diagonal dropped |
| rgg_n_2_20_s0 | 1,048,576 | 6,891,620 | random geometric graph: 2^20 random points in the unit square, an edge joins points closer than a threshold | SuiteSparse, [DIMACS10/rgg_n_2_20_s0](https://sparse.tamu.edu/DIMACS10/rgg_n_2_20_s0) | as is |
| com-youtube | 1,134,890 | 2,987,624 | friendships of YouTube users; one vertex has degree 28,754 | [SNAP](https://snap.stanford.edu/data/com-Youtube.html), com-youtube.ungraph.txt.gz | edge list converted, vertices renumbered 1..n without gaps (KaMinPar lists 1,157,828 vertices, apparently with the 22,938 unused numbers as isolated vertices) |
| thermal2 | 1,227,087 | 3,676,134 | finite element mesh of a steady-state thermal problem | SuiteSparse, [Schmid/thermal2](https://sparse.tamu.edu/Schmid/thermal2) | values and diagonal dropped, 958 isolated vertices removed (as in KaMinPar) |
| belgium_osm | 1,441,295 | 1,549,970 | road network of Belgium from OpenStreetMap | SuiteSparse, [DIMACS10/belgium_osm](https://sparse.tamu.edu/DIMACS10/belgium_osm) | as is |
| G3_circuit | 1,585,478 | 3,037,674 | circuit simulation | SuiteSparse, [AMD/G3_circuit](https://sparse.tamu.edu/AMD/G3_circuit) | values and diagonal dropped |
| kkt_power | 2,063,494 | 6,482,320 | KKT system of an optimal power flow problem (nonlinear optimization) | SuiteSparse, [Zaoui/kkt_power](https://sparse.tamu.edu/Zaoui/kkt_power) | values and diagonal dropped |
| netherlands_osm | 2,216,688 | 2,441,238 | road network of the Netherlands from OpenStreetMap | SuiteSparse, [DIMACS10/netherlands_osm](https://sparse.tamu.edu/DIMACS10/netherlands_osm) | as is |

