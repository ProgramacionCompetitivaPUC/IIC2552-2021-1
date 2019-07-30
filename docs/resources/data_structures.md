---
title: "Estructuras de Datos"
---

[Index](../index) > [Recursos](resources) > ```{{page.title}}```

# {{page.title}}

## C++ Data Structures (para llegar y usar):

- **Sequence Containers**:
    - [youtube: Introduction of STL #2: Sequence Containers](https://www.youtube.com/watch?v=gxZJ5JNuWMY&feature=youtu.be) (el video cubre vector, deque, list, forward list, array)
    - [youtube: C++ STL Part - 7 : The Container Adapters - Stack, Queue & Priority Queue](https://www.youtube.com/watch?v=VZh8GXQAnxY) (el video cubre stack, queue y priority_queue)
    - vector: [documentación](http://www.cplusplus.com/reference/vector/vector/), [geeksforgeeks](https://www.geeksforgeeks.org/vector-in-cpp-stl/)
    - queue: [documentación](http://www.cplusplus.com/reference/queue/queue/), [geeksforgeeks](https://www.geeksforgeeks.org/queue-cpp-stl/)
    - stack: [documentación](http://www.cplusplus.com/reference/stack/stack/), [geeksforgeeks](https://www.geeksforgeeks.org/stack-in-cpp-stl/)  
    - priority_queue (minheap / maxheap): [documentación](https://en.cppreference.com/w/cpp/container/priority_queue), [geeksforgeeks](https://www.geeksforgeeks.org/priority-queue-in-cpp-stl/)

- **Associative Containers**:
    - [youtube: Introduction of STL #3: Associative Containers](https://www.youtube.com/watch?v=6iyzPed7FrM&feature=youtu.be) (el video cubre set, multiset, map, multimap)
    - Set: [documentación](http://www.cplusplus.com/reference/set/set/), [geeksforgeeks](https://www.geeksforgeeks.org/set-in-cpp-stl/)
    - Multiset: [documentación](http://www.cplusplus.com/reference/set/multiset/), [geeksforgeeks](https://www.geeksforgeeks.org/multiset-in-cpp-stl/)
    - Map: [documentación](http://www.cplusplus.com/reference/map/map/), [geeksforgeeks](https://www.geeksforgeeks.org/map-associative-containers-the-c-standard-template-library-stl/)
    - Multimap: [documentación](http://www.cplusplus.com/reference/map/multimap/), [geeksforgeeks](https://www.geeksforgeeks.org/multimap-associative-containers-the-c-standard-template-library-stl/)

- **Unordered Containers**:
    - [Introduction of STL #4: Unordered Containers](https://www.youtube.com/watch?v=NNLvY9O7ufU) (el video cubre unordered set/multiset/map/multimap)
    - unordered_set: [documentación](http://www.cplusplus.com/reference/unordered_set/unordered_set/), [geeksforgeeks](https://www.geeksforgeeks.org/unordered_set-in-cpp-stl/)
    - unordered_multiset: [documentación](http://www.cplusplus.com/reference/unordered_set/unordered_multiset/), [geeksforgeeks](https://www.geeksforgeeks.org/unordered_multiset-and-its-uses/)
    - unordered_map: [documentación](http://www.cplusplus.com/reference/unordered_map/unordered_map/), [geeksforgeeks](https://www.geeksforgeeks.org/unordered_map-in-cpp-stl/)
    - unordered_multimap: [documentación](http://www.cplusplus.com/reference/unordered_map/unordered_multimap/), [geeksforgeeks](https://www.geeksforgeeks.org/unordered_multimap-and-its-application/)

- **Policy based data structures**:
    - [codeforces: C++ STL: Policy based data structures](https://codeforces.com/blog/entry/11080)
    - [geeksforgeeks: Policy based data structures in g++](https://www.geeksforgeeks.org/policy-based-data-structures-g/)

## Sparse Table:

- [cp-algorithms: sparse table](https://cp-algorithms.com/data_structures/sparse-table.html)
- [Código de ejemplo](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/sparse-table.cpp)

## Segment Tree:

- [cp-algorithms: segment tree](https://cp-algorithms.com/data_structures/segment_tree.html)
- <http://progcomp.cl/segmenttree>
- [youtube: Segment Tree Range Minimum Query](https://www.youtube.com/watch?v=ZBHKZF5w4YU)
- [Código de ejemplo](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/segment-tree.cpp)

## Segment Tree Lazy:

- [cp-algorithms: segment tree lazy](https://cp-algorithms.com/data_structures/segment_tree.html#toc-tgt-9)
- [youtube: Lazy Propagation Segment Tree](https://www.youtube.com/watch?v=xuoQdt5pHj0)
- [youtube: Segment Tree - Range Queries with Lazy Updates](https://www.youtube.com/watch?v=CN0N1ddJ9hA)
- [Código de ejemplo](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/segment-tree-lazy.cpp)

## Fenwick Tree (a.k.a. BIT o Binary Indexed Tree):
- (RECOMENDADO) [youtube: explicación de Jorge Pérez](https://youtu.be/0PzR0IoqkkU?t=2160)
    - <https://youtu.be/0PzR0IoqkkU?t=1453> (por si quieren ver la explicación de **sweep line** también que viene justo antes)
- (RECOMENDADO) [youtube: Fenwick Tree or Binary Indexed Tree](https://www.youtube.com/watch?v=CWDQJGaN1gY)
- [cp-algorithms: fenwick tree](https://cp-algorithms.com/data_structures/fenwick.html)
- [HackerEarth - binary indexed tree made easy](https://www.hackerearth.com/practice/notes/binary-indexed-tree-made-easy-2/)
- <http://progcomp.cl/fenwicktree>
- [cs.stackexchange: BIT: What is the intuition behind a binary indexed tree and how was it thought about?](https://cs.stackexchange.com/questions/10538/bit-what-is-the-intuition-behind-a-binary-indexed-tree-and-how-was-it-thought-a)
- [Topcoder: binary indexed trees](https://www.topcoder.com/community/data-science/data-science-tutorials/binary-indexed-trees/)
- Fenwick Tree 2D:
  - [geeksforgeeks - Two Dimensional Binary Indexed Tree or Fenwick Tree](http://www.geeksforgeeks.org/two-dimensional-binary-indexed-tree-or-fenwick-tree/)
  - [youtube: explicación de Jorge Pérez](https://youtu.be/0PzR0IoqkkU?t=4207)
  - [Topcoder: BIT 2D](https://www.topcoder.com/community/data-science/data-science-tutorials/binary-indexed-trees/#2d)
- Códigos de ejemplo:
    - [Fenwick tree 1D](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/fenwicktree.cpp)
    - [Fenwick tree 2D](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/fenwicktree2D.cpp)

## Union Find (a.k.a. DSU o Disjoint Set Union):

- [cp-algorithms: Disjoint Set Union](https://cp-algorithms.com/data_structures/disjoint_set_union.html)
- [youtube: Disjoint Sets using union by rank and path compression Graph Algorithm](https://www.youtube.com/watch?v=ID00PMy0-vE)
- [geeksforgeeks: Disjoint Set (Or Union-Find) \| Set 1 (Detect Cycle in an Undirected Graph)](https://www.geeksforgeeks.org/union-find/)
- [geeksforgeeks: Union-Find Algorithm \| Set 2 (Union By Rank and Path Compression)](https://www.geeksforgeeks.org/union-find-algorithm-set-2-union-by-rank/)
- [Código de ejemplo](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/unionfind.cpp)

## Treap:
- <https://cp-algorithms.com/data_structures/treap.html>

## Wavelet Tree:

- <https://www.dcc.uchile.cl/~jperez/papers/ioiconf16.pdf>
- [Código de ejemplo](https://github.com/PabloMessina/Competitive-Programming-Material/blob/master/Data_Structures/WaveletTree.cpp)

[Index](../index) > [Recursos](resources) > ```{{page.title}}```
