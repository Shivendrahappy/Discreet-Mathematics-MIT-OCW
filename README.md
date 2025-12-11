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
