---
topic: Introduction to Logic
code: ISC1013
week: 0
lecturer: Mr. Thilina W.
date: 2025-04-21T23:00:00
draft: false
cascade:
  type: docs
tags:
  - lecture
  - maths
---
# Introduction to Logic - Mathematics 1 - Week 1
## Key Concepts
- Propositions
- Connectives/Operators
- Logical equivalencies
- Tautologies and Contradictions
## 1. Introduction to Logic 
### 1.1 Propositions (Statements/Premises)
A **proposition (or statement)** is a declarative sentence that is either true or false (but not both). The truth or falsehood of a proposition is called its **truth value.**

| Proposition                 | Truth Value |
| --------------------------- | ----------- |
| p= “The sea is blue”        | True        |
| q= “London is in Sri Lanka” | False       |
| r= “2 < 4”                  | True        |
| s= “4 = 7”                  | False       |
### 1.2 Connectives / Operators
**Connectives/operators** are used for making **compound propositions**. The truth value depends on the value of it's components.

| Description               | Word                      | Symbol | Usage  | Example                                           |
| ------------------------- | ------------------------- | ------ | ------ | ------------------------------------------------- |
| Negation                  | NOT                       | ¬ ~    | ¬p, ~p | **¬p** is true if **p** is false.                 |
| Conjunction               | AND                       | ∧      | p ∧ q  | **true** if both **p** and **q** are true.        |
| Disjunction               | OR                        | ∨      | p ∨ p  | **true** if either **p** or **q** is true.        |
| Implication / Conditional | If... Then...             | →      | p → q  | **false** only if **p is  true** and **q false**. |
| Bi-conditional            | If and only if... then... | ↔      | p ↔ q  | true when **p** and **q** have same truth values. |

**Unary and Binary Operators:** When categorized based on the number of arguments or operands, there are 2 types of connectives. 

| Arity            | Operators                                                         | Description                     |
| ---------------- | ----------------------------------------------------------------- | ------------------------------- |
| Unary Operators  | ¬ (Negation)                                                      | Applies to a single proposition |
| Binary Operators | ∧(Conjunction), ∨(Disjunction), →(Implication), ↔(Bi-conditional) | Connects two propositions       |
#### Negation / NOT Operator
If _p_ is a proposition, then the negation of _p_ is denoted by _¬p_ , which when translated to simple English means- “It is not the case that _p_ or simply not _p_. The truth value of _¬p_ is the opposite of the truth value of _p_.

##### Truth Table

| p   | ¬p  |
| --- | --- |
| T   | F   |
| F   | T   |

>**Example 1:** Negation of “It is raining today”, is “It is not the case that is raining today” or simply “It is **not** raining today”.

#### Conjunction / AND Operator
For any two propositions _p_ and _q_, their conjunction is denoted by _p∧q_, which means _"p and q"_. The conjunction _p∧q_ is True when both _p_ and _q_ are True, otherwise False.
##### Truth Table

| p   | q   | p ∧ q |
| --- | --- | ----- |
| T   | T   | T     |
| T   | F   | F     |
| F   | T   | F     |
| F   | F   | F     |

>**Example 1:**
_p_ – “Today is Friday” 
_q_ – “It is raining today”
_p∧q_ - “Today is Friday **and** it is raining today”. 
This proposition is true only on rainy Fridays and is false on any other rainy day or on Fridays when it does not rain. 

#### Disjunction / OR Operator
For any two propositions _p_ and _q_, their disjunction is denoted by _p∨q_, which means _“p or q“_. The disjunction _p∨q_ is True when either _p_ or _q_ is True, otherwise False. 

##### Truth Table

|p|q|p ∨ q|
|---|---|---|
|T|T|T|
|T|F|T|
|F|T|T|
|F|F|F|

>**Example 1:** 
_p_ – “Today is Friday”
_q_ – “It is raining today”
_p∨ q_ - “Today is Friday **or** it is raining today”. 
This proposition is true on any day that is a Friday or a rainy day(including rainy Fridays) and is false on any day other than Friday when it also does not rain.

#### Implication / Conditional / IF... THEN... Operator

For any two propositions p and q, the statement _“if p then q”_ is called an **implication** and it is denoted by _p→q_ . In the implication _p→q_, _p_ is called the **hypothesis** or **antecedent** or **premise** and _q_ is called the **conclusion** or **consequence**. The implication is _p→q_ is also called a **conditional statement**. The implication is **false** when _p_ is true and _q_ is false otherwise it is **true**.

##### Truth Table

| p     | q     | p → q |
| ----- | ----- | ----- |
| T     | T     | T     |
| **T** | **F** | **F** |
| F     | T     | T     |
| F     | F     | T     |

One might wonder that why is **p→q** true when _p_ is false. This is because the implication guarantees that when _p_ and _q_ are true then the implication is true. But the implication does not guarantee anything when the premise _p_ is false. There is no way of knowing whether or not the implication is false since _p_ did not happen. This situation is similar to the “Innocent until proven Guilty” stance, which means that the implication _p→q_ is considered true until proven false. Since we cannot call the implication _p→q_ false when _p_ is false, our only alternative is to call it true.

This follows from the **Explosion Principle** which says: “A False statement implies anything” Conditional statements play a very important role in mathematical reasoning, thus a variety of terminology is used to express _p→q_ , some of which are listed below.

> If p, then q
> p is sufficient for q
> q when p
> a necessary condition for p is q
> p only if q
> q unless ≠p
> q follows from p
##### Inverse, Converse, Contrapositive of an implication
Implication _𝑝 → 𝑞_ 
If it is raining, then the sky is gray

**• Inverse of the implication:**
 _~𝑝 → ~𝑞_ 
 If it is not raining, then the sky is not gray

**• Converse of the implication:**
 _𝑞 → 𝑝_
 If the sky is gray, then it is raining

**• Contrapositive of the implication:**
 _~𝑞 → ~𝑝_ 
 If the sky is not gray, then it is not raining

##### Examples
>**Example 1:** _“If it is Friday then it is raining today”_ is a proposition which is of the form _p→q_. The above proposition is true if it is not Friday(premise is false) or if it is Friday and it is raining, and it is false when it is Friday but it is not raining.

>**Example 2:** Decide which of the following statements are true and which are false.
> 1. 0 = 1 → 1 = 1
> 2. 1 = 1 → most horses have 4 legs
> 3. If 8 is a prime number, then the 7624th digit of π is an 8.
> 4. If the 7624th digit of π is an 8, then 2 + 2 = 4
> 
>**Solution:** All four of the statements are true. Remember, the only way for an implication to be false is for the _if_ part to be true and the _then_ part to be false.
> 5. Here both the hypothesis and the conclusion are true, so the implication is true. It does not matter that there is no meaningful connection between the true mathematical fact and the fact about horses.
> 6. Here the hypothesis is false and the conclusion is true, so the implication is true.
> 7. I have no idea what the 7624th digit of π is, but this does not matter. Since the hypothesis is false, the implication is automatically true.
> 8. Similarly here, regardless of the truth value of the hypothesis, the conclusion is true, making the implication true.

>**Example 3:** Suppose I tell Sue that if she gets a 93% on her final, then she will get an A in the class. Assuming that what I said is true, what can you conclude in the following cases:
> 1. Sue gets a 93% on her final.
> 2. Sue gets an A in the class.
> 3. Sue does not get a 93% on her final.
> 4. Sue does not get an A in the class.
> 
>**Solution:** Note first that whenever _p→q_ and _p_ are both true statements, _q_ must be true as well. For this problem, take _p_ to mean “Sue gets a 93% on her final” and _q_ to mean “Sue will get an A in the class.”
>	1. We have _p→q_ and _p_, so _q_ follows. Sue gets an A.
>	2. You cannot conclude anything. Sue could have gotten the A because she did extra credit for example. Notice that we do not know that if Sue gets an A, then she gets a 93% on her final. That is the **converse** of the original implication, so it might or might not be true.
>	3. The **contrapositive** of the converse of _p→q_ is _¬p→¬q_, which states that if Sue does not get a 93% on the final, then she will not get an A in the class. But this does not follow from the original implication. Again, we can conclude nothing. Sue could have done extra credit.
>	4. What would happen if Sue does not get an A but **did** get a 93% on the final? Then _p_ would be true and _q_ would be false. This makes the implication _p→q_ false! It must be that Sue did **not** get a 93% on the final. Notice now we have the implication _¬q→¬p_ which is the **contrapositive** of _p→q_. Since _p→q_ is assumed to be true, we know _¬q→¬p_ is true as well.
##### Important
Consider the following two implications.

>If HCL acid and NaOH are combined, then NaCl will be produced.

This statement is an example of **cause and effect**.

> If March has 31 days, then dogs are mammals.

In this statement, there is clearly no causal relation between days of the
month and dogs being mammals. Both the premise and the conclusion of
Statement 2 are true, so according to the truth table, the implication is true.

The point here is that the use of “implies” in logic is very different from its use in everyday language to reflect causality. So it is important to remember that, in mathematics, **the statement, _“p implies q”_ doesn’t necessarily mean p causes q, but rather that if p is true, then q must also be true.**

#### Biconditional or Double Implication

For any two propositions _p_ and _q_, the statement “_p_ if and only if(iff) _q_” is called a **biconditional / bi-implication** and it is denoted by _p↔q_. _p↔q_ has the same truth value as **_(p→q)∧(q→p)_** The implication is true when _p_ and _q_ have same truth values, and is false otherwise.

##### Truth Table

| p   | q   | p ↔ q |
| --- | --- | ----- |
| T   | T   | T     |
| T   | F   | F     |
| F   | T   | F     |
| F   | F   | T     |

Some other common ways of expressing _p↔q_ are:

“p is necessary and sufficient for q” if p then q, and conversely” p if q”

Example, “It is raining today if and only if it is Friday today.” is a proposition which is of the form p↔q   p↔q . The above proposition is true if it is not Friday and it is not raining or if it is Friday and it is raining, and it is false when it is not Friday or it is not raining.