# CSC-270-Work

This is William Blackwell's repository for work on the text of *Les Miserables* by Victor Hugo.

# Victor Hugo, *Les Miserables*
A citable digital edition. This edition has had a character-set validation to ensure that all characters are consistent. In this read.me you are provided with both the character-set list and a character-set count. Here you can also find `scripts/ngrams2.sc` which will allow you to run an n-gram analysis of the text without including stopwords.

**status:** In progress.

# Character-set Validation:

| Character | Character | Character | Character | Character |
|-----------|-----------|-----------|-----------|-----------|
| `space` (20) | `!` (21) | `"` (22) | `'` (27) | `(` (28) |
| `)` (29) | `*` (2a) | `+` (2b) | `,` (2c) | `-` (2d) |
| `.` (2e) | `/` (2f) | `0` (30) | `1` (31) | `2` (32) |
| `3` (33) | `4` (34) | `5` (35) | `6` (36) | `7` (37) |
| `8` (38) | `9` (39) | `:` (3a) | `;` (3b) | `?` (3f) |
| `A` (41) | `B` (42) | `C` (43) | `D` (44) | `E` (45) |
| `F` (46) | `G` (47) | `H` (48) | `I` (49) | `J` (4a) |
| `K` (4b) | `L` (4c) | `M` (4d) | `N` (4e) | `O` (4f) |
| `P` (50) | `Q` (51) | `R` (52) | `S` (53) | `T` (54) |
| `U` (55) | `V` (56) | `W` (57) | `X` (58) | `Y` (59) |
| `Z` (5a) | `_` (5f) | `a` (61) | `b` (62) | `c` (63) |
| `d` (64) | `e` (65) | `f` (66) | `g` (67) | `h` (68) |
| `i` (69) | `j` (6a) | `k` (6b) | `l` (6c) | `m` (6d) |
| `n` (6e) | `o` (6f) | `p` (70) | `q` (71) | `r` (72) |
| `s` (73) | `t` (74) | `u` (75) | `v` (76) | `w` (77) |
| `x` (78) | `y` (79) | `z` (7a) | `«` (ab) | `º` (ba) |
| `»` (bb) | `À` (c0) | `Â` (c2) | `Ç` (c7) | `È` (c8) |
| `É` (c9) | `Ê` (ca) | `Ô` (d4) | `à` (e0) | `â` (e2) |
| `ç` (e7) | `è` (e8) | `é` (e9) | `ê` (ea) | `ë` (eb) |
| `î` (ee) | `ï` (ef) | `ñ` (f1) | `ô` (f4) | `ö` (f6) |
| `ù` (f9) | `û` (fb) | `ü` (fc) | `—` (2014) |

# Character-count Validation

|Letter| Occurances |Letter | Occurances | Letter | Occurances |Letter | Occurances |Letter | Occurances |
------ |------------|-------|------------|--------|------------|-------|------------|-------|------------|   
e      |    364573  | '     | 34886      |I       | 5561       |Q      |    1478    |(      |    75
s      |    218515  |g      | 34705      |M       | 5045       |B      |    1445    |)      |    75
t      |    209045  |1      | 28955      |;       | 4244       |ù      |    1416    |Ç      |    62
i      |    200419  |q      | 27424      |7       | 4063       |û      |    1366    |w      |    54
a      |    197261  |b      | 23954      |z       | 3643       |ô      |    1294    |Ô      |    47
u      |    189649  |2      | 23282      |!       | 3641       |î      |    1290    |Ê      |    43
n      |    174592  |L      | 19366      |J       | 3552       |F      |    1279    |ü      |    38
r      |    167071  | -     | 19254      |E       | 3206       |G      |    1210    |Z      |    37
l      |    150963  |8      | 18892      |?       | 2934       |U      |    1080    |ë      |    35
o      |    134848  |6      | 17601      |_       | 2908       |N      |    1011    |Y      |    35
.      |    96677   |[#]    | 13284      |P       | 2814       |R      |    670     |K      |    33
d      |    83055   |à      | 12177      |V       | 2725       |«      |    664     |"      |    24
c      |    80897   |j      | 9452       |9       | 2647       |À      |     558    |º      |    23
m      |    76315   |x      | 9445       | 0      | 2403       |»      |    557     |*      |    8
p      |    60160   |3      | 8670       | T      | 2307       |H      |    451     |/      |    6
:      |    55709   |4      | 8374       |A       | 2284       |—      |    365     |Â      |    6
é      |    45902   |è      | 8350       | D      | 2209       |É      |    329     |ñ      |    6
,      |    43847   |y      | 7843       |S       | 2044       |ï      |    265     |È      |    5
v      |    40922   |5      | 7247       |â       | 1790       |W      |    208     |*Blank*|    2
f      |    38664   |C      | 6848       |O       | 1651       |X      |    195     |ö      |    1
h      |    36678   |ê      | 6000       |ç       | 1646       |k      |    121     |+      |    1
