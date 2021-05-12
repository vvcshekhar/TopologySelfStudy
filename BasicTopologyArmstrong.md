# Basic Topology
M. A. Armstrong

## Chapter 1 Introduction

### Euler's Theorem
Conventions and definitions:
1. A _polyhedron_ refers to the surface that bounds a "solid", i.e., it is a finite collection of plane polygons that fit together.
2. If two polygons meet, they do so in a common edge, and each edge of a polygon lies in precisely one other polygon.
3. If we consider the polygons that contain a particular vertex, then we can label the polygons $Q_1, Q_2, \dots , Q_k$ such that $Q_i$ has an edge in common with $Q_{i+1}$ for $1 \leq i < k$, and $Q_k$ has an edge in common with $Q_1$. This rules out, for example, two cubes joined together at a single vertex.

**Euler's Theorem**. Let $P$ be a polyhedron which satisfies:
(a) Any two vertices of $P$ can be connected by a chain of edges.
(b) Any loop on $P$ which is made up of straight line segments (not necessarily of edges) separates $P$ into two pieces.
Then $v - e + f = 2$ for $P$.

### Topological Equivalence
