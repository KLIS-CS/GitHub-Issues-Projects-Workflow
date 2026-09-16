# Teacher Grading — Checkpoint 3

Final score: **60 automatic + 40 teacher-reviewed = 100**.

## Manual Rubric — 40 points

| Category | Full-credit evidence | Points |
|---|---|---:|
| Issue quality | Goal is clear and acceptance criteria are testable | 10 |
| Project evidence | Project URL is valid and the Issue was moved through sensible statuses | 10 |
| Conceptual understanding | Accurately explains Issues, acceptance criteria, and Projects | 15 |
| Reflection | Specific explanation connected to the student's own workflow | 5 |
| **Total** |  | **40** |

## Entering the Teacher Grade

You do **not** need to remember a score command.

When the student opens the required Pull Request, the grader posts a **Teacher grading** section directly in that PR with this fixed template:

```text
/manual-grade
Issue quality: 0/10
Project evidence: 0/10
Concepts: 0/15
Reflection: 0/5

Feedback:
Write concise feedback here.
```

Copy the block into a **new PR comment**, replace the four scores, and add feedback. The workflow calculates the 40-point teacher subtotal automatically and combines it with the automatic 60 points.

Example:

```text
/manual-grade
Issue quality: 9/10
Project evidence: 10/10
Concepts: 13/15
Reflection: 4/5

Feedback:
Clear Issue and acceptance criteria. Your Project evidence is complete; make the explanation of when an Issue should be closed more precise.
```

The newest valid grading comment by `hbycwyh2008` is used. To change a grade, post a new completed template.

The older short form remains supported for compatibility:

```text
/manual-grade 36
```

## Recommended teacher check

Open the student's `[CP3]` Issue and Project before grading. Verify that the acceptance criteria are genuinely testable, the Issue is assigned and labeled appropriately, and the Project status history reflects a sensible workflow rather than a screenshot-only exercise.
