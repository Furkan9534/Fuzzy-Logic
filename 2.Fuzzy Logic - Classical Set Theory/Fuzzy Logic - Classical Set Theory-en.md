# Fuzzy Logic - Classical Set Theory
---
## Purpose

A set is an unordered collection of distinct elements. The elements of a set can be written as a list using curly braces. If the order of the elements is changed, or if any element of the set is repeated, nothing changes in the set.

---
 ## Mathematical Representation of a Set

Roster or Tabular Form
In this format, a set is written as a list of all its elements. The elements are enclosed in curly braces and separated by commas.

in Roster or Tabular Form:

Alphabet Set: A = {x,y,z,t,w,v,y}

Number Set: B = {1,2,3,4,5,6,7}

---
## Set Constructor Notation

Set elements are defined by a common property. A is defined as A = {x:p(x)}.

Example: The set {1,3,5,7,9} is written as follows:

B = {x:1 ≤ x < 10 and (x%2) ≠ 0}

## Cluster Builder
 The elements of a set are defined by a common property. A set A is defined as A = {x:p(x)}.

Example: The set {1,3,5,7,9} is written as:

B = {x:1 ≤ x < 10 and (x%2) ≠ 0}

---
## Cardinality of a Set
The number of elements in a set is denoted by |S|. This number is called the cardinal number. If a set has infinitely many elements, then the number of elements is infinite.

Let X and Y be two sets. The expression |X| = |Y| shows that X and Y have the same number of elements. This is true if the two sets have an equal number of elements. Mathematically, this means that there exists a one-to-one and onto function f from X to Y.

The expression |X| ≤ |Y| indicates that the number of elements in set X is less than or equal to the number of elements in set Y. Therefore, a one-to-one function f exists from X to Y.

The expression |X| < |Y| indicates that the number of elements in set X is less than the number of elements in set Y. Here, the function f defined from X to Y is an injective function, but not a biective function.

If |X| ≤ |Y| and |X| ≤ |Y|, then |X| = |Y|. The sets X and Y are often referred to as equivalent sets.

## Cluster Types
There are many types of sets. Some examples include finite sets, infinite sets, subsets, universal sets, proper sets, and single-element sets.
## Finite Set
A set containing a specific number of elements is called a finite set.

Example: − S = {x|x ∈ N and 55 > x > 50}

## Infinite Set
A set containing an infinite number of elements is called an infinite set.

Example: − S = {x|x ∈ N and x > 5}
## Subset
A set X is a subset of a set Y (X ⊆ Y) if every element of X is also an element of Y.

Example 1: Let X = {1,2,3,4} and Y = {1,2}. Here, Y is a subset of X because all elements of Y are in X. Therefore, it is written as Y⊆X.

Proper Subset
A proper subset is a subset of a set that is not equal to it. X is a proper subset of Y if all elements of X are in Y and X is not equal to Y.

Example: Let X = {1,2,3,4,5,6} and Y = {1,2}. Here, Y ⊂ X because all elements in Y are also in X, and X has at least one element greater than Y.

## Universal Set

The universal set is the largest set containing all the elements of a given subject, and all other sets on that subject are its subsets; it is usually denoted by U. For example, if all animals on Earth is chosen as the universal set, then mammals, fish, and insects would be subsets of this set.

## Empty Set or Null Set
The empty set (null set) is a set that contains no elements and is denoted by ∅ (or Φ). The empty set has 0 elements, therefore it is a finite set.

Example: S={x∣x∈N,7<x<8}=∅

because there are no natural numbers between 7 and 8.

## Single Element (Unit) Set
A single-element (identity) set is a set containing only one element and is usually denoted as {s}.

Example: S={x∣x∈N,7<x<9}={8}

Because the only natural number that satisfies this range is 8.

## Equal sets:
If two sets have the same elements (regardless of their order), they are called equal sets.
Example: If A = {1, 2, 6} and B = {6, 1, 2}, then A = B because both sets contain the same elements.

## Equivalent Set:
If two sets have the same number of elements, they are called equivalent sets.
Example: For A = {1, 2, 6} and B = {16, 17, 22}, sets A and B are equivalent since |A|=|B|=3.

## Overlapping Sets:
Two sets that have at least one common element are called overlapping sets. In this case, the following relationships hold for the number of elements:

n(A∪B)=n(A)+n(B)−n(A∩B) \
n(A∪B)=n(A−B)+n(B−A)+n(A∩B) \
n(A)=n(A−B)+n(A∩B) \
n(B)=n(B−A)+n(A∩B)

Example: For sets A = {1, 2, 6} and B = {6, 12, 42}, since A∩B={6}, these two sets are overlapping sets.

## Disjoint Sets
Two sets, A and B, are disjoint sets if they have no common elements. Therefore, disjoint sets have the following properties:

n ( A ∩ B ) = ϕ
n ( A ∪ B ) = n ( A ) + n ( B )

Example: Let A = {1,3,8} and B = {7,9,14}. They have no common elements, therefore these sets are overlapping sets.

## Operations on Classical Sets

Set operations include set union, set intersection, set difference, set complement, and Cartesian product.

## Union

The union of sets A and B is the set of elements that are in A, in B, or in both A and B. That is, A ∪ B = {x|x ∈ A OR x ∈ B}.

Example: If A = {11,12,13,14} and B = {11,14,15}, then A ∪ B = {11,12,13,14,15}. The common element appears only once.

<img width="205" height="157" alt="image" src="https://github.com/user-attachments/assets/aaa1d682-eb3a-49c8-821e-ec19076c7e95" /> 

## Intersection
The intersection of sets A and B is denoted by A ∩ B. It is the set of common elements in both A and B. That is: A ∩ B = {x|x ∈ A AND x ∈ B}.

## Difference/Relative Complementary
The difference of sets A and B is the set of elements that are present only in set A but not in set B. This can be mathematically represented as AB = {x|x ∈ A AND x ∉ B}.

Example: If A = {9, 8, 12, 13} and B = {9, 16, 25}, then (A B) = {8, 12, 13} and (B A) = {16, 25}.

<img width="439" height="153" alt="a-b" src="https://github.com/user-attachments/assets/dda2a82c-1bb1-4e57-a0ad-aa614b687008" />

## The Complement of a Set
The complement of a set A is the set of elements that are not in set A.
More specifically, A′ = (UA), where U is a universal set containing all objects.

## Cartesian Product / Cross Product
The Cartesian product of n sets A1, A2, An is denoted as A1 × A2...× An and can be defined as all possible ordered pairs (x1, x2, xn) where x1 ∈ A1, x2 ∈ A2, xn ∈ An.

## Properties of Classical Sets
The properties of the sets play a significant role in obtaining the solutions we want.
The distinctive properties of classical sets are as follows:

## Changeability
If we have two sets, A and B, this property means:

A∪B=B∪A \\
A∩B=B∩A

## Association Feature
A∪(B∪C)=(A∪B)∪C \\
A∩(B∩C)=(A∩B)∩C



---