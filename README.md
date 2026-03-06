# Discreet-Mathematics-MIT-OCW
Discreet Mathematics MIT OCW
PROOFS
1. Proposition

A proposition is just a sentence that can be true or false.

Example:

“Dogs bark.” → true

“1 + 1 = 3.” → false

That’s all.

✅ 2. NOT

NOT means no or opposite.

If something is true,
NOT makes it false.

✅ 3. AND

AND means both things must happen.

Example:
“You eat AND you drink.”
→ You must do both.

✅ 4. OR

OR means any one is enough.

Example:
“You can have tea OR coffee.”
→ You can take tea,
→ or coffee,
→ or even both.

✅ 5. IMPLIES (If → then)

This means:

If something happens, then another thing must happen.

Example:
“If it rains, then the road gets wet.”

It is wrong only when:

It rains

but the road does NOT get wet

Only that case is false.

Everything else → true.

✅ 6. IFF (if and only if)

This means:
Both things are the same.

Both true → OK
Both false → OK
Different → NOT OK

✅ 7. For all (∀)

Means everybody, everything.

Example:
“For all numbers, x + 0 = x.”

✅ 8. There exists (∃)

Means at least one.

Example:
“There exists a number that is 5.”
→ Yes, the number 5.

🎯 FINAL TINY SUMMARY (Just 5 lines)

Proposition = true/false sentence

NOT = opposite

AND = both

OR = at least one

IF → THEN = only false when first is true and second is false

∀ = for all

∃ = at least one

1. NOT (¬P)

This table shows the opposite.

P	NOT P
T (true)	F (false)
F (false)	T (true)

👉 Whatever P is, NOT P is the opposite.

✅ 2. AND (P ∧ Q)

Both must be true.

P	Q	P AND Q
T	T	T
T	F	F
F	T	F
F	F	F

👉 AND is true only when both P and Q are true.

✅ 3. OR (P ∨ Q)

At least one true.

P	Q	P OR Q
T	T	T
T	F	T
F	T	T
F	F	F

👉 OR is true when any one is true.
(Even both)

✅ 4. XOR (exclusive OR)

Exactly one true.

P	Q	P XOR Q
T	T	F
T	F	T
F	T	T
F	F	F

👉 XOR is true only when one is true and the other is false.

✅ 5. IMPLIES (P → Q)

This is the tricky one.
Wrong only when P is true and Q is false.

P	Q	P → Q
T	T	T
T	F	F
F	T	T
F	F	T

👉 Only false when:
P = true
Q = false

All other cases = true.

✅ 6. IFF (P ↔ Q)

True when both are same.

P	Q	P IFF Q
T	T	T
T	F	F
F	T	F
F	F	T

👉 True when both true or both false.

⭐ FINAL SUPER TINY SUMMARY

NOT = opposite

AND = both

OR = at least one

XOR = exactly one

IMPLIES = only false when (T → F)

IFF = same truth value1. NOT (¬P)

This table shows the opposite.

P	NOT P
T (true)	F (false)
F (false)	T (true)

👉 Whatever P is, NOT P is the opposite.

✅ 2. AND (P ∧ Q)

Both must be true.

P	Q	P AND Q
T	T	T
T	F	F
F	T	F
F	F	F

👉 AND is true only when both P and Q are true.

✅ 3. OR (P ∨ Q)

At least one true.

P	Q	P OR Q
T	T	T
T	F	T
F	T	T
F	F	F

👉 OR is true when any one is true.
(Even both)

✅ 4. XOR (exclusive OR)

Exactly one true.

P	Q	P XOR Q
T	T	F
T	F	T
F	T	T
F	F	F

👉 XOR is true only when one is true and the other is false.

✅ 5. IMPLIES (P → Q)

This is the tricky one.
Wrong only when P is true and Q is false.

P	Q	P → Q
T	T	T
T	F	F
F	T	T
F	F	T

👉 Only false when:
P = true
Q = false

All other cases = true.

✅ 6. IFF (P ↔ Q)

True when both are same.

P	Q	P IFF Q
T	T	T
T	F	F
F	T	F
F	F	T

👉 True when both true or both false.

⭐ FINAL SUPER TINY SUMMARY

NOT = opposite

AND = both

OR = at least one

XOR = exactly one

IMPLIES = only false when (T → F)

IFF = same truth value
✅ 1. Contrapositive, Converse, Inverse

The video explains these:

1) Contrapositive

P → Q
same as
¬Q → ¬P
(always equivalent)

2) Converse

Q → P
(not equivalent)

3) Inverse

¬P → ¬Q
(also not equivalent)

✅ 2. Logical Equivalence

Two statements are equivalent when they always have the same truth values.

Example:
P → Q
is equivalent to
¬P OR Q

✅ 3. Using Logical Equivalence to Simplify

Example from video:
(P OR (NOT P AND Q))
simplifies to
(P OR Q)

They show this using a truth table.

✅ 4. Predicates

A predicate is like a function that gives true or false depending on input.

Example:
P(n): “n is a perfect square”

✅ 5. Quantifiers

Two types:

Universal (∀)

“For all”

Existential (∃)

“There exists”

They also show symbols like:
∀x ∈ ℕ : P(x)

✅ 6. Combining Quantifiers

Example from the video:
Goldbach’s conjecture
∀n (exists p, q such that p + q = n)

They show how changing order changes the meaning.

✅ 7. Negating Quantifiers

The video teaches:

¬(∀x P(x)) = ∃x ¬P(x)
¬(∃x P(x)) = ∀x ¬P(x)

Very important.

✅ 8. Validity & Satisfiability

They also explain:

Valid

Always true no matter what P, Q, R are.

Satisfiable

True for at least one combination.
1. First, the key idea of logic (very important)

In mathematical logic, a statement is judged only by whether it is violated, not by whether it sounds natural in English.

👉 “P implies Q” is considered FALSE only in one situation:

P is true

Q is false

In every other case, it is considered TRUE.

That single idea explains the whole table.

2. The truth table again (with meaning)
P	Q	P → Q	Meaning
T	T	T	Promise kept
T	F	F	Promise broken ❌
F	T	T	No promise made
F	F	T	No promise made
3. Why only (T → F) is false

Think of P → Q as a promise:

“If P happens, then Q will happen.”

Case by case:
(1) P = T, Q = T

“If you study, you will pass.”
You studied and you passed.
✅ Promise kept → TRUE

(2) P = T, Q = F

“If you study, you will pass.”
You studied but failed.
❌ Promise broken → FALSE

👉 This is the only false case.

(3) P = F, Q = T

“If you study, you will pass.”
You didn’t study, but still passed.
🤷 No rule was violated → TRUE

(4) P = F, Q = F

“If you study, you will pass.”
You didn’t study and didn’t pass.
🤷 Still no violation → TRUE

4. Now your confusing examples make sense
Example 1

“If pigs can fly, then you can understand the Chebyshev bound.”

P = “Pigs can fly” → False

Q = “You understand Chebyshev bound” → maybe False

So we are in F → F, which is TRUE in logic.

👉 This does NOT mean the Chebyshev bound is incomprehensible.
It only means the statement was not violated.

Example 2

“If you can solve any problem we come up with, then you get an A.”

Let:

P = “You can solve all problems”

Q = “You get an A”

If you solve some but not all problems:

P = False
So P → Q is automatically TRUE, regardless of Q.

👉 Logic alone does NOT guarantee you an A.
👉 It only says no logical contradiction occurred.

This is why English promises ≠ logical implication.

5. Very important takeaway (exam gold)
Logical implication is NOT causation
Logical implication is NOT a real-life promise
Logical implication is about truth preservation

P → Q is false only when:

P is true and Q is false

That’s it.

6. Do you need to memorize the table?

❌ No
✅ Just remember this one sentence:

“An implication is false only when the hypothesis is true and the conclusion is false.”

Everything else follows.
Chapter 2 -
Proof by contradiction
What is Proof by Contradiction?

Proof by contradiction means:

To prove a statement is true, we temporarily assume it is false.
If that assumption leads to impossible or illogical result, then our assumption must be wrong.

Therefore the original statement is true.

Structure

We want to prove P is true

Assume P is false

From this assumption we get a contradiction (impossible result)

Therefore the assumption is wrong

So P must be true

Symbolically in logic:

If assuming ¬P leads to contradiction → P is true

2️⃣ Example 1: √2 is irrational

This is the classic example.

We want to prove:

√2 is irrational

(Irrational = cannot be written as a fraction)

Step 1 — Assume the opposite

Assume √2 is rational.

So it can be written as:

√2 = a/b

Where:

a and b are integers

fraction is simplified (no common factor)

Step 2 — Square both sides

√2 = a/b

Square both sides:

2 = a² / b²

Multiply both sides by b²:

2b² = a²

Step 3 — Observe something important

2b² = a²

So a² is even.

If a² is even → a must be even.

So let:

a = 2k

Step 4 — Substitute again

a = 2k

a² = 4k²

Put into equation:

2b² = 4k²

Divide by 2:

b² = 2k²

Now b² is also even → b is even.

Step 5 — Contradiction

We found:

a is even

b is even

That means a and b have common factor 2.

But earlier we assumed fraction a/b was simplified.

This is a contradiction.

Step 6 — Conclusion

Our assumption was wrong.

So:

√2 cannot be rational

Therefore:

√2 is irrational.

3️⃣ Second Example: Triangle Area 90 > 92

This example is usually used to show impossible assumption.

Suppose someone claims:

A triangle with integer sides has area greater than 90 but less than 92

We assume this is true.

Then using Heron's formula, we compute possible triangles.

A = \sqrt{s(s-a)(s-b)(s-c)}

After checking all integer side combinations:

No triangle produces an area between 90 and 92.

So our assumption leads to impossibility.

Therefore the statement is false.

This is another contradiction-style reasoning.

4️⃣ Why do Computer Science students study this?

Proof by contradiction is very important in CS.

1. Algorithm correctness

Example:

Prove that an algorithm must terminate.

Assume it never terminates → leads to contradiction.

2. Graph theory

Example:

Prove properties like

shortest path

minimum spanning tree

Many proofs use contradiction.

3. Complexity theory

Example:

Proofs in:

NP-completeness

undecidable problems

use contradiction.

4. Logic in programming

Contradiction reasoning appears in:

SAT solvers

automated theorem proving

type systems

5️⃣ Simple intuition

Think like a detective method:

Instead of proving directly, you say:

“Let me assume the opposite is true.”

Then you follow the consequences.

If the result becomes impossible, the assumption must be wrong.

6️⃣ Why you felt sleepy reading it

Very normal reason.

Your brain was trying to understand:

logical structure

algebra

number theory

all at once.

That is heavy cognitive load.

Even MIT students pause on this proof.

7️⃣ Quick memory trick

Remember this pattern:

Goal: prove P

Assume NOT P

→ derive impossible result

Therefore NOT P is false

So P is true
8️⃣ Your plan tonight

Good sequence:

1️⃣ Study contradiction proof 1 hour
2️⃣ Complete I-20 form
3️⃣ Upload loan approval
4️⃣ Sleep

If you want, I can also show you the easiest contradiction proof in computer science:

There are infinitely many prime numbers

It is very beautiful and easier than √2 proof.

What do you mean algoriths terminate , not getting

Good question. I’ll explain very simply.

What does “algorithm terminates” mean?

An algorithm terminates means:

The program eventually stops and gives an answer.

It does not run forever.

Example 1 — Terminating algorithm

Suppose we write an algorithm to count from 1 to 5.

start
i = 1

while i ≤ 5
   print i
   i = i + 1

stop

Output:

1
2
3
4
5

After printing 5, the program stops.

So this algorithm terminates.

Example 2 — Non-terminating algorithm

Now look at this:

start
i = 1

while i ≥ 1
   print i

Here:

i is always ≥ 1

the condition never becomes false

So the program runs forever.

This algorithm does not terminate.

Why termination matters in Computer Science

If an algorithm never stops, it is useless.

Imagine:

login system that never finishes

banking transaction that never completes

program stuck in loop

So computer scientists prove algorithms terminate.

Where contradiction is used

Sometimes it is hard to prove directly.

So we use proof by contradiction.

Example logic:

Assume the algorithm does NOT terminate

Follow the steps mathematically

We reach an impossible situation

Therefore assumption is wrong

So the algorithm must terminate

Simple real-life example

Imagine stairs with 10 steps.

You start at step 10 and move down one step each time.

Algorithm:

while step > 0
   step = step - 1

Steps:

10
9
8
7
...
1
0

Eventually you reach 0.

You cannot go forever.

So the algorithm must terminate.

Why MIT teaches this in Discrete Math

Because algorithms are built on logic proofs:

contradiction

induction

logic rules

sets

These help prove:

algorithms stop

algorithms are correct

algorithms are optimal

This is the mathematical foundation of Computer Science.




