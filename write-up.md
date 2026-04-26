
👉 This alone gives you **bonus impression**

---

# 📝 2. `write-up.md` (Short & Perfect)

Create: `write-up.md`

```markdown
# Reflection Tree Design Write-up

## 1. Overview
This project implements a deterministic reflection agent using a decision tree structure. The goal is to guide users through structured end-of-day reflection across three psychological axes:
- Axis 1: Locus (Victim vs Victor)
- Axis 2: Orientation (Entitlement vs Contribution)
- Axis 3: Radius (Self vs Others)

The system avoids any runtime AI usage and ensures fully deterministic behavior.

---

## 2. Question Design

Questions were designed to:
- Be simple and relatable for end-of-day reflection
- Avoid judgment or moral pressure
- Offer clear, distinguishable options

Each question captures behavioral tendencies instead of opinions, making reflection more honest and actionable.

---

## 3. Branching Logic

Branching is handled using decision nodes:
- Based on user answers, the flow moves to different follow-up questions or reflections
- Example: Positive vs negative day leads to different agency questions

This ensures:
- Personalized flow
- Deterministic execution (same input → same path)

---

## 4. Axis Mapping

Each axis captures a behavioral dimension:

- **Axis 1 (Locus):**
  Measures whether the user takes ownership or externalizes outcomes

- **Axis 2 (Orientation):**
  Measures contribution vs expectation mindset

- **Axis 3 (Radius):**
  Measures whether focus is self-centered or includes others

Signals are recorded during traversal and used to summarize behavior.

---

## 5. Design Choices

- Used fixed options to maintain determinism
- Added reflection nodes after key decisions to create conversational flow
- Used bridge nodes to smoothly transition between axes
- Maintained simple state tracking using lists

---

## 6. Improvements (Future Work)

- Add dominant-axis calculation instead of raw answer storage
- Improve summary personalization using dynamic interpolation
- Add UI (web-based interface)
- Expand tree depth for more nuanced reflection

---

## 7. Conclusion

This system demonstrates how psychological frameworks can be converted into structured, navigable decision trees. The result is a predictable, auditable reflection tool that guides users without relying on generative AI.