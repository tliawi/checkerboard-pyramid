# quincunx-pyramid
A study of the quincunx (or checkerboard) pyramid data structure:

>A quincunx pyramid is a connected graph represented as an implicit data structure within a two-dimensional array. A quincunx pyramid is balanced, in that each node has two parents and four children...

>It is striking that the quincunx pyramid is not just a graph, it is a graph that has a Euclidean geometry. That is, each node’s [row, column] array index not only determines the implicit links to its two parents and four children, but also determines a meaningful location in the plane. This geometry leads to interesting applications...

From the white paper [The Quincunx Pyramid](https://drive.google.com/open?id=1C_2Oy4wpvf8gNk4AH4UV7v6LLSFd9heF85NJPLOfrK0) which uses many illustrations derived in [this project's web app](https://tliawi.github.io/quincunx-pyramid/). Given an image of a dot pattern, the web app calculates an approximation to the Voronoi diagram using an algorithm that admits of a massively parallel implementation using a circuit switched network on a chip.
