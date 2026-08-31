---
course: Linear Algebra for Data Science
type: course-reference
status: reference
---

# Linear Algebra for Data Science (LADS) - course reference

**EN.553.295** - Applied Mathematics and Statistics, 4 credits, EQ
Mon/Wed/Fri 1:30-2:20pm, Maryland 201, in person (all sections)
Lecture recordings will **not** be posted.
Prerequisite: Calculus II (AS.110.107 / AS.110.109 or equivalent).

> **This is LADS, not LADE.** EN.553.291 *Linear Algebra and Differential
> Equations* is a separate course that shares this one's first 27 of 39
> lectures, homework, recitation content, office hours, and both midterms.
> Everything filed in this folder is LADS. LADE-only staff and details are
> deliberately not tracked here.

## Contacts

- **Dr. Mario Micheli** (instructor, both LADS and LADE) - mmiche18@jhu.edu,
  Wyman Park Building N441
- **Victoria Wilfong** - vwilfon1, **Head TA for LADS**. This is who
  homework extension requests go to.
- Other LADS TAs: Abeeha Mirza (amirza9), Caitlin Ferrini (cferrin2),
  Marwa Naji (mnaji2), Tanya Liu (tliu23), Tiffany Wei (twei23)
- **Dr. TaeHo Yoon** - tyoon7@jh.edu, Mt. Washington building. LADE
  co-instructor; relevant only because content and office hours are shared.

Office hours: TBA, posted on Canvas. Both in-person and online (Zoom).

## Recitation sections

Tuesdays, in person. Section 01: 3:00-3:50pm. Section 02: 4:30-5:20pm.
(Check SIS for room assignments.)

Partially mandatory - roll call at the start of each section. **8 of 11
sections required for the full 2%.** Below 8, each miss costs 0.25%
(attend 5 of 11 and you earn 1.25% instead of 2%). Effectively three free
drops, and the syllabus expects those drops to absorb illness and family
emergencies rather than being spent casually.

**Open item:** the syllabus gives the count (11) but not which Tuesdays
count. Worth confirming, since the two midterm Tuesdays are explicitly not
counted and Thanksgiving week is unclear.

## Grade breakdown

| Component | Weight |
|---|---|
| Recitation section attendance | 2% |
| Office hours (one meaningful visit by Oct 2) | 0.5% |
| Homework (13 assignments, two lowest dropped) | 18.5% |
| Midterm 1 | 20% |
| Midterm 2 | 20% |
| Final Exam | 39% |

Sums to 100%. The two exams plus the final are 79% of the grade.

## The curve

Per the syllabus: the grade is curved, and **the median of the raw scores
is the threshold between a B and a B+**.

Per Dr. Micheli in lecture (not in the syllabus text): the median is drawn
from the LADE cohort and applied to both courses, and the LADE average
tends to run slightly lower - which makes the effective threshold more
generous for LADS students. Treat this as a lecture claim to re-verify,
not a documented policy.

What the curve mechanically does: it fixes the *median* student at the
B/B+ line. It does not cap A grades, but it does mean an A comes from
finishing meaningfully above the median of a cohort that is largely
sophomores and juniors, not from clearing an absolute score bar.

## Homework policy

- 13 assignments, typically due Fridays at 11:59pm on Gradescope. Two
  lowest scores dropped (an unsubmitted zero can be one of the drops).
- Posted roughly one week before the due date. Some material needed may be
  covered after posting, but always before the due date.
- **16-minute grace period** - uploads accepted penalty-free until 12:15am.
- After that: late-marked and a **25-point penalty**, and Gradescope stops
  accepting entirely 24 hours after the due time.
- **One 24-hour "no questions asked" extension** for the whole semester.
  Must be emailed to the Head TA **before** 11:59pm on the due date. No
  bonus for leaving it unused. Requesting it removes the 25-point penalty.
- Further no-penalty extensions only from the instructor, only for family
  emergencies or documented medical reasons.
- **Tag your problems on Gradescope** ("selecting pages") after uploading -
  skipping this is a flat **15-point penalty out of 100**.
- Scanning: black and white (not grayscale), letter-sized pages, reasonable
  file size. CamScanner / GeniusScan / a real scanner / Notability or
  OneNote on a tablet all fine. Do **not** export as one long page.
- No homework solutions are released - problems get reused across semesters.
  Worked examples come via recitation worksheets and pre-exam review sets.
- Regrade requests accepted at any time during the course.

## Exams

| Exam | Date | Time | Notes |
|---|---|---|---|
| Midterm 1 | Tue 2026-10-06 | 8:00-9:00pm | Shared with LADE |
| Midterm 2 | Tue 2026-11-10 | 8:00-9:00pm | Shared with LADE, not cumulative |
| Final | Wed 2026-12-16 | 2:00-5:00pm | LADS-only, cumulative |

- Evening midterms exist because the course runs multiple sections; ~170
  students across LADS and LADE sit the same exam in one reserved room.
  Conflicts (labs, other classes) can be raised for alternate arrangements.
- Cheat sheets: Midterm 1 one one-sided letter sheet; Midterm 2 two
  one-sided (or one two-sided), and the Midterm 1 sheet may be reused;
  Final three sides. Handwritten by you - electronic handwriting then
  printed is acceptable. Keep them all.
- No calculators at any exam.
- On midterm Tuesdays, recitation time becomes open extra office hours with
  no attendance taken.
- Exams are on paper, scanned by TAs, graded on Gradescope. Regrades via
  Gradescope with a written justification.
- No past exams are released; most review problems are drawn from them.
- Missing an exam requires a note from the Student Health Center or a
  doctor. Contact the instructors before the exam if at all possible.
- No guarantee Midterm 1 is graded before the course drop deadline.

## Textbooks

None required. The instructors distribute their own notes and typed
homework problems. Suggested references:

1. **Selinger, *Matrix Theory and Linear Algebra*** - free at
   https://www.mathstat.dal.ca/~selinger/linear-algebra/ , printed copy
   ~$15-20. Strongly recommended; good extra problems. Caveat: written for
   a one-semester course in ordinary linear algebra, not data science.
2. **Strang, *Linear Algebra and Learning from Data*** - good, but the
   instructor considers the exposition poorly suited to a first pass at
   linear algebra. Useful once already comfortable.
3. **Trefethen & Bau, *Numerical Linear Algebra*** - advanced, numerically
   focused, with a good SVD treatment.

## Topics

- **Core linear algebra** (shared with LADE): systems of linear equations,
  matrices, REF, consistent and homogeneous systems, matrix operations,
  scalar product, norm, linear independence, inverses, determinants, null
  space, range, spanning sets, bases, dimension and rank, orthogonal and
  orthonormal bases, Gram-Schmidt, linear transformations, eigenvalues and
  eigenvectors, characteristic polynomials, complex eigenvalues,
  diagonalization.
- **Data science applications:** least-squares approximation, spectral
  decomposition, quadratic forms, convexity, principal component analysis,
  dimensionality reduction, approximation in function spaces.
- **Programming:** basic linear algebra in MATLAB, weighted toward
  operations that matter in data science. Not the main focus.

## Ethics policy

- Collaboration on homework is permitted; each student must independently
  write up their own solutions. Copying is punished for both parties equally.
- Solutions manuals and instructor materials: **always** prohibited.
- Previous course material: prohibited unless provided by the instructor.
- AI tools may be consulted, but every solution step must be carried out and
  presented by you. Results from the course notes and from previous homework
  may be used without proof; everything else must be justified. **Lecture
  notes notation is required.**
- A document, "Best Practices for Using AI to Learn Mathematics," is
  attached to the syllabus - not yet read; worth pulling from Canvas.
- Witnessed unethical behavior must be reported to the instructor or a TA.

## Support and study guidance

- **PILOT** sections are offered, non-mandatory. Problems posted to Canvas
  at the end of each week. PILOT covers only the first two thirds (core
  LA), then switches to differential equations - stop attending at that point.
- Instructors and TAs will **not** provide one-on-one tutoring or recommend
  individual tutors. Use the Learning Den for that.
- No extra credit work will be assigned to any individual student.
- The instructor's stated study method: allocate roughly 50% of course time
  to understanding theory before touching problems. Read 2-3 pages of notes
  line by line, put them away, and rewrite the definitions, theorem
  statements, and proofs from a blank page, justifying each step. The
  explicit warning is against "illusions of knowing" - reading notes,
  agreeing they make sense, and then failing on unfamiliar problems.
- Exams will contain problems never seen before; theory is the only route.

## Known issues in this syllabus draft

This is a **1st draft dated 8/31/26**, and it carries at least two errors
worth watching for in a revised version:

1. The homework notes reference **"Spring Break"** twice. In a fall
   semester this can only mean Thanksgiving Break, and the surrounding
   dates (HW #12 on Wed Dec 2) fit that reading.
2. That same note says the homework after the break moves to **Sunday
   instead of Friday**, but HW #13 is listed as Friday, Dec 11. The
   parenthetical labels are also shuffled - HW #12 is the one that actually
   follows Thanksgiving, while HW #13 carries the "due after Thanksgiving
   Break" label.

All dates in this repo follow the **explicit date table**, not the
prose notes, since the table is internally consistent and every listed
date falls on its stated weekday in 2026.

Also note: there is no homework due between Nov 15 and Dec 2 - a
two-and-a-half week gap spanning Midterm 2 aftermath and Thanksgiving.

## Miscellaneous

- Late-join rules for homework and recitation attendance exist in the
  syllabus but do not apply - enrolled from day one.
- Check SIS for last-minute classroom changes and recitation rooms.
- All course materials live on Canvas.
- Do not add the instructors on social media.

## Source

Source: EN.553.295 syllabus, 1st draft dated 8/31/26 (subject to revision). Imported 2026-08-31.
