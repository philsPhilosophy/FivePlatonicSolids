# Five Platonic Solids

To prove that there are exactly 5 Platonic solids, we can follow a step-by-step process, based on the definition of a Platonic solid and using some basic geometric principles.

## Definition of a Platonic Solid:
A Platonic solid is a convex polyhedron with the following properties:
1. All faces are congruent regular polygons.
2. The same number of faces meet at each vertex.
3. The same number of edges meet at each vertex.

## Steps to Prove There Are Exactly 5 Platonic Solids:

### 1. Euler's Formula for Polyhedra:
Euler's formula for polyhedra is given by:

\[
V - E + F = 2
\]

where \( V \) is the number of vertices, \( E \) is the number of edges, and \( F \) is the number of faces. Euler's formula is true for any polyhedron.

### 2. Relationships between \( V, E, F, p, \) and \( q \):
- Let \( p \) be the number of edges at any vertex.
- Let \( q \) be the number of sides in the regular polygon that makes up the polyhedron.
- For any Platonic solid, at each vertex, \( p \) edges meet.
- Therefore, we may conclude that \( E = Vp \). However, since each edge is shared by two vertices, this counts each edge twice. Thus, we have:

\[
E = \frac{Vp}{2}
\]

- Similarly, for the relationship between \( F, q, \) and \( E \):
  - For any Platonic solid, \( q \) is the number of sides (or edges) in each face.
  - Therefore, \( E = Fq \). Again, since each edge is shared by two faces, this counts each edge twice. Thus, we have:

\[
E = \frac{Fq}{2}
\]

### 3. Combining Formulas (\( V - E + F = 2 \), \( E = \frac{Vp}{2} \), and \( E = \frac{Fq}{2} \)):
- Solving \( E = \frac{Vp}{2} \) for \( V \):

\[
V = \frac{2E}{p}
\]

- Solving \( E = \frac{Fq}{2} \) for \( F \):

\[
F = \frac{2E}{q}
\]

- Substituting these values into \( V - E + F = 2 \):

\[
\frac{2E}{p} - E + \frac{2E}{q} = 2
\]

- Dividing through by \( 2E \):

\[
\frac{1}{p} - \frac{1}{2} + \frac{1}{q} = \frac{1}{E}
\]

- Adding \( \frac{1}{2} \) to both sides:

\[
\frac{1}{p} + \frac{1}{q} = \frac{1}{2} + \frac{1}{E}
\]

### 4. Investigation of the Equation \( \frac{1}{p} + \frac{1}{q} = \frac{1}{2} + \frac{1}{E} \):
- Note that this equation must hold for any Platonic solid.
- Since \( E \geq 3 \) for any polyhedron, \( \frac{1}{E} > 0 \).
- Therefore:

\[
\frac{1}{p} + \frac{1}{q} > \frac{1}{2}
\]

### 5. Investigation of the Inequality \( \frac{1}{p} + \frac{1}{q} > \frac{1}{2} \):
- This inequality must hold for any Platonic solid.
- Since \( p \geq 3 \) and \( q \geq 3 \):
  - \( p = 3 \), \( q = 3 \):

    \[
    \frac{1}{3} + \frac{1}{3} > \frac{1}{2} \quad \text{(true, so this is a Platonic solid)}
    \]

  - \( p = 4 \), \( q = 3 \):

    \[
    \frac{1}{4} + \frac{1}{3} > \frac{1}{2} \quad \text{(true, so this is a Platonic solid)}
    \]

  - \( p = 5 \), \( q = 3 \):

    \[
    \frac{1}{5} + \frac{1}{3} > \frac{1}{2} \quad \text{(true, so this is a Platonic solid)}
    \]

  - \( p = 6 \), \( q = 3 \):

    \[
    \frac{1}{6} + \frac{1}{3} = \frac{1}{2} \quad \text{(false, so this is not a Platonic solid)}
    \]

  - \( p = 3 \), \( q = 4 \):

    \[
    \frac{1}{3} + \frac{1}{4} > \frac{1}{2} \quad \text{(true, so this is a Platonic solid)}
    \]

  - \( p = 3 \), \( q = 5 \):

    \[
    \frac{1}{3} + \frac{1}{5} > \frac{1}{2} \quad \text{(true, so this is a Platonic solid)}
    \]

### 6. There Are Only Five Possible Value Combinations of \( p \) and \( q \):
- From the analysis above, there are only 5 possible combinations for \( p \) and \( q \), corresponding to the 5 Platonic solids:
  - \( p = 3 \), \( q = 3 \): Tetrahedron
  - \( p = 4 \), \( q = 3 \): Octahedron
  - \( p = 5 \), \( q = 3 \): Icosahedron
  - \( p = 3 \), \( q = 4 \): Cube
  - \( p = 3 \), \( q = 5 \): Dodecahedron
