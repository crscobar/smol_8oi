# smol_8oi
Custom 8-bit ISA

The goal of thsis 8-bit ISA is to optimize hashing as much as possible in two ways:

1. High Speed in SW: (i.e., minimizing dynamic instruction count for the Hash program).
2. Low Cost in HW: (i.e., making your CPU’s hardware design simplified).

We were able to reduce the dynamic instruction count for hashing from an initial 50K+ to 515! 
