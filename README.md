# quincunx-pyramid
A study of the quincunx (or checkerboard) pyramid data structure:

>A quincunx pyramid is a connected graph represented as an implicit data structure within a two-dimensional array. A quincunx pyramid is balanced, in that each node has two parents and four children...

>It is striking that the quincunx pyramid is not just a graph, it is a graph that has a Euclidean geometry. That is, each node’s [row, column] array index not only determines the implicit links to its two parents and four children, but also determines a meaningful location in the plane. This geometry leads to interesting applications...

From the white paper [The Quincunx Pyramid](https://docs.google.com/document/d/11RjqjuvjJlTw8JSmGqyyEiPCy0nd3gDQn6WKBdxchXw) which uses many illustrations derived in [this project's web app](https://tliawi.github.io/quincunx-pyramid/). Given an image of a dot pattern, the web app calculates an approximation to the Delaunay triangulation in one pass through a 2D array essentially the same size as the image.
