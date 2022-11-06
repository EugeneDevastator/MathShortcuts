l - looped arguments

s - non looped segment

a - infinite argument (axis)

|       | representations for f(args)= value  |
| ----- | ----------------------------------- |
| s     | simple function slice               |
| l     | ring                                |
| a     | func                                |
| s,s   | 2d map                              |
| s,l   | sphere surface                      |
| l,l   | torus surface                       |
| s,s,s | cube volume sampler                 |
| s,s,l | sphere volume sampler               |
| s,l,l | torus volume sampler                |
| l,l,l | 4d torus volume? looped cube volume |
|       |                                     |



with infinite args

|       | representations for f(args)= value |
| ----- | ---------------------------------- |
| a     | vector                             |
| a,a   | 2d space                           |
| a,a,a | 3d space                           |
| a,l   | cylinder surface                   |
| a,a,l | 2d plane with looped height        |
| a,l,l | infinite looped cubic pole         |
| a,l,s | volume of infinite tube            |
|       |                                    |
|       |                                    |
|       |                                    |
|       |                                    |
|       |                                    |
|       |                                    |



Representations.

**Area** is 2d shape with its contents in 2d space.

**Volume** is 3d volume with its contents in 3d space

**Surface** is Area in 3d space

**Line** is any line in any space.



| f(x..)=(A..) | A (1d)                       | AB (2d)                                                      | ABC (3d)                                                  |
| ------------ | ---------------------------- | ------------------------------------------------------------ | --------------------------------------------------------- |
| x            | histogram,<br />value vector | parametric line in 2d                                        | parametric line in 3d                                     |
| x,y          | heat map 2d, heightmap       | 2d area deformation. convert one 2d area to other area.<br />2d vector map | parametric surface in 3d                                  |
| x,y,z        | heatmap 3d,<br />sdf,        |                                                              | volume of 3d vectors,<br /> parametric volume deformation |
|              |                              |                                                              |                                                           |

