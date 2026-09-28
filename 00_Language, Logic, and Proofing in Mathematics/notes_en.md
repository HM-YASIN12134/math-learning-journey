# Step 0: Mathematical Language, Logic and Proof

## Lesson 1: What Is Mathematics Really? And Why Do We Need a Special Language?

### Starting from Zero...

Think, you went to the market. One shopkeeper said, **"I have many mangoes."** Another said, **"I have 5 mangoes."**

With which one will you be able to decide how many mangoes to buy? The second one. Because the word **"many"** is vague — to someone 10 is many, to someone 100 is.

Mathematics is that language, where we **remove vagueness** and say things in such a way that there is no doubt. This is the birth of mathematics — from the need to speak clearly.

---

### Statement — The First Brick of Mathematics

Everything in mathematics starts with a **statement**.

**What is a statement?** A sentence that is either **true** or **false** — there is no third option.

| Sentence | Statement? | Why? |
| --- | --- | --- |
| "2 + 3 = 5" | ✅ True | Can be clearly verified |
| "2 + 3 = 7" | ✅ False | Can be clearly verified |
| "The sky is beautiful today" | ❌ | "Beautiful" is relative — beautiful to someone, not to someone else |
| "x + 2 = 5" | ❌ (yet) | Without knowing what x is, true/false cannot be said |
| "All humans are mortal" | ✅ True | Verifiable |

**Notice:** "x + 2 = 5" — here **x** is a **blank box**. If you put a number in place of x, the sentence becomes a statement. If you put x = 3, it is true; if you put x = 4, it is false.

> **Connection Ahead (Hint):** This **x** thing will later become the **variable of algebra** (Step 5). For now, just remember — x is a blank box, where, if you put a number, the sentence becomes true or false. The whole game of algebra is filling this blank box.

---

### Logical Connectives — Four Tools for Joining Statements

Two statements can be joined to make a new statement. Four ways:

**1. AND** — true only if both are true
> "I will get wet in the rain **and** take an umbrella"
> — If you do both → true. If you do not do one → false.

**2. OR** — true if at least one is true
> "I will drink tea **or** coffee"
> — If you do either one, it is true. If you do neither, it is false.

**3. NOT** — reverses it
> "It is **not** raining today"
> — If it rains, false; if not, true.

**4. IF...THEN** — most important
> "**If** it rains, **then** I will take an umbrella"
> — It is false only when "it rains" is true but "I take an umbrella" is false. In all other cases, true.

| Rain? | Umbrella? | If-then true/false? |
| --- | --- | --- |
| Yes | Yes | ✅ True |
| Yes | No | ❌ False |
| No | Yes | ✅ True (the condition did not apply) |
| No | No | ✅ True (the condition did not apply) |

> **Connection Ahead (Hint):** This **if-then** is the **backbone of all proofs** in mathematics. When I say "If the triangle is right-angled, then Pythagoras' theorem holds" — this is that if-then. Geometry, algebra, calculus — in all places this one thing will return again and again.


---
### The Backbone of Discrete Math and Graph Theory?

**1. Discrete Math (Discrete Mathematics):**
Discrete Math is that mathematics where we work with **separate, countable things** (such as: numbers, sets, graphs). And the **backbone of this Discrete Math is this logic (Logic)** that we are just learning.
*   When you learned "and", "or", "not" — in Discrete Math these are called **Boolean Operators**. Computer circuits (AND gate, OR gate) work exactly like this.
*   When you learned "if-then" — this is **Implication** in Discrete Math. In programming, `if-else` conditions, database queries — all come from here.

**2. Graph Theory:**
Graph Theory is actually a part of Discrete Math itself.
*   Think, a graph is some **points (Vertices)** and the **lines (Edges)** connecting them.
*   This "group of points" and "group of lines" — these are but **sets** (Step 2)!
*   And "Is this graph connected (Connected)?" — answering this question is an **if-then proof** (Step 0). That is, the foundation of Graph Theory is the logic and sets we just learned.

> **Connection Ahead (Hint):** When we study **Step 12 (Permutations and Combinations)** or **Step 13 (Probability)**, then you will see how probability is calculated with "and/or" (for example: the probability of "A and B occurring"). And in **Step 19 (Limits)**, when we say "if the value of x gets very close to 2, the value of y gets close to 4", then that too is an "if-then" statement!
---
### The Structure of Mathematics: Definition → Axiom → Theorem → Proof

Now see how mathematics is built:

**Definition:** We ourselves decide the meaning of a word.
> "An even number is that number which is exactly divisible by 2." — This is a definition. We are saying what "even" means.

**Axiom:** The statements that we assume to be true without proof, because they are so fundamental that nothing can be said without them.
> "Through two points, only one straight line can be drawn." — This is an axiom.

**Theorem:** The statements that can be said to be true by **proving** them from definitions and axioms.
> "The sum of the three angles of a triangle is 180°." — This is a theorem.

**Proof:** Showing step by step with reasoning that the theorem is true.

> **Connection Back (Reminding):** Step 2-**Set** — a group of things. The concept of set will now be useful here. For example: "the set of all even numbers" — here "even" is a definition, "set" is a group. Together, both are the language of mathematics.

---

# Step 0, Lesson 2: The Structure of Mathematics — Definition → Axiom → Theorem → Proof

## Why Is Structure Needed?

Think, you are learning a new game. But no one told you the rules of the game. You are doing whatever you like. Then what will happen? The game will not happen at all.

Mathematics is also a game. It has some **rules**, some **definitions**. Without these, mathematics cannot be done. And this structure is like this:

```
Definition (we fix the name)
    ↓
Axiom (we fix the rule, accept it without proof)
    ↓
Theorem (we discover new truth using definitions and axioms)
    ↓
Proof (we show step by step why that truth is true)
```

It is like a pyramid. One has to rise from the bottom to the top.

---

## 1. Definition

**What?** We ourselves decide what the meaning of a word will be.

**Why is it needed?** If we do not fix what "even" means, then saying "4 is even" has no meaning at all.

**Examples:**

| Definition | What we fixed |
| --- | --- |
| Even number | The integer that can be divided by 2 without remainder |
| Odd number | The integer that cannot be divided by 2 without remainder |
| Prime number | The natural number greater than 1 that has no factors other than 1 and itself |

**Important point:** A definition is not true or false. It is naming. We are deciding.

> **Connection (Step 1):** The numbers that we will place on the number line? We are now giving names to those very numbers — "even", "odd", "prime". These are definitions.

> **Connection Ahead (Hint — chapter 5, Algebra):** When we say "a variable is that symbol which expresses an unknown number" — that too is a definition.

---
## 2. Axiom

**What?** The statements that we assume to be true without proof. Because they are so fundamental that nothing can be said without them. And there is nothing below to go to in order to prove them.

**Why is it needed?** With definitions, only names can be fixed. But to do the work of mathematics, some primary rules are needed.

**Examples:**

| Axiom | What it says |
| --- | --- |
| a + b = b + a | Commutative law of addition |
| a + 0 = a | Identity of zero |
| a × 1 = a | Identity of one |
| Through two points, only one straight line can be drawn | Fundamental rule of geometry |

**Important point:** An axiom is not a thing to prove. These are the rules of the game.

> **Analogy:** In chess, "the horse swims" — this is not a thing to prove, this is a rule of the game. Mathematical axioms are also that.

**A deep truth:** An axiom is not "eternal truth". We assume it to be true. If the set of axioms changes, a completely different mathematics is created.

> **Example:** One of Euclid's axioms was "parallel lines never meet". Someone asked "If they meet?" — then non-Euclidean geometry was born, which is useful in Einstein's theory of relativity.

---

## 3. Theorem

**What?** The statements that can be **proved** using definitions and axioms.

**Why is it needed?** Axioms are very few, but we want to know countless truths. Theorems are those truths that we discover.

**Examples:**

| Theorem | What it says |
| --- | --- |
| The sum of two even numbers is even | A truth of numbers |
| The sum of the three angles of a triangle is 180° | A truth of geometry |
| √2 is irrational | A truth of numbers |

**Important point:** A theorem can be true or false — proof is needed to verify.

---

## 4. Proof

**What?** Showing step by step with reasoning that the theorem is true.

**Why is it needed?** Just saying "it is true" is not enough. How did you know? Proof is that answer.

**Structure of proof:**

1. We start with what we know (definitions, axioms, previous theorems).
2. We proceed step by step through reasoning.
3. At the end, we show that what we wanted to prove has been reached.

---

## A Complete Example: From Zero to Theorem

Let's prove a theorem — right from zero.

### Step 1: Definition (We fixed it)

**Definition (even):** An integer n is even if and only if n = 2k, where k is an integer.
**Definition (odd):** An integer n is odd if and only if n = 2k + 1, where k is an integer.

>In mathematics and logic, for any definition the phrase "if and only if" (if and only if - iff) is used because it expresses a two-way condition or complete equivalence. In simple language, it means the condition must be true from both directions—no exception or alternative can exist. Its symbolic form (⟺)

### Step 2: Axiom (We assumed)

**Axiom 1:** Adding two integers gives an integer.
**Axiom 2:** Multiplying two integers gives an integer.
**Axiom 3:** a(b + c) = ab + ac (distributive law).

### Step 3: Theorem (What we will prove)

**Theorem:** The sum of two even numbers is even.

### Step 4: Proof

Let a and b be two even numbers.

From definition:
- a = 2m (for some integer m)
- b = 2n (for some integer n)

Then,
```
a + b = 2m + 2n
      = 2(m + n)    [Axiom 3: distributive law]
```

Now m and n are integers, so (m + n) is also an integer [Axiom 1].

Then a + b = 2 × (some integer).

From definition, what can be written in the form 2 × integer is even.

**Therefore, a + b is even.** ∎

**∎ The meaning of this symbol: "Proof complete".**

### What was used in this proof?

| Thing used | Where it came from |
| --- | --- |
| Definition of even number | Definition |
| Closure under addition, closure under multiplication | Axiom |
| Distributive law | Axiom |
| "Let a and b be even" | Start of reasoning |
| "a = 2m, b = 2n" | Application of definition |
| "a + b = 2(m+n)" | Algebraic simplification |
| "Therefore even" | Application of definition (from the reverse direction) |

> **Connection Back (Step 1):** On the number line, you placed even-odd numbers left-right. That word "even" now we gave a clear meaning through definition.

> **Connection Ahead (Step 2):** Set? Here by "m integer" we meant m is a member of the set of integers.

> **Connection Ahead (Hint — Step 5, Algebra):** These a = 2m, b = 2n — these are variables. In algebra you will arrange equations with these variables. The structure of this proof will come again and again in algebraic proofs.

> **Connection Ahead (Hint — Step 19, Limits):** In calculus, when we learn "limits", even then we will use this if-then structure: "If the value of x goes very close to 2, then the value of y will go close to 4."

> **Connection (Hint — Discrete Math/Graph Theory):** The entire foundation of Discrete Math is this definition-axiom-theorem-proof. In Graph Theory, "this graph is connected" — this is a theorem, which has to be proved.

---

## The Web of Connections (So Far):

```
[Definition] ────────→ Fixing the name of a thing
    │
    ▼
[Axiom] ─────→ Fixing the rules of the game (without proof)
    │
    ▼
[Theorem] ───────→ A discovered truth
    │
    ▼
[Proof] ────────→ Reasoned explanation of the truth
    │
    ├──→ Proofs of Algebra (Step 5)
    ├──→ Theorems of Geometry (Step 15)
    ├──→ Theorems of Calculus (Step 21-22)
    └──→ Discrete Math, Graph Theory
```
---

## Summary of Step 0

So far we learned:

| Topic | Main point |
| --- | --- |
| Statement | A sentence that can be said to be true/false |
| Logic | and, or, not, if-then |
| Definition | We fix the meaning of a word |
| Axiom | Fundamental rules assumed without proof |
| Theorem | A truth provable from definitions+axioms |
| Proof | Establishing truth step by step with reasoning |

**Structure of proof:**
1. Say what you will prove
2. Start with "Let..."
3. Place definitions
4. Use axioms/algebra
5. Draw conclusion
6. End with ∎

---