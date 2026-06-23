---
id: 2026-06-23-002-heavy-rewrites-and-decisions
timestamp: 2026-06-23T00:00:00+02:00
model: claude-opus-4-8
files_touched:
  - _quarto.yml
  - appendix-checklists.qmd
  - appendix-drawings.qmd
  - ch-before.qmd
  - ch-citation-license.qmd
  - ch-course-shape.qmd
  - ch-create-orgs.qmd
  - ch-live-drawings.qmd
  - ch-new-iteration.qmd
  - ch-run-of-show.qmd
  - ch-teacher-setup.qmd
  - ch-three-orgs.qmd
  - ch-website.qmd
  - index.qmd
  - intro.qmd
  - part-prerequisites.qmd
  - part-setup.qmd
  - summary.qmd
---

Continuation of the handbook TODO cleanup (Phase 2 + 3 of the approved plan), after the author resolved the gating decisions:

1. DOI: canonical concept DOI for gitforsci/* and gitforsci-dev/*, PLUS a separate per-iteration DOI for each iteration org.
2. Setup order: swap to instructor-first in Part 2.
3. Lesson plan: generic timed run-of-show as the main content of ch-run-of-show, with the gitforsci-cis plan as a worked example.
4. Survey tool: KoboToolbox template, Google Forms noted as the simpler alternative.
5. Intro diagram: cleaner Mermaid, light theme, top-down People -> Accounts/software -> Three orgs.

This entry covers the heavy chapter rewrites that depended on those decisions: the corrected three-org model (one new iteration org per cohort, generated from gitforsci-dev templates; landing page in gitforsci-dev/website, not the central org; CONTRIBUTING.md and per-iteration documentation), the ghclass-based learner invitation and the pre-course timeline, the descriptive-voice citation chapter with two-level DOIs, the instructor-first reorder, the redrawn intro and three-org diagrams, the run-of-show worked example, and the appendix refresh. Drawing cross-reference ids were renamed to sec-drawing-* so they resolve as cross-references, and the @larnsce / @gitforsci-cis-lesson-plan.md citation-syntax warnings were removed. The book now renders with no warnings.
