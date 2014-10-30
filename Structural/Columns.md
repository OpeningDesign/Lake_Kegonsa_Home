# Example Column Design #



|          LOADS AND SPAN         |             |         | SECTION PROPERTIES |                               |             |             |        |      |
| ------------------------------- | ----------- | ------- | ------------------ | ----------------------------- | ----------- | ----------- | ------ | ---- |
| Wd=                             | 0,13        | kip/ft  | Shape  | d                             | tw          | bf          | tf     | Ry   | Zx   | Ix  | Sx   | J     | ho   |
| Wl=                             | 0,353       | kip/ft  | W10X26 | 10,3                          | 0,26        | 5,77        | 0,44   | 1,36 | 31,3 | 144 | 27,9 | 0,402 | 9,86 |
| L =                             | 21,6        | ft      |        |                               |             |             |        |      |      |     |      |       |      |
|                                 |             |         |        |                               |             |             |        |      |      |     |      |       |      |
| MATERIAL PROPERTIES             |             |         | A992   | High-Strength Low-Alloy       |             |             |        |      |      |     |      |       |      |
| Fy =                            | 50          |         |        | Preferred for W shape         |             |             |        |      |      |     |      |       |      |
| Fx =                            | 65          |         |        |                               |             |             |        |      |      |     |      |       |      |
| E =                             | 29000       |         |        |                               |             |             |        |      |      |     |      |       |      |
|                                 |             |         |        |                               |             |             |        |      |      |     |      |       |      |
| REQUIRED MOMENT OF INERTIA      |             |         |        | DESIGN MOMENT OF INERTIA      |             |             |        |      |      |     |      |       |      |
| D = L/360                       | 0,72        | inch    |        | Ix =                          | 144         | inch^4      |        |      |      |     |      |       |      |
| Ix (req) =                      | 82,80217291 | inch^4  |        | Ix req                        | <           | Ix          |        |      |      |     |      |       |      |
| Deflection criterion OK         |             |         |        | Checking Section              |             | W10X26      |        |      |      |     |      |       |      |
|                                 |             |         |        |                               |             |             |        |      |      |     |      |       |      |
| REQUIRED YIELD MOMENT           |             |         |        | DESIGN MOMENT AS PER AISC ASD |             |             |        |      |      |     |      |       |      |
| Yield Criterion as per F2.1 ASD |             |         |        | Mp =                          | 1565        | kip-in      |        |      |      |     |      |       |      |
| wa =                            | 0,483       | kip/ft  |        | Ob =                          | 1,67        |             |        |      |      |     |      |       |      |
| Ma =                            | 338,02272   | kip-in  |        | Available Flexural Strength:  |             |             |        |      |      |     |      |       |      |
|                                 |             |         |        | Mp / Ob =                     | 937,1257485 | kip-in      |        |      |      |     |      |       |      |
| Ma                              | <           | Mp / Ob |        |                               |             |             |        |      |      |     |      |       |      |
| Yield criterion OK              |             |         |        |                               |             |             |        |      |      |     |      |       |      |
|                                 |             |         |        |                               |             |             |        |      |      |     |      |       |      |
| Rts =                           | 1,536093205 |         |        | LATERAL-TORSIONAL BUCKLING    |             |             |        |      |      |     |      |       |      |
| Lr =                            | 138,8392288 | inch    |        | DESIGN MOMENT AS PER AISC ASD |             |             |        |      |      |     |      |       |      |
| Lp =                            | 57,64552157 | inch    |        |                               | Sx =        | 27,9        |        |      |      |     |      |       |      |
| Lb =                            | 259,2       | inch    |        |                               | Jc =        | 0,402       |        |      |      |     |      |       |      |
| Bracing @                       | 0           | points  |        |                               | h0 =        | 9,86        |        |      |      |     |      |       |      |
|                                 |             |         |        |                               | Fcr =       | 20,69112477 |        |      |      |     |      |       |      |
|                                 |             |         |        | Case (b)                      | Mn =        | 104,1132572 | kip-in |      |      |     |      |       |      |
| Using case (c):                 |             |         |        | Case (c)                      | Mn =        | 577,282381  | kip-in |      |      |     |      |       |      |
| Ma                              | <           | Mn / Ob |        |                               | Mn / Ob =   | 345,6780724 | kip-in |      |      |     |      |       |      |
| Buckling criterion OK           |             |         |        |                               |             |             |        |      |      |     |      |       |      |