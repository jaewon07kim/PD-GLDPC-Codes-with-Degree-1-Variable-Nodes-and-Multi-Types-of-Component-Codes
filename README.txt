1. LDPC_PCM.txt: a lifted Tanner graph from the base matrix
- First row: number of check nodes / number of variable nodes / number of edges
- From the second row: edge information (check node index / variable node index)

2. Component.txt: information about component codes
- First row: component code type 1 / component code type 2
- Second row: number of GC nodes with type 1 / number of GC nodes with type 2
- Third row: codelength of type 1 / codelength of type 2
- From the fourth row: edge information of type 1 (GC node index / variable node index) and edge information of type 2 (GC node index / variable node index)

3. parity_check_matrix_%d.txt: PCM of component codes (%d: index)
- First row: number of check nodes / number of variable nodes
- From the second row: binary PCM

4. Base.base: base matrix

5. Puncturing for partially doped VNs is conducted with rho_d