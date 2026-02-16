# AI Control Card  
### Durable System-Level Prompting for Coding Agents

---

## 1️⃣ STOP — No Code Yet

Before implementation, require:

1. What system-level problem are we solving?
2. What invariants must remain true?
3. What assumptions are being made?
4. What could break silently?
5. What existing modules are impacted?
6. What are 2–3 alternative design approaches?
7. Which is most durable long-term and why?

If these are unclear → do not proceed.

---

## 2️⃣ Define the Boundaries

Require clear separation of:

- UI layer
- State management
- Domain logic
- External IO
- Persistence
- Automation logic

No cross-layer leakage without explicit justification.

---

## 3️⃣ Demand Invariants

Ask:

- List all invariants this feature must preserve.
- Define each clearly (mathematically if possible).
- Explain how each is enforced.
- Explain how each could be violated.

If invariants are fuzzy → the design is weak.

---

## 4️⃣ Force Long-Term Thinking

Before approval, ask:

How does this hold up if:
- Scale increases 10–100x?
- Contributors increase?
- APIs evolve?
- Features expand?
- External dependencies fail?

If the design collapses under scale → redesign.

---

## 5️⃣ Implement With Constraints

When moving to code:

- No hidden coupling
- No silent state mutation
- No duplicated logic
- No premature optimization
- Prefer composable abstractions over conditionals
- Comment WHY, not WHAT

---

## 6️⃣ Run Adversarial Audit

After implementation, require:

1. What are the edge cases?
2. What assumptions are implicit?
3. What technical debt was introduced?
4. Where will this hurt in 6 months?
5. What tests prove this is safe?
6. What would break at 10x scale?

If weaknesses appear → refactor now.

---

## 7️⃣ Assumption Disclosure

Always require explicit listing of:

- Explicit assumptions
- Implicit assumptions
- Risky assumptions
- Unknowns

Hidden assumptions destroy trust.

---

## 8️⃣ Alternative Rejection Check

Ask:

- What reasonable alternative did you reject?
- Why is it inferior?
- Under what conditions would it become superior?

If tradeoffs cannot be articulated → reasoning is shallow.

---

## 9️⃣ Hack Detection

Stop immediately if you see:

- Growing conditionals instead of abstractions
- Symptom-fixing instead of root cause solving
- Global state mutation
- Naming drift
- Copy/paste logic
- Cross-layer mixing

Ask:

Is this solving root cause or adding complexity?

---

## 🔟 When You Don’t Know the Right Thing

Use this pressure test:

- Explain this as if teaching a senior engineer.
- Now argue against it.
- Now describe catastrophic failure modes.
- What are we not considering?

You do not need the correct answer.  
You need to stress-test the proposed answer.

---

## 11️⃣ Master Pre-Feature Prompt

Before any major change:

You are not allowed to write code yet.

Define:
- Goal
- Constraints
- Invariants
- Failure modes
- Scaling risks

Propose 3 architectures.  
Compare tradeoffs rigorously.  
Recommend the most durable option.  
List unknowns requiring research.

---

## Core Meta-Rule

AI optimizes locally.  
You must enforce global coherence.

If it jumps to code → slow it down.  
If it gives one solution → demand alternatives.  
If it avoids tradeoffs → require them.  
If invariants are unclear → stop.

Your role is not to out-code the AI.  
Your role is to control its thinking horizon.
