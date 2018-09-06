/*
Jeewanjyot Dhanjal
Assignment 2

Part 1: (15 points)

 Create a file called "Assignment 2.md" in your github repository
 Show that p->q and q' -> p' are logically equivalent without using truth tables or a "contrapositive" law (don't assume they are true)
 Show that (p->r) ^ (q->r) <=> (p v q) -> r
 Give an interpretation to prove that the following wff is not valid: (Ǝx)A(x) ^ (Ǝx)B(x) -> (Ǝx)(A(x) ^ B(x))
Part 2: (5 points)

 Add support for parentheses in your WFF calculator that you did for assignment 1

*/

Part 1

q'->p' 
qvp'   implication

p'vq   commutative

p->q   implication

(p->r) ^ (q->r) <=> (p v q) -> r

(p'vr)^(q'vr)  implication

(rvp')^(rvq')  commutative

rv(p'^q')      distributive

(p'^q')vr      commutative

(pvq)'vr       de morgan's

(pvq)->r       implication

(Ǝx)A(x) ^ (Ǝx)B(x) -> (Ǝx)(A(x) ^ B(x))

x is animals

A(x) is a dog

B(x) is a cat
