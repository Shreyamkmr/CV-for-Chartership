# CV for Chartership

Working towards a Curriculum Vitae for a **Chartered Engineer (CEng)**
application with the **Institute of Materials, Minerals and Mining (IOM3)**,
assessed against the Engineering Council's UK-SPEC standard.

## Structure

- `original/shreyam-cv-deedy.tex` -- the existing general-purpose resume,
  kept as source material for content (education, roles, projects, skills).
  It uses the [Deedy Resume](https://github.com/deedydas/Deedy-Resume)
  two-column template and depends on files not in this repo
  (`deedy-resume-openfont.cls`, a headshot image) -- it won't compile as-is;
  it's here purely as a content reference.
- `chartership-cv/main.tex` -- the new draft CV being adapted for the
  chartership application. Plain `article` class, no external
  dependencies, compiles with `pdflatex`. Content from the original CV has
  been carried over and reorganized; sections needed for a chartership CV
  that weren't in the original are stubbed with `[TODO: ...]` placeholders.

## What's still needed

A CEng/IOM3 CV is judged differently from a general resume -- assessors are
looking for evidence of responsibility, engineering judgement, leadership,
and continued professional development, not just a list of tools and
projects. The current draft still needs:

1. **More detail on each role** -- scope of responsibility, team size,
   budget/spend influenced, specific technical or engineering decisions
   made, and the impact of those decisions (especially for Essar Oil UK and
   Vedanta).
2. **Competency mapping** -- UK-SPEC groups evidence under five areas (A:
   knowledge & understanding, B: design/development, C: responsibility &
   leadership, D: communication & interpersonal skills, E: professional
   commitment). Once we have enough detail, the CV/supporting statement
   should be organised to make this mapping obvious to an assessor.
3. **IOM3 membership details** -- current grade, membership number, date
   joined, and which route is being followed (Standard / Further Learning /
   Experiential Learning).
4. **CPD record** -- training, courses, conferences, internal
   certifications, since the original resume started.
5. **Referees** -- IOM3 typically wants two, at least one already
   chartered.

Send over more experience/detail and it'll get folded into
`chartership-cv/main.tex`.
