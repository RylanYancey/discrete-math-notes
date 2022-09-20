# 1.1 Sets

  **Set** $A$ = $\\{1, 2, 4, 3, 5\\}$ => unordered collection of unique elements
  
  Sets have domains, and are generally represented with the table below. 
  | Symbol | Set | Example of Members |
  |:------:|:---:|:------------------:|
  |$\textbf{Z}$ | Integers | $-3, 2, 7, -10, 0$|
  |$\textbf{Q}$| Rational Numbers | $-1/3, 2/5, 0, 5$ |
  |$\textbf{R}$| Real Numbers | $\pi, 5/3, \sqrt{2}, 2.445$|
  
   A custom domain, the **universe**, can also  be specified. This is denoted as $U$. 
  
  The $nonneg$ subscript can be applied to one of the above symbols to exclude negative numbers, but not zero. $Z_{nonneg}$\
  The $+$ or $-$ superscript can be applied to show either all positive numbers or all negative numbers (excluding zero). $Z^+$
  
  **Cardinality** refers to the amount of items in a set. $A = \\{1, \\{2, 3\\}\\}$ has a cardinality of 2. Cardinality is denoted as $|X|$
  
  **Set Union** Is a set that is every element in the sets being unioned.
  $$A = \\{1, 2, 3, 4\\} B = \\{4, 5\\}$$ $$A \cup B = \\{1, 2, 3, 4, 5\\}$$ 
  **Set Intersection** Is a set that is every duplicate element between two tests. 
  $$A = \\{1, 2, 3, 4\\} B = \\{4, 5\\}$$ $$A \cap B = \\{4\\}$$
  
  A **Subset** is a set whose elements are all within another. A subset can also be equal to the other set. 
  $$A = \\{1, 2, 3, 4\\}$$ $$B = \\{1, 2, 3\\}$$ $$A \subseteq B$$
  
  A **Proper Subset** is the same as a Subset, but the subset cannot be equal to the other. 
  
  Sets have laws associated with them[^1].
  | Law Name | Union | Intersection|
  |:--------:|:--------|:--------|
  |Associative| $(A \cup B) \cup C = A \cup (B \cup C)$ | $(A \cap B) \cap C = A \cap (B \cap C)$|
  |Commutative| $A \cup B = B \cup A$ | $A \cap B = B \cap A$|
  |Distributive| $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$ | $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$|
  |Identity| $A \cup \emptyset = A$ | $A \cap U = A$ |
  |Idempotent| $A \cup A = A$ | $A \cap A = A$ |
  |Complement| $A \cup \bar{A} = U$ | $A \cap \bar{A} = \emptyset$ |
  |De Morgan's Set Law| $\bar{(A \cup B)} = \bar{A} \cap \bar{B}$ | $\bar{(A \cap B)} = \bar{A} \cup \bar{B}$ |
  
# 1.2 Propositions

  A sentence that is either *True* or *False* is a proposition. 
  Propositions are also called Logical Expressions. 
  Propositional operators are evaluated using truth tables and can be chained to form more complex logic. 
  
  **Conjunction**: $p \wedge q$ => p and q\
  **Disjunction**: $p \lor q$ => p or q
  
  Conjunction, or AND propositions, have this truth table:
  |P|Q||
  |:-:|:-:|:-:|
  |T|T|T|
  |T|F|F|
  |F|T|F|
  |F|F|F|
  
  Disjunction, or OR propositions, have this truth table:
  |P|Q||
  |:-:|:-:|:-:|
  |T|T|T|
  |T|F|T|
  |F|T|T|
  |F|F|F|

  In Java, Conjunction is represented by &&, and Disjunction by ||. 
  
  **Negating Propositions** When you negate a propositon, you take the inverse of its truth value. Denoted $\neg{p}$. 

# 1.3 Conditional Propositions and Logical Equivalence

**Conditional Propositions** are denoted $p \rightarrow q$, and read "If p, then q". 
P is the **Hypothesis**, and Q is the **Conclusion**. 

The Truth Table for a Conditional Proposition looks like this[^2]:
  |P|Q||
  |:-:|:-:|:-:|
  |T|T|T|
  |T|F|F|
  |F|T|T|
  |F|F|T|

If you're confused on why FT and FF is True, think of it this way. We've only said, if P, then Q, we never what would happen if P was false. So, TF is false because it disproves our proposition. FT and FF don't disprove the proposition.  

A Conditional Proposition that is true because the Hypothesis is false is known as **True by Default** or **Vacously True**. 

The **Converse** of a Conditional Proposition is reversing the Conclusion and the Hypothesis. For example, the converse of $p \rightarrow q$ is $q \rightarrow p$. 

The If and Only If Operator is used to denoted 

# 1.4 Arguments and Rules of Inference



# 1.5 Quantifiers

# 1.6 Nested Quantifiers

# Footnotes

  [^1]: Page 8 - Theorem 1.1.22
  [^2]: Page 21 - Definition 1.3.3
