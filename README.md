# Data-Center-and-Graphs
## Part 1
  1. Write a script to generate an p-ER random graph.
  2. Write a script to generate an r -regular random graph.
  3. Write a script to check the connectivity of a given graph.
    - algebraic method 1 (irreducibility);
    - algebraic method 2 (eigenvalue of the Laplacian matrix);
    - breadth-first search algorithm.
  4. Compare the complexity as a function of n of the methods above.
  5. Let pc(G) denote the probability that a graph G is connected.
     Produce two graphs:
      - pc(G) vs. p for Erdos-Renyi graphs G(n,p) with n = 100.
      - pc(G) vs. n for r-regular random graphs with r = 2, 4, 8, 16 and n ranging up to 100.
## Part 2
  1. Throughput performance
     - Write a script that: (i) generates a random graph describing the topology of the ToR switch network; (ii) checks its connectivity;    (iii) finds shortest path routes; (iv) estimates h.
     - Use both the r-regular random graph model and the p-Erdos-Renyi random graph model. In either case let n be the number of nodes (you can assume 9 <= n <= 100, r = 8 and p = 8=(n - 1)).
     - Plot the application-oblivious throughput bound TH, as defined above, versus n for the two graph models.
  2. Reliability performance
     - Assume a link can break down (fail) with probability q.
     - Plot TH as a function of q for 0 < q <= 0:25, for the two network models in point 1) above with n = 100.
