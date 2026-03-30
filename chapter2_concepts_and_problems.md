# NCERT Class 7 Math — Chapter 2: Arithmetic Expressions
## Top 5 Key Concepts & Top 20 Key Problems (for Simulation Design)

---

## TOP 5 KEY CONCEPTS

### Concept 1: Terms in Expressions — Breaking Expressions into Parts (Section 2.2)

**What it covers:**
- Terms are parts of an expression separated by the '+' sign
- Subtraction is converted to addition of the inverse: `83 – 14` → terms are `83` and `–14`
- A product/quotient within an expression is a single term: in `6 × 5 + 3`, the terms are `6 × 5` and `3` (NOT `6`, `5`, and `3`)
- To evaluate: first compute each term's value, then add all terms together
- In `30 + 5 × 4`: terms are `30` and `5 × 4` → values are `30` and `20` → sum = 50

**Simulation potential:** HIGH — Visual term-highlighter that breaks any expression into colored terms, shows evaluation order step by step.

---

### Concept 2: Brackets & Order of Operations (Section 2.2)

**What it covers:**
- Without brackets, `30 + 5 × 4` could mean `(30 + 5) × 4 = 140` or `30 + (5 × 4) = 50`
- Brackets resolve ambiguity: always evaluate inside brackets first
- Real-world context: Mallesh's marbles (30 + 5 bags of 4) vs Purna's wrong interpretation
- Irfan's change: `100 – (15 + 56)` vs incorrect `100 – 15 + 56`
- Nested operations: `5 × (3 + 2) + 7 × 8 + 3`

**Simulation potential:** EXCELLENT — Interactive expression builder where student places brackets and sees how the value changes. "Same numbers, different brackets, different answers."

---

### Concept 3: Removing Brackets — Sign Rules (Sections "Removing Brackets I & II")

**What it covers:**
- **Minus before brackets** → signs inside flip:
  - `200 – (40 + 3) = 200 – 40 – 3` (plus becomes minus)
  - `500 – (250 – 100) = 500 – 250 + 100` (minus becomes plus)
- **Plus before brackets** → signs stay unchanged:
  - `28 + (35 – 10) = 28 + 35 – 10`
- The key insight: subtracting a subtraction is like adding
- "Rather than memorizing rules, think about meanings"

**Simulation potential:** EXCELLENT — Step-by-step bracket removal with animated sign changes. Color-code which signs flip and which stay.

---

### Concept 4: Commutative & Associative Properties — Swapping & Grouping (Section 2.2)

**What it covers:**
- **Commutative (Swapping):** changing the order of terms doesn't change the value: `a + b = b + a`, even with negative terms: `(–7) + 10 = 10 + (–7)`
- **Associative (Grouping):** grouping terms differently gives the same sum: `(a + b) + c = a + (b + c)`
- Together: terms of an expression can be added in ANY order
- Real-world analogy: hat-and-shoes (order doesn't matter) vs socks-and-shoes (order matters!)
- Manasa's shortcut: forgot a number? Just add it to the existing sum

**Simulation potential:** HIGH — Drag-and-drop term reordering tool. Show that regardless of arrangement, the sum stays the same.

---

### Concept 5: Distributive Property — Multiple of a Sum = Sum of Multiples

**What it covers:**
- `a × (b + c) = a × b + a × c` — "the multiple of a sum is the sum of the multiples"
- Visual: 2 people each ordering cutlet (₹43) and rasgulla (₹24): `2 × (43 + 24) = 2 × 43 + 2 × 24`
- Visual: scouts (4 rows × 5) + guides (3 rows × 5) = (4+3) × 5
- Works for subtraction too: `(14 – 6) × 10 = 14 × 10 – 6 × 10`
- Mental math power: `97 × 25 = (100 – 3) × 25 = 2500 – 75 = 2425`
- Tinker the terms: `53 × 18 = 954` → `63 × 18 = (53 + 10) × 18 = 954 + 180 = 1134`

**Simulation potential:** EXCELLENT — Visual area model (rectangle split into parts) + mental math calculator showing distributive decomposition.

---
---

## TOP 20 KEY PROBLEMS

### Problem 1: Fill Blanks to Make Expressions Equal
**Source:** Page 25, Figure it Out 1
**Statement:** Fill blanks: (a) 13+4 = ___+6  (b) 22+___ = 6×5  (c) 8×___ = 64÷2  (d) 34–___ = 25
**Answer:** (a) 11 (b) 8 (c) 4 (d) 9
**Sim fit:** HIGH — Interactive balance/equation solver.

### Problem 2: Compare Without Computing
**Source:** Page 25-26, Examples 2-3
**Statement:** Which is greater? 1023+125 or 1022+128? (Without adding!) Also: 245+289 vs 246+285, 273–145 vs 272–144, etc.
**Answer:** 1023+125 < 1022+128 (Joy got 3 more, Raja had 1 more → Joy ahead by 2)
**Sim fit:** EXCELLENT — Visual marble comparison showing the reasoning.

### Problem 3: Arrange Expressions in Order
**Source:** Page 25, Figure it Out 2
**Statement:** Arrange ascending: 67–19, 67–20, 35+25, 5×11, 120÷3
**Answer:** 120÷3(40) < 67–20(47) < 67–19(48) < 5×11(55) < 35+25(60)
**Sim fit:** HIGH — Drag to sort expressions on a number line.

### Problem 4: Ambiguity Without Brackets (Mallesh vs Purna)
**Source:** Page 27, Example 4
**Statement:** `30 + 5 × 4` — Purna gets 140 (adding first), Mallesh gets 50 (multiplying first). Who is right?
**Answer:** Mallesh is right. The expression means 30 + (5 bags × 4 marbles each) = 50.
**Sim fit:** EXCELLENT — Show both interpretations visually, student picks correct one.

### Problem 5: Identify Terms in Complex Expressions
**Source:** Pages 28-29
**Statement:** Identify terms in: 13–2+6, 5+6×3, 4+15–9, 23–2×4+16, 28+19–8
**Answer:** e.g., 5+6×3 → terms are `5` and `6×3`. 23–2×4+16 → terms are `23`, `–2×4`, `16`.
**Sim fit:** HIGH — Visual term-coloring tool, student taps to split expression into terms.

### Problem 6: Evaluate Expressions Using Terms
**Source:** Page 34, Figure it Out 1
**Statement:** Find values: (a) 28–7+8 (b) 39–2×6+11 (c) 40–10+10+10 (d) 48–10×2+16÷2 (e) 6×3–4×8×5
**Answer:** (a) 29 (b) 38 (c) 50 (d) 36 (e) –142
**Sim fit:** EXCELLENT — Step-by-step evaluator showing term identification → term evaluation → addition.

### Problem 7: Fire in the Mountain Game
**Source:** Page 32-33, Example 8
**Statement:** 33 students, teacher calls '5'. Ruby writes 6×5+3. If teacher calls '4'? If '7'?
**Answer:** Called '4': 8×4+1. Called '7': 4×7+5.
**Sim fit:** HIGH — Interactive grouping visualization with draggable students.

### Problem 8: Pay ₹432 with Coins & Notes
**Source:** Page 33, Example 10
**Statement:** Express 432 using ₹1, ₹5, ₹10, ₹20, ₹50, ₹100 notes/coins in different ways.
**Answer:** 4×100+1×20+1×10+2×1, or 8×50+1×10+4×5+2×1, etc.
**Sim fit:** HIGH — Drag-and-drop coin/note builder. Multiple decompositions.

### Problem 9: Remove Brackets (Sign Rules)
**Source:** Page 37-38, Figure it Out 1-2
**Statement:** Fill in: 24+(6–4)=24+6___, 24–(6+4)=24___6–4, 27–(8+3)=27___8___3
**Answer:** 24+(6–4)=24+6–4, 24–(6+4)=24–6–4, 27–(8+3)=27–8–3
**Sim fit:** EXCELLENT — Animated bracket removal showing sign changes.

### Problem 10: The Sign-Flip Rule
**Source:** Pages 35-36, Examples 12-13
**Statement:** 200–(40+3)=200–40–3. But 500–(250–100)=500–250+100 (NOT –100). Why?
**Answer:** When removing brackets preceded by minus, ALL signs inside flip. The –100 inside becomes +100.
**Sim fit:** EXCELLENT — Step-by-step animation with color-coded sign changes.

### Problem 11: Do Expressions Have Same Value?
**Source:** Page 38, Figure it Out 3
**Statement:** Compare: (6+10)–2 vs 6+(10–2); 16–(8–3) vs (16–8)–3; 27–(18+4) vs 27+(–18–4)
**Answer:** (a) Equal (both 14). (b) Not equal (11 vs 5). (c) Equal (both 5).
**Sim fit:** HIGH — Side-by-side evaluator, student predicts then verifies.

### Problem 12: Add Brackets to Get Target Value
**Source:** Page 38, Figure it Out 5
**Statement:** Add brackets: (a) 34–9+12=13 (b) 56–14–8=34 (c) –22–12+10+22=–22
**Answer:** (a) 34–(9+12)=13 (b) (56–14)–8=34 (c) –22–(12+10)+22=–22
**Sim fit:** EXCELLENT — Drag brackets onto expression, see value change in real-time.

### Problem 13: Tinker the Terms
**Source:** Page 37
**Statement:** Given 53–16=37. What is 54–16? 52–16? 53–15? 53–17?
**Answer:** 54–16=38 (+1), 52–16=36 (–1), 53–15=38 (+1), 53–17=36 (–1)
**Sim fit:** HIGH — Interactive "nudge" slider showing how changing one term changes the result.

### Problem 14: Generate Expressions for a Value
**Source:** Page 38, Figure it Out 7
**Statement:** Using 2, 3, 5 and +, –, brackets: make as many different values as possible.
**Answer:** 2–3+5=4, 3–(5–2)=0, 5+2+3=10, 5+2–3=4, 2–(3+5)=–6, etc.
**Sim fit:** EXCELLENT — Expression builder puzzle: given digits and operations, hit target values.

### Problem 15: Distributive Property Fill-in
**Source:** Pages 41-42, Figure it Out 1
**Statement:** 3×(6+7)=3×6+3×7, (8+3)×4=8×4+3×4, 5×(9–2)=5×9–5×___
**Answer:** All follow the pattern a×(b+c)=a×b+a×c (or with subtraction).
**Sim fit:** HIGH — Visual rectangle area model showing the split.

### Problem 16: Distributive Mental Math
**Source:** Page 41, Examples 17-18
**Statement:** 53×18=954 → find 63×18. Also: 97×25, 95×8, 104×15, 49×50.
**Answer:** 63×18=(53+10)×18=954+180=1134. 97×25=(100–3)×25=2500–75=2425.
**Sim fit:** EXCELLENT — Step-by-step mental math decomposer.

### Problem 17: Compare Expressions Using Distributive Reasoning
**Source:** Page 42, Figure it Out 2
**Statement:** (8–3)×29 vs (3–8)×29; 15+9×18 vs (15+9)×18; 23×(17–9) vs 23×17+23×9
**Answer:** (a) > (b) < (c) < (d) =
**Sim fit:** HIGH — Reasoning quiz with visual explanation.

### Problem 18: Jasoda's Subtraction Strategy
**Source:** Page 38, Problem 8
**Statement:** To subtract 9: subtract 10, add 1 back. 36–9=36–10+1=26+1=27. Why does this work?
**Answer:** Because 9=10–1, so subtracting 9 = subtracting (10–1) = subtracting 10 and adding 1.
**Sim fit:** HIGH — Visual number line showing the "overshoot and compensate" strategy.

### Problem 19: Melvin's Reading (Multiple Equivalent Expressions)
**Source:** Page 43, Problem 2
**Statement:** Melvin reads daily except Tue/Sat. In 8 weeks, which expressions describe total stories? Options include 5×2×8, (7–2)×8, 7×8–2×8, etc.
**Answer:** (b) (7–2)×8 and (g) 7×8–2×8 — both equal 40.
**Sim fit:** HIGH — Match expressions to scenarios.

### Problem 20: Expression Engineer (Four 4s Puzzle)
**Source:** Page 45
**Statement:** Using four 4s with +, –, ×, ÷ and brackets, make all values from 1 to 20.
**Answer:** e.g., (4+4)÷(4+4)=1, 4÷4+4÷4=2, (4+4+4)÷4=3, 4+(4–4)×4=4, etc.
**Sim fit:** EXCELLENT — Puzzle game: drag four 4s into an expression template, use operations to hit each target 1-20.

---

## CONCEPT-TO-SIMULATION MAPPING SUMMARY

| # | Concept | Best Simulation Type | Key Interaction |
|---|---------|---------------------|-----------------|
| C1 | Terms in Expressions | **Term Highlighter/Evaluator** | Tap to identify terms, step-by-step evaluation |
| C2 | Brackets & Order | **Bracket Placement Explorer** | Drag brackets, see value change |
| C3 | Sign Rules | **Bracket Removal Animator** | Watch signs flip when removing brackets |
| C4 | Commutative/Associative | **Term Reorder Tool** | Drag terms to reorder, sum stays same |
| C5 | Distributive Property | **Area Model + Mental Math** | Split rectangles, decompose multiplications |

| Problem Cluster | Problems Covered | Simulation Type |
|----------------|------------------|-----------------|
| Expression Evaluator | P5, P6, P7 | Step-by-step term evaluator |
| Bracket Explorer | P4, P9, P10, P11, P12 | Interactive bracket placement/removal |
| Distributive + Mental Math | P15, P16, P17 | Area model + decomposition calculator |
| Expression Comparison | P2, P3, P13, P17 | Side-by-side reasoner |
| Expression Builder | P8, P14, P20 | Puzzle: build target values with constraints |
