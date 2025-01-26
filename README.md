# Implementation of Incremental and Gauss Reduction Algorithms

This project focuses on implementing two algorithms: the **Incremental Algorithm** and the **Gauss Reduction Algorithm**. 
These algorithms are applied to compute Betti numbers of simplicial complexes and their filtrations.

## Project Objectives

1. **Algorithm Implementation**:
   - Both algorithms should take as input:
     - A **simplicial complex K**, represented as a list or dictionary.
     - A **filtration of subcomplexes**: \( K_1 \subset K_2 \subset K_3 \subset \dots \subset K_n = K \).

2. **Filtration**:
   - Use a filtration based on the **dimension of the simplices**.

3. **Output**:
   - The output should be a list of **Betti numbers**: 
     \( \beta_0(K), \beta_1(K), \dots, \beta_{\text{dim}(K)}(K) \), 
     where each \( \beta_i \) corresponds to the rank of the \( i \)-th homology group.

4. **Testing**:
   - Test the algorithms on the triangulations of the following topological spaces:
     - A **circle** (\( S^1 \)).
     - A **2-dimensional sphere** (\( S^2 \)).
     - A **torus**.

## Goals
The main goal of this project is to compute the Betti numbers of simplicial complexes accurately using the Incremental and Gauss Reduction Algorithms. This will provide insights into the topological properties of the given spaces.
