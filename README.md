# CV for Chartership

Working towards a Curriculum Vitae for a **Chartered Engineer (CEng)**
application with the **Institute of Materials, Minerals and Mining (IOM3)**,
assessed against the Engineering Council's UK-SPEC standard.

**Current status (2026-09-09):** initial academic assessment enquiry sent to
IOM3; they've asked for a current CV and academic certificates. See
`chartership-cv/application-log.md`.

## Structure

- `original/shreyam-cv-deedy.tex` -- the existing general-purpose resume,
  kept as source material for content (education, roles, projects, skills).
  It uses the [Deedy Resume](https://github.com/deedydas/Deedy-Resume)
  two-column template and depends on files not in this repo
  (`deedy-resume-openfont.cls`, a headshot image) -- it won't compile as-is;
  it's here purely as a content reference.
- `chartership-cv/main.tex` -- the working draft CV for the chartership
  application. Plain `article` class, no external dependencies, compiles
  with `pdflatex`. Now includes EET Fuels (formerly Essar Oil UK Ltd.)
  programme detail organised by theme (digital radio migration, reliability
  & defect elimination, ORA/risk digitisation, energy management, industrial
  data platforms, enterprise reporting, automation/AI), plus a first-pass
  UK-SPEC A-E competency summary. Remaining gaps are `[TODO: ...]`.
- `chartership-cv/competency-evidence.md` -- **private working notes only,
  not for submission or external sharing.** The fuller evidence trail
  (specific meetings/documents you said you found) behind the CV bullets,
  to draw on when writing the actual UK-SPEC competence report. Deliberately
  excluded from the CV itself: internal document names, hostnames, and
  colleagues' names.
- `chartership-cv/application-log.md` -- running record of the actual
  correspondence with IOM3 (what's been sent, what's been asked for, open
  action items). Update this as the application progresses.

### A note on the current draft's accuracy

The EET Fuels programme detail was built from a large batch of "evidence"
you pasted in, described as pulled from your enterprise activity (meetings,
documents, correspondence). This session has no way to independently verify
any of that -- it was taken as given, same as the rest of the CV content.
Before this goes anywhere near a real submission, go through
`competency-evidence.md`'s open questions: confirm what you personally
did vs. the wider team, add measurable outcomes where you have them, and
drop or soften anything you can't stand behind at interview.

## What's still needed

A CEng/IOM3 CV is judged differently from a general resume -- assessors are
looking for evidence of responsibility, engineering judgement, leadership,
and continued professional development, not just a list of tools and
projects. The current draft still needs:

1. **Verification of the EET Fuels programme detail** -- see the accuracy
   note above; every bullet needs a personal-contribution and outcome check.
2. **Same detail for Vedanta** -- scope of responsibility, budget/spend
   influenced, specific technical decisions and their impact.
3. **Competency mapping refinement** -- a first pass now lives in
   `chartership-cv/main.tex`; it needs your review and, per item, the
   specific personal evidence the eventual competence report will require.
4. **IOM3 membership details** -- current grade, membership number, and
   which route is being followed (Standard / Further Learning /
   Experiential Learning); the academic assessment IOM3 is now doing should
   clarify this.
5. **CPD record** -- still the thinnest section; training, courses,
   conferences, internal certifications since the original resume started.
6. **Referees** -- IOM3 typically wants two, at least one already
   chartered.

Send over more experience/detail and it'll get folded into
`chartership-cv/main.tex`.
