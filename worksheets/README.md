# POLISCI 450A worksheet workbook

Edit `main.tex` to develop the group's shared answers. It is a single, self-contained LaTeX file; no copied worksheet PDFs or separate question files are required to compile it.

Each question has an empty `groupanswer` environment. Replace its blank space with the group's work, credit contributors where relevant, and record any unresolved disagreement. The document contains questions and original instructor hints; no answers have been generated or filled in.

Open this folder in Codex for the LaTeX editor and live PDF preview. For a local PDF, run `latexmk -pdf -interaction=nonstopmode -halt-on-error -outdir=build main.tex` from this folder. The main file also works as a standalone Overleaf upload.

## Coverage

| Worksheet | Questions included |
| --- | --- |
| Lecture 2-1: Point Estimation | 1–4 |
| Lecture 2-2: Interval Estimation | 1–3, with the original nested subparts |
| Lecture 2-3: Hypothesis Testing | 1–3; question 3 retains its optional designation |
| Lecture 2-4: Bootstrap Procedures & Clustering | 1–2; question 2 retains parts (a)–(d) |

The current export has 12 numbered questions in these four worksheets. `lec1` is a course outline with no worksheet questions. The Worksheets module also contains `handout_ols.pdf`, a worked OLS reference handout rather than a separate unanswered question set; it is not converted into additional questions.

## Sources and transcription

Questions come from the active Worksheet sections of the instructor-supplied `lec2-1.tex` through `lec2-4.tex` in the October 21 course export. Question wording, notation, subparts, hints, and optional status are preserved. Lecture outlines, commented-out material (including hidden solutions and additional questions), and the original large blank writing spaces are excluded. Source identifiers are shown under each lecture heading.

The point-estimation worksheet refers to four estimators without defining them. Its setup has therefore been added from the accompanying exported lecture handout: printed slide 5 (PDF page 7) supplies the sampling assumptions, and printed slide 15 (PDF page 19) lists the estimators. This addition is labeled separately from the worksheet questions.

The editable TeX and worksheet PDFs have small differences. This workbook follows the TeX version:

- Lecture 2-1, question 2 includes “What do you conclude?”; this is absent from the worksheet PDF but also appears in the lecture slides.
- Lecture 2-2, question 1(ii) has a more explicit decomposition and WLLN hint in the TeX.
- Lecture 2-2, question 2 has additional normality, chi-square, and independence facts in the TeX hint.

`source-manifest.json` records the source paths and SHA-256 hashes, question counts, and statement hashes. Paths are relative to the Method1 course workspace. This makes the source versions identifiable without copying instructor source comments into the workbook.

Instructor-authored questions and hints: Yiqing Xu, POLISCI 450A, Fall 2026. Included for public group collaboration with instructor authorization, confirmed by the repository owner on October 21, 2026. See [LICENSE.md](LICENSE.md): the public hub's MIT license does not relicense instructor-authored text.

The question transcription and LaTeX scaffold were prepared with Dudu (AI) assistance and checked against the active source questions. The group-answer sections are still blank.
