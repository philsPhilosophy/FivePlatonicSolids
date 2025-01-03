# FivePlatonicSolids
FivePlatonicSolids
To prove that there are exactly 5 Platonic solids, we can follow a step-by-step process, based on the definition of a Platonic solid and using some basic geometric principles.

### Definition of a Platonic Solid:
A Platonic solid is a convex polyhedron with the following properties:
1. All faces are congruent regular polygons.
2. The same number of faces meet at each vertex.
3. The same number of edges meet at each vertex.


### Steps to Prove There Are Exactly 5 Platonic Solids:

1. **Euler's Formula for Polyhedra:**
   Euler's formula for polyhedra is given by:
   \[
   V - E + F = 2
   \]
   where \( V \) is the number of vertices, \( E \) is the number of edges, and \( F \) is the number of faces. Euler's Formula is true for any Polyhedra.

2. **Relationships between \( V, E, F, p,\)  and \(q \).**
  - Let \(p =\) the number of edges at any vertex.
  - Let \(q =\) the number of sides in the regular polygon that makes up the polyhedron.
  - For any Platonic Solid, at each vertex is \(p\) edges. 
  - Therefore, we may conclude that \(E = Vp \), however if we notice that each edge is shared by two vertices, this will count each edge twice. Thus we have, 
\[ E = \frac{Vp}{2} \]
 - Similarly, lets investigate the relationship between \(F, q,\) and \(E\).
 - For any Platonic Solid, \(q\) is the number of sides in, or edges, in each face.
 - Therefore, we may conclude that \(E = Fq \), again though, each edge is shared by two faces, this will count each edge twice.
 - Thus we have,
\[ 
E = \frac{Fq}{2}

 \]

  
3. **Combining Formulas, \(V-E+F=2, E = \frac{Vp}{2},\) and \( E = \frac{Fq}{2} \)**
 - Solving \(E = \frac{Vp}{2}\), for \(V\) we get,
\[ 
V = \frac{2E}{p}
\]
  - Solving \(E = \frac{Fq}{2} \), for \(F\) we get,
\[
F = \frac{2E}{q}
\]
 - Substituting these values into \( V - E + F = 2 \) we get,
\[ 
\frac{2E}{p} - E + \frac{2E}{q} = 2
\]
 - We divide by \(2E\) on both sides to get,
\[
\frac{1}{p} - \frac{1}{2} + \frac{1}{q} = \frac{1}{E}
\]
 - Finally, we add the \( \frac{1}{2} \) to the other side.

\[
\frac{1}{p} + \frac{1}{q} = \frac{1}{2} + \frac{1}{E}
\]

4. **Investigation of the equation: \( \frac{1}{p} + \frac{1}{q} = \frac{1}{2} + \frac{1}{E} \).**
 - First note that this equation must be true for ANY Platonic Solid.
 - Now see that for any polyhedra \(E \geq 3 \), convince yourself of this fact.
 - Therefore, \( \frac{1}{E} \gt 0 \),
 - Clearly, \( \frac{1}{E} + \frac{1}{2} \gt \frac{1}{2} \)
 - Now seeing that \( \frac{1}{E} + \frac{1}{2} \) is the right side of our equation, this inequality applies to the left side,
\[ 
\frac{1}{p} + \frac{1}{q} \gt \frac{1}{2}
\]
5. **Investigation of the Inequality \(\frac{1}{p} + \frac{1}{q} \gt \frac{1}{2} \)**
 - Again, this inequality must be true for ANY Platonic Solid.
 - Since \(p \geq 3 \) and \(q \geq 3 \) , convince yourself of this fact. 
 -  \(p = 3 \) and \(q = 3 \).
    - Gives \(\frac{1}{3} + \frac{1}{3} \gt \frac{1}{2}\) which is true, therefore this could give a platonic solid.
 - \(p = 4\) and \(q = 3\).
     - Gives \(\frac{1}{4} + \frac{1}{3} \gt \frac{1}{2}\) which is true, therefore this could give a platonic solid.
- \(p = 5 \) and \(q = 3 \).
     - Gives \(\frac{1}{5} + \frac{1}{3} \gt \frac{1}{2}\) which is true, therefore  this could give a platonic solid.
- \(p= 6\) and \(q = 3\).
     - Gives \(\frac{1}{6} + \frac{1}{3} \gt \frac{1}{2}\) is FALSE since \(\frac{1}{6} + \frac{1}{3} = \frac{1}{2}\) , therefore this CANNOT be a platonic solid.
- \(p = 3 \) and \(q = 4\).
     - Gives \(\frac{1}{3} + \frac{1}{4} \gt \frac{1}{2}\) which is true, therefore  this could give a platonic solid.
- \(p = 3 \) and \(q = 5 \)
     - Gives \(\frac{1}{3} + \frac{1}{5} \gt \frac{1}{2}\) which is true, therefore  this could give a platonic solid.
- \(p = 3 \) and \(q = 6\)
     - Gives \(\frac{1}{3} + \frac{1}{6} \gt \frac{1}{2}\) is FALSE, therefore  this CANNOT be a platonic solid.
- \(p = 4 \) and \(q =4 \)
     - Gives \(\frac{1}{4} + \frac{1}{4} \gt \frac{1}{2}\) is FALSE, therefore  this CANNOT be a platonic solid.

5. **There are only Five Possible Value Combinations of \(p\) and \(q\).**
 - From above we should see that there are only 5 possible values for \(p\) and \(q\). 
 - Therefore, we have shown that there are only 5 Platonic Solids.
 - \(p = 3 \) and \(q = 3 \) is the Tetrahedron.
 - \(p = 4\) and \(q = 3\) is the Octahedron.
 - \(p = 5 \) and \(q = 3 \) is the Icosahedron.
 - \(p = 3 \) and \(q = 4\) is the Cube.
 - \(p = 3 \) and \(q = 5 \) is the Dodecahedron.

