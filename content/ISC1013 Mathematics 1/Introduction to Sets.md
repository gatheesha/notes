---
topic: Introduction to Sets
code: ISC1013
week: 1
lecturer: Mr. Thilina W.
date: 2025-04-28T23:00:00
draft: false
cascade:
  type: docs
tags:
  - lecture
  - maths
---
# Introduction to Sets - Mathematics 1 - Week 2

## Key Concepts
- Types of Numbers
- Set theory & Set Language
- Set Notation
- Set Operations & Product of Two Sets
- Algebra of Sets
## Introduction to Sets

> [!info]+ Lecture Reference  
> ESC, BSC, ISC 1013 – Mathematics I  
> Topic: Logic & Sets  
> Academic Year: 2025


### Types of Numbers

Types of numbers in mathematics include various types of numbers i.e., natural numbers, whole numbers, integers, rational numbers, irrational numbers, real numbers, imaginary numbers, complex numbers, prime numbers, composite numbers, even numbers, odd numbers etc.

> Sources:  
> [GeeksforGeeks](https://www.geeksforgeeks.org/types-of-numbers/)

| Symbol | Name               | Description                                            | Examples             |
| ------ | ------------------ | ------------------------------------------------------ | -------------------- |
| ℕ      | Natural Numbers    | Counting Numbers                                       | 1,2,3,4,...          |
| W      | Whole Numbers      | Zero and the Counting Numbers                          | 0,1,2,3,4,....       |
| ℤ      | Integers           | Zero and Positive & Negative Counting Numbers          | ...,-2,-1,0,1,2,...  |
| Q      | Rational Numbers   | Ratios of Integers (Repeating or Terminating decimals) | 1/2, 3/4, 0.75,3.666 |
| I      | Irrational Numbers | Don't Repeat or Terminate                              | 2, √3, √5, π         |
| R      | Real Numbers       | All rational and Irrational Numbers                    |                      |


### What is a Set?

- A **set** is a well-defined collection of **distinct objects**.
- The objects in a set are called **elements** or **members**.

> [!example]+ Example  
> - Set of vowels: `A = {a, e, i, o, u}`  
> - Set of even numbers less than 10: `B = {2, 4, 6, 8}`



### Set Notation

- **Roster / Tabular form**: Lists all elements  
  → e.g., `A = {1, 2, 3}`
- **Set-builder form**: Describes properties of elements  
  → e.g., `B = {x | x is an even number < 10}`

> `∈` means "is an element of"  
> `∉` means "is not an element of"



### Types of Sets

| Type                 | Description                                 | Example                    |
|----------------------|---------------------------------------------|----------------------------|
| **Finite Set**       | Contains a countable number of elements     | `{1, 2, 3}`                |
| **Infinite Set**     | Has uncountable elements                    | `{x | x ∈ ℕ}`              |
| **Equal Sets**       | Same elements, order doesn't matter         | `{a, b, c} = {c, b, a}`    |
| **Null/Empty Set**   | Has no elements                             | `∅` or `{}`                |
| **Singleton Set**    | Has exactly one element                     | `{0}`                      |
| **Universal Set (U)**| Contains all elements under consideration   | `U = {1, 2, 3, 4, 5, 6}`   |
| **Subset**           | `A ⊆ B` if all elements of A are in B       | `{1, 2} ⊆ {1, 2, 3}`       |
| **Proper Subset**    | `A ⊂ B` and `A ≠ B`                         | `{1} ⊂ {1, 2}`             |
| **Power Set**        | Set of all subsets                          | `P({1,2}) = {∅, {1}, {2}, {1,2}}`|



### Set Operations

#### 1. Union ( ∪ )

- Combines all elements from both sets  
- `A ∪ B = {x | x ∈ A or x ∈ B}`

#### 2. Intersection ( ∩ )

- Common elements  
- `A ∩ B = {x | x ∈ A and x ∈ B}`

#### 3. Set Difference ( − )

- Elements in A not in B  
- `A − B = {x | x ∈ A and x ∉ B}`

#### 4. Complement ( A′ or Aᶜ )

- Elements in the Universal Set not in A  
- `A′ = {x | x ∈ U and x ∉ A}`



### Venn Diagrams

- Visual tool for representing sets and their relationships.
- Useful for solving problems involving unions, intersections, and complements.



### Important Properties

#### Idempotent Laws:
- `A ∪ A = A`
- `A ∩ A = A`

#### Commutative Laws:
- `A ∪ B = B ∪ A`
- `A ∩ B = B ∩ A`

#### Associative Laws:
- `(A ∪ B) ∪ C = A ∪ (B ∪ C)`
- `(A ∩ B) ∩ C = A ∩ (B ∩ C)`

#### Distributive Laws:
- `A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)`
- `A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)`

#### De Morgan’s Laws:
- `(A ∪ B)′ = A′ ∩ B′`
- `(A ∩ B)′ = A′ ∪ B′`



###  Examples

> [!example]+ Example 1  
> Let `U = {1, 2, 3, 4, 5, 6, 7, 8, 9}`,  
> Let `A = {1, 2, 3, 4}`, `B = {3, 4, 5, 6}`  
>
> Find:  
> - `A ∪ B = {1, 2, 3, 4, 5, 6}`  
> - `A ∩ B = {3, 4}`  
> - `A − B = {1, 2}`  
> - `B − A = {5, 6}`  
> - `A′ = {5, 6, 7, 8, 9}`



##  Summary

- Sets are fundamental in mathematics for representing collections.
- Set operations allow us to manipulate and combine data meaningfully.
- Visual and logical tools like Venn diagrams and set laws simplify reasoning.

> [!tip]+ Tip  
> Practice with Venn diagrams and set identities often—they’re common in exams and logical reasoning tests.

[^1]: 
