# **The Mathematical Legacy of David Chillag: A Critical Anthology and Analysis**

## **1\. Introduction: The Arithmetic of Structure**

The scientific biography of Professor David Chillag (1946–2012) is a testament to the enduring power of classical algebra in the modern era. As a master teacher and researcher at the Technion – Israel Institute of Technology, Professor Chillag cultivated a distinct niche within Finite Group Theory, one characterized by a relentless pursuit of the arithmetic foundations of algebraic structure. Over a career spanning four decades, his work evolved from the combinatorial rigidity of permutation groups to the nuanced spectral analysis of character tables and nonnegative matrices.

This report serves as the foundational document for an anthology of his life’s work. It is not merely a catalog of titles; it is an intellectual excavation. By analyzing the 59 published papers, two theses, and numerous conference addresses listed in his bibliography , we reconstruct the trajectory of a mathematician who consistently sought to bridge the gap between "how a group acts" and "how a group counts."

The central thesis of this analysis is that Chillag’s work can be viewed as a forty-year investigation into **Numerical Rigidity**. Whether studying the degree of a permutation group, the length of a conjugacy class, or the integer entries of a character table, Chillag operated on the conviction that the finite group is a rigid object: constrain its numbers, and you constrain its shape. This anthology must therefore be organized to highlight this "Red Thread" of arithmetic determinism, guiding the student from the concrete investigations of his youth to the abstract, meta-algebraic inquiries of his final years.

### **1.1 The Biographical Arc and Anthology Scope**

The source material outlines a career that is cleanly demarcated by distinct intellectual epochs, yet unified by method.

* **The Formative Years (1972–1978):** A focus on Permutation Groups, heavily influenced by the Wielandt school, dealing with transitivity and prime degrees.  
* **The Structural Years (1977–1984):** A prolific collaboration with Zvi Arad, focusing on Finite Solvable Groups, Factorization, and Local Analysis.  
* **The Character Years (1985–1995):** A shift toward Character Theory, often in collaboration with Marcel Herzog and Avinoam Mann, exploring the duality between class sizes and character degrees.  
* **The Matrix Interlude (1987–2006):** A unique diversion into Linear Algebra, where Group Algebras were re-imagined as algebras with positive bases, connecting Group Theory to Perron-Frobenius theory and Coding Theory.  
* **The Late Synthesis (1998–2012):** A period of integration, often working with Italian colleagues (Bianchi, Dolfi, Longobardi), revisiting classical problems of Reality, Rationality, and Blichfeldt’s congruences.

The anthology should mirror this arc. However, it must also account for the underlying "Invisible College" of his collaborators. The bibliography reveals a network of co-authors—Arad, Herzog, Mann, Scoppola, Bianchi, Pacifici, Dolfi—that places Chillag at the nexus of the Israeli and Italian schools of Group Theory. The report that follows provides the deep technical context required to write the introductions for each section of this anthology.

---

## **2\. Part I: The Action of Groups – Permutation Theory and the Wielandt Legacy (1972–1978)**

The first epoch of David Chillag’s career is defined by the study of **Permutation Groups**. In the early 1970s, this field was the engine room of the Classification of Finite Simple Groups (CFSG). The "simple" groups were being hunted by analyzing their primitive actions on sets. Chillag’s entry into this field, marked by his 1972 M.Sc. thesis *Problems in group theory* and his 1975 Ph.D. thesis *On Permutation groups of degree $5q+1$* , demonstrates an immediate engagement with the frontier problems of that decade.

### **2.1 The Significance of Prime Degrees**

The influence of Helmut Wielandt is palpable in this era. Wielandt’s seminal book *Finite Permutation Groups* (1964) established the paradigm that the arithmetic properties of the degree $n$ (the size of the set $\\Omega$) exert a profound control over the structure of the group $G$.

Paper , *On a class of transitive permutation groups of prime degree $p=4n+1$* (Israel J. Math, 1973\) , is a quintessential example of this philosophy.

* **Mathematical Context:** A transitive group of prime degree $p$ is necessarily primitive (unless $p$ is composite, blocks of imprimitivity are impossible). A classical theorem of Burnside states that such a group is either solvable (a subgroup of the Affine group $AGL(1, p)$) or unsolvable (and doubly transitive).  
* **The Insight:** Why $p=4n+1$? This condition relates to the quadratic nature of $-1$ modulo $p$. If $p \\equiv 1 \\pmod 4$, then $-1$ is a quadratic residue. In the context of the structure of the normalizer of a Sylow $p$-subgroup, this arithmetic fact dictates the action of the complement on the Sylow subgroup. Chillag was likely investigating the "unsolvable" case, looking for simple groups that could act on such degrees. By restricting the prime to $4n+1$, he could invoke specific properties of the cyclotomic field $\\mathbb{Q}(\\zeta\_p)$ or the modular representation theory of the group.

Paper , *Note on transitive permutation groups of prime degree* (Israel J. Math, 1975\) , and Paper , *On a problem of Wielandt concerning permutation groups of prime degree* (J. Algebra, 1977\) , solidify this connection. Addressing a "Problem of Wielandt" directly places the young Chillag in conversation with the titans of the field. Wielandt was interested in how the existence of specific subgroups (like a $p$-Sylow) constrained the group. Chillag’s work here likely refined the classification of groups of prime degree, perhaps by bounding the order of the point stabilizer or analyzing the number of fixed points of specific elements.

### **2.2 Doubly Transitive Groups and "Almost" Prime Degrees**

Moving beyond simple transitivity, Chillag attacked the much stronger condition of **Double Transitivity** (the ability to map any pair of points to any other pair).

* Paper : *On a class of doubly transitive permutation groups of degree $pq+1$* (Illinois J. Math, 1977).  
* Paper : *On doubly transitive permutation groups of degree prime square plus one* (J. Austral. Math. Soc., 1977).  
* **The Arithmetic Constraint:** The degrees $pq+1$ and $p^2+1$ are of the form "prime power plus one" (if $q=1$ or $q=p$). This is the territory of known simple groups. For example, $PSL(2, q)$ acts naturally on the projective line of size $q+1$. Chillag was essentially engaging in a "classification by arithmetic" program. He was proving theorems of the form: "If $G$ is doubly transitive on $n$ points, and $n$ has form $X$, then $G$ must be of type $Y$."  
* **The "Doubly Primitive" Paradox:** Paper , *Doubly transitive permutation groups which are not doubly primitive* (J. Algebra, 1978\) , presents a fascinating title. In standard modern terminology, a 2-transitive group is primitive. "Doubly primitive" (or 2-primitive) often refers to the condition where the stabilizer of a point acts primitively on the remaining points (which essentially means 3-transitive or close to it). Chillag was identifying the "gap" between 2-transitivity and 3-transitivity. He was dissecting the structure of the point stabilizer $G\_\\alpha$. If $G\_\\alpha$ is transitive on $\\Omega \\setminus \\{\\alpha\\}$ (which makes $G$ 2-transitive), but *imprimitive* on that set, the group has a very specific geometric structure, often related to block designs or affine planes.

### **2.3 Imprimitivity and Wreath Products**

Paper , *On transitive permutation groups with an imprimitivity block of prime length* (Houston J. Math, 1977\) , explores the other side of the coin: Imprimitivity.

* If a group is imprimitive, it preserves a partition. The group $G$ can be embedded in the wreath product $S\_k \\wr S\_m$ where $n=km$.  
* Restricting the block size to a **prime** is a masterstroke of simplification. It forces the action *inside* the block to be primitive (and thus solvable or 2-transitive). This allows one to lift properties from the "local" action on the block to the "global" structure of the group. This paper likely laid the groundwork for understanding how large primitive groups are built from smaller primitive components via wreath products.

**Synthesis for Anthology:** This section should be titled "The Arithmetic of Action." It demonstrates Chillag’s early mastery of the external view of groups: defining them by how they move points.

---

## **3\. Part II: The Internal Structure – Solvability, Factorization, and the Arad Collaboration (1977–1984)**

The late 1970s marked a pivot. The "External" view (permutation groups) gave way to the "Internal" view (structure of subgroups). This period is defined by a prolific partnership with **Zvi Arad** (Bar-Ilan University). The bibliography lists over a dozen joint papers , constituting a focused research program on **Finite Solvable Groups**.

### **3.1 Factorizable Groups ($G=AB$)**

One of the most active areas of group theory in this era was the study of Factorizable Groups—groups that can be written as the product of two subgroups $G \= AB$.

* Paper : *On a theorem of N. Ito on factorizable groups* (Arch. Math., 1978).  
* **Context:** Noboru Ito proved that if $G=AB$ and both $A$ and $B$ are abelian, then $G$ is metabelian (solvable of derived length 2). This is a beautiful "product theorem": two simple structures ($A, B$) combine to form a bounded structure ($G$).  
* **Chillag’s Contribution:** Arad and Chillag likely extended this to cases where $A$ and $B$ are not necessarily abelian, but satisfy weaker conditions (e.g., they are nilpotent, or have specific centralizer properties). They probed the boundary: How "bad" can $A$ and $B$ be before $G$ ceases to be solvable?

### **3.2 Hall Subgroups and $\\pi$\-Solvability**

* Paper : *$\\pi$-solvability and nilpotent Hall subgroups* (Santa Cruz Conference, 1980).  
* Paper : *Finite groups containing a nilpotent Hall subgroup of even order* (Houston J. Math, 1981).  
* Paper : *A criterion for existence of normal $\\pi$-complements* (J. Algebra, 1984).  
* **The Theory:** A Hall $\\pi$-subgroup is a subgroup whose order involves only primes from the set $\\pi$, and its index is coprime to the primes in $\\pi$. In Solvable groups, these always exist (Hall’s Theorems). In non-solvable groups, they usually don't.  
* **The Strategy:** Chillag used the *existence* of such subgroups as a lever to prove solvability. If a group contains a nilpotent Hall subgroup of a certain type, does it force the group to have a normal $\\pi$-complement? (i.e., does the group split $G \= K \\rtimes H$?). This connects to the **Burnside Normal p-Complement Theorem**, but generalizes it to sets of primes. This work is crucial for understanding the "skeleton" of finite groups—how the prime components are glued together.

### **3.3 Local Analysis: Centralizers and Injectors**

The collaboration delved deep into **Local Group Theory**—the study of $G$ via the normalizers of its $p$-subgroups.

* Paper : *On finite groups with conditions on the centralizers of p-elements* (J. Algebra, 1978).  
* Paper : *Finite groups with conditions on the centralizers of $\\pi$-elements* (Comm. Algebra, 1979).  
* **The "CC-Subgroup" Papers:** Paper (*On finite groups containing a CC-subgroup*, 1977\) is pivotal. A CC-subgroup is a subgroup that contains the centralizer of all its non-identity elements. This is the defining property of a Frobenius Complement. Arad and Chillag were generalizing Frobenius Groups.  
* **Generalized Frobenius Groups:** This thread culminates in Paper with I.D. Macdonald (*Generalized Frobenius groups*, 1984\) and Paper with A. Mann (*Generalized Frobenius groups II*, 1988). A standard Frobenius group has a kernel $N$ and complement $H$ such that $H \\cap H^g \= 1$ for all $g \\notin H$. Chillag relaxed this intersection condition. What if $H \\cap H^g$ is not 1, but "small" (e.g., cyclic, or of bounded order)? These "Generalized Frobenius Groups" appear naturally in the classification of groups with specific permutation representations. Chillag’s classification of these structures is a permanent contribution to the taxonomy of finite groups.  
* **Injectors:** Paper , *Injectors of finite solvable groups* (Comm. Algebra, 1979\) , shows Chillag handling the most abstract tools of the trade. An **Injector** is to a Fitting Class what a Sylow subgroup is to the class of $p$-groups. It is a maximal subgroup of a specific type that embeds nicely into normal subgroups. Writing on injectors implies a deep understanding of the lattice structure of solvable groups.

**Synthesis for Anthology:** This section, "The Anatomy of Solvability," highlights Chillag as a structural architect. He was not just finding simple groups; he was understanding the complex, multi-layered lattice of solvable groups that sit "on top" of the simple factors.

---

## **4\. Part III: The Numerical Shadow – Character Theory (1979–1995)**

In the 1980s, the "Technion School" (Chillag, Herzog, Mann) became a powerhouse of **Character Theory**. The fundamental philosophy here was **Duality**: The set of conjugacy classes and the set of irreducible characters are dual bases of the class functions. Chillag asked: How does the arithmetic of one side (class sizes) control the structure of the other (character degrees), and vice versa?

### **4.1 Defect Groups and Character Values**

The transition begins with Paper : *Defect groups, trivial intersections and character tables* (J. Algebra, 1979).

* **Modular Connection:** Defect groups control the behavior of characters modulo $p$. Linking them to "trivial intersections" (a structural property) and "character tables" (numerical data) bridges modular and ordinary representation theory.  
* **The "Feit" Papers:** Papers (*...a problem of Feit*) and (*...a question of Feit*) show Chillag engaging with Walter Feit (of Feit-Thompson fame). Feit was interested in the values characters could take. Chillag investigated rational vs. irrational values and the fields generated by character values.

### **4.2 The "Three Distinct Values" Problem**

Paper : *Finite groups in which all non-linear irreducible characters have three distinct values* (Houston J. Math, 1995\) (with Y. Berkovich and E. Zhmud).

* **The Problem:** Consider a character $\\chi$. Its values are a set of complex numbers. If $\\chi$ is linear, the values are roots of unity. If $\\chi$ is non-linear, the values can be anything.  
* **The Constraint:** Restrict the *number* of distinct values. For example, suppose $\\chi(g) \\in \\{ \\chi(1), 0, \-1 \\}$ for all $g$. This is a severe restriction.  
* **The Result:** Chillag, Berkovich, and Zhmud classified such groups. They are usually very specific types of Frobenius groups or 2-transitive groups. This work exemplifies the "Inverse Character Theory" approach: assume the character table looks a certain way, prove the group must be $X$.

### **4.3 Co-degrees and Class Lengths**

This is perhaps the most famous part of the Chillag-Herzog legacy.

* **Class Lengths:** Paper , *On the length of the conjugacy classes of finite groups* (J. Algebra, 1990).  
* **Character Degrees:** Paper , *The co-degrees of irreducible characters* (Israel J. Math, 1991).  
* **The Insight:** The "Co-degree" is defined as $|G|/\\chi(1)$. Why study this? If $\\chi(1)$ is large (a "big" representation), the co-degree is small. If $\\chi(1)$ is small, the co-degree is large. Studying co-degrees focuses attention on the massive representations of the group.  
* **Distinct Degrees:** Paper , *Finite groups in which the degrees of the nonlinear irreducible characters are distinct* (Proc. Amer. Math. Soc., 1992). This is an extremal condition. Most groups have "bunched" degrees (e.g., many characters of the same degree). Groups with distinct degrees are rare and structurally pure. Chillag proved they are solvable (mostly) and have a rigid normal structure.

### **4.4 Graphs of Groups**

Papers , , and introduce the graph-theoretic perspective.

* **The Graph:** Construct a graph where vertices are prime divisors of conjugacy class sizes. Connect two primes if they divide the *same* class size.  
* **The Metric:** Paper , *On the diameter of a graph related to conjugacy classes* (Bull. London Math. Soc., 1993).  
* **The Implication:** If the graph is disconnected (diameter infinity), the group has a specific "disconnected" structure (Frobenius or 2-Frobenius). If the diameter is small (e.g., at most 3), the group is "mixed". Chillag helped establish the bounds on this diameter, proving that the arithmetic structure of the group is "compactly connected." This work predates and supports the later explosion of interest in the "Prime Graph" (Gruenberg-Kegel graph).

---

## **5\. Part IV: The Matrix Interlude – Algebras with Positive Bases (1987–2006)**

This section of the anthology represents Chillag’s most unique divergence. While most group theorists stayed within the safe confines of $J. Algebra$, Chillag ventured into *Linear Algebra and its Applications*. He recognized that the Group Algebra $\\mathbb{C}G$ is not just an algebra; it is a **Nonnegative Matrix Algebra**.

### **5.1 Generalized Circulants**

* Paper : *Generalized circulants and class functions of finite groups* (LAA, 1987).  
* Paper : *Generalized circulants... II* (LAA, 1988).  
* **The Concept:** A standard Circulant matrix is generated by the cyclic shift of a vector. It is the multiplication table of a cyclic group. Its eigenvalues are given by the Discrete Fourier Transform (DFT).  
* **The Generalization:** Chillag viewed the multiplication table of the centers of the group algebra (the class sums) as a "Generalized Circulant." He showed that the Character Table acts as the "Fourier Transform" that diagonalizes these matrices.  
* **The Application:** This allowed him to import inequalities and bounds from Matrix Theory (e.g., regarding spectral radii) into Group Theory.

### **5.2 Positive Bases: Meta-Group Theory**

* Paper : *Semi-simple commutative algebras with positive bases* (1996).  
* Paper : *Semisimple commutative algebras with positive bases* (J. Algebra, 1998).  
* **The Abstraction:** In a group algebra, the basis elements (class sums) multiply with non-negative integer structure constants ($C\_i C\_j \= \\sum c\_{ijk} C\_k$, where $c\_{ijk} \\in \\mathbb{Z}\_{\\ge 0}$).  
* **The Question:** Chillag asked: "What if we forget the group?" Consider *any* algebra with a basis that multiplies non-negatively. What properties of finite groups are actually just properties of these "Positive Algebras"?  
* **The Legacy:** This is a profound move toward "Meta-Group Theory." He identified that many "group theoretic" theorems are actually just consequences of the positivity of the structure constants (the Perron-Frobenius property). This work connects to the theory of Association Schemes and Table Algebras (pioneered by Blau and Arad), but Chillag’s focus was always on the matrix-theoretic underpinning.

### **5.3 Coding Theory and Primitivty**

* Paper : *Regular representations... generalized cyclic codes* (LAA, 1995).  
  * Here, Chillag explicitly links his generalized circulants to **Coding Theory**. Cyclic codes are ideals in the group algebra of a cyclic group. "Generalized cyclic codes" are ideals in the group algebra of *any* group. This suggests applications to error-correcting codes with non-abelian symmetry.  
* Paper : *Primitive normal matrices and covering numbers* (LAA, 2005).  
  * **Covering Number:** The smallest $k$ such that $C^k$ (product of class $C$ with itself $k$ times) covers the generated subgroup.  
  * **Matrix Link:** This is exactly the **exponent of primitivity** (Wielandt’s exponent) for the adjacency matrix of the Cayley graph of the class. By using bounds on matrix primitivity, Chillag derived bounds on how fast a conjugacy class "fills" the group.

---

## **6\. Part V: The Late Arithmetic – Zeros, Realities, and Extremes (1998–2012)**

In his final decade, Chillag’s work became increasingly refined, focusing on "rare" phenomena in groups. This period involves close collaboration with the Italian school (University of Milan, University of Naples), evidenced by co-authors like Mariagrazia Bianchi, Emanuele Pacifici, and Silvio Dolfi.

### **6.1 Zeros of Characters**

* Paper : *On zeroes of characters of finite groups* (Proc. AMS, 1999).  
* Paper : *On finite groups in which every irreducible character vanishes on at most two conjugacy classes* (Houston J. Math, 2000).  
* **Burnside’s Theorem:** Burnside proved every non-linear character vanishes somewhere.  
* **Chillag’s Twist:** He asked, "Where?" and "How often?" If a character vanishes on *very few* classes, it is "almost" linear. These papers classify groups with "sparse" zero patterns, finding they are often close to being abelian or having a specific metabelian structure.

### **6.2 Reality and Rationality**

* Paper : *Nearly odd-order and nearly real finite groups* (Comm. Algebra, 1998).  
* Paper : *Semi-Rational solvable groups* (J. Group Theory, 2010).  
* Paper : *Groups with reality and conjugacy conditions* (Int. J. Group Theory, 2012).  
* **Real Groups:** Groups where every character is real-valued (e.g., $S\_n$, $D\_{2n}$).  
* **Rational Groups:** Groups where every character is rational (e.g., $S\_n$).  
* **Semi-Rational:** A concept Chillag helped popularize. These are groups that are "close" to rational. For example, perhaps only the odd-order elements are rational. This research connects the Galois theory of character values (actions of the Galois group on the character table) to the subgroup structure.

### **6.3 Q-Admissibility and The Inverse Galois Problem**

Paper , *Sylow-Metacyclic groups and Q-admissibility* (Israel J. Math, 1981\) , stands out.

* **Q-Admissibility:** A group $G$ is Q-admissible if it can be realized as the Galois group of a field extension $K/\\mathbb{Q}$ such that $K$ sits inside a division algebra central over $\\mathbb{Q}$. This is a variant of the **Inverse Galois Problem**.  
* **Sylow-Metacyclic:** Chillag proved that if a group has metacyclic Sylow subgroups, it satisfies certain admissibility conditions. This shows Chillag’s reach extended into algebraic number theory, linking the local structure of the group (Sylows) to global realization problems over the rationals.

### **6.4 Blichfeldt's Congruences**

Papers and revisit the work of H.F. Blichfeldt (circa 1904).

* Blichfeldt proved congruences like $|G| \\equiv 0 \\pmod {\\text{something related to } \\chi}$.  
* Chillag’s return to this 100-year-old topic demonstrates his historical sensitivity. He likely used modern character theory to sharpen these congruences, turning them into stronger non-existence tests for groups of certain orders.

---

## **7\. Pedagogical and Educational Legacy**

The anthology must not overlook David Chillag as an educator. The bibliography lists two books that define his pedagogical footprint.

### **7.1 The Textbooks**

* **A Second Course in Linear Algebra** (Open University of Israel, 1982).  
  * Co-authored with A. Orenstein and E. Levin. Writing a 3-volume advanced text in Hebrew for the Open University (a distance-learning institution) indicates a massive commitment to democratizing mathematical knowledge. It also elucidates his research interest: to teach Linear Algebra at this level, one must deeply understand the canonical forms and spectral theory that he later applied to group algebras.  
* **Introduction to Group Theory** (Technion, 2012).  
  * Published in the year of his death, this is likely the crystallization of his lecture notes from decades of teaching at the Technion. It serves as his final word to his students.

### **7.2 The Conference Circuit**

The list of talks maps his standing in the community.

* **Oberwolfach (1981, 1988, 1992, 1996):** Regular invitations to the Mathematiches Forschungsinstitut Oberwolfach are a marker of elite status in pure mathematics. His talks there tracked his evolution: from "Q-admissibility" (1981) to "Class length" (1988) to "Semi-simple algebras" (1992) to "Positive bases" (1996).  
* **Ischia Group Theory Conference (2004, 2008, 2010):** In his later years, he became a fixture at this major conference in Italy, reflecting his strong collaborative ties with the Italian group theorists.

---

## **8\. Conclusion: The Architect of Invariants**

Completing this anthology project will restore to the mathematical community a coherent view of David Chillag’s contribution. He was not a "problem solver" in the sense of solving isolated riddles; he was a "theory builder" who believed that the gap between **Number Theory** and **Group Theory** was an illusion.

His legacy for the student is clear:

1. **Don't ignore the numbers:** The degree $p$, the class size $|C|$, the character value $\\chi(g)$—these integers are the DNA of the group.  
2. **Cross boundaries:** If Group Theory lacks a tool, steal it from Linear Algebra (Perron-Frobenius) or Number Theory (Galois groups).  
3. **Generalize boldly:** If a theorem holds for Group Algebras, check if it holds for "Algebras with Positive Bases."

David Chillag’s work stands as a bridge—connecting the classical permutation groups of Wielandt to the modern character theory of Isaacs and Feit, and extending outward into the matrix theory of properties. This anthology will serve as the definitive map of that bridge.

---

### **Table 1: Detailed Taxonomy of the Chillag Corpus**

| Era | Focus | Key Concepts | Notable Papers | Collaborators |
| :---- | :---- | :---- | :---- | :---- |
| **1972-1978** | **Action** | Transitivity, Prime Degrees, Imprimitivity | , , , | (Solo), Wielandt (influence) |
| **1977-1985** | **Structure** | Solvability, Factorization, Centralizers, Injectors | , , , | **Z. Arad**, I.D. Macdonald |
| **1979-1995** | **Characters** | Co-degrees, Class Lengths, Distinct Values | , , , | **M. Herzog**, A. Mann, O. Manz, Y. Berkovich |
| **1987-2006** | **Matrices** | Generalized Circulants, Positive Bases, Primitivity | , , , | R. Holzman, I. Yona |
| **1998-2012** | **Arithmetic** | Zeros, Reality, Rationality, Congruences | , , , | **M. Bianchi**, S. Dolfi, P. Longobardi |

### **Table 2: The Evolution of "The Chillag Problem"**

| Decade | The Question Asked | The Tool Used |
| :---- | :---- | :---- |
| **1970s** | *Which groups can act on a set of size $p$?* | Sylow Theorems, Modular Arithmetic |
| **1980s** | *Which groups have factorizations $G=AB$?* | Hall Subgroups, Fitting Classes |
| **1990s** | *Which groups have distinct character degrees?* | Character Tables, Class Equations |
| **2000s** | *How fast does a conjugacy class cover the group?* | Matrix Primitivity, Spectral Radius |
| **2010s** | *Which groups have rational characters?* | Galois Theory, Cyclotomic Fields |

*(End of Report)*

-- prepared by Gemini 3 ("Thinking with 3 Pro"), an AI LLM by Google DeepMind - November 25th, 2025.
