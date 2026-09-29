
## Core User Flow

```text
User submits code + error
        ↓
System analyzes the problem
        ↓
"What happened?"
        ↓
"Why did it happen?"
        ↓
Progressive hint
        ↓
Student attempts a fix
        ↓
Feedback
        ↓
Full explanation / fix if needed
```
## MVP Goal
Write code → get error.

Paste into DebugMate (or integrate with IDE).

Get:

Clear error classification,

Short explanation,

Level‑1 hint.

Try to fix based on hint.

If still stuck, request deeper hints.

Optionally see corrected code after attempting.

Receive a 1‑line “lesson learned” summary tied to DSA patterns.
# unique proposition
Progressive disclosure by design: Level 1 (rephrase error in plain English) → Level 2 (point to the concept) → Level 3 (narrow the location) → Level 4 (Socratic question) → Level 5 (small code snippet only if stuck). Never jump to full solution unless user explicitly opts out of learning mode.
Built-in metacognition: “What do you think is wrong?” + quizzes.
Error → concept mapping + spaced review.
Language-specific beginner curriculum (common Java vs Python error taxonomies)