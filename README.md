# LaTeX template for Academy of Management (AOM) submissions

This is an unofficial template for authors preparing a manuscript for an Academy of Management journal (or the annual conference) using the [LaTeX document preparation system](https://www.latex-project.org). It is fully compliant with the editorial "[Style Guide for Authors](https://aom.org/docs/default-source/publishing-with-aom/aom_journal_style_guidea3b84b773e3649569a17a05e14cc6eaf.pdf?sfvrsn=f94177b2_4)" and the [conference paper submission sample](https://aom.org/docs/default-source/events/sample_submission_paper.pdf) provided by the [Academy](https://aom.org).

## Features
- Times New Roman 12-point type both as text and math font
- US letter page size with one-inch margins
- Double-spaced lines in LaTeX style (or optionally in MS Word style)
- Three levels of unnumbered section headings in AOM style
- Title page with manuscript title, author blocks (including names, affiliations, and complete addresses), and acknowledgements
- Abstract page with keywords and submission ID header
- Custom environments with automatic numbering (see below) for hypotheses, tables, and figures
- Tables and figures automatically placed at the end of the manuscript with in-text markers indicating their position in the text
- References in AOM style
- Multiple appendices with proper section numbering for tables and figures (e.g., Table A1 or Figure B2)
- Can be compiled by all common TeX typesetting engines (such as [pdfLaTeX](https://www.math.rug.nl/~trentelman/jacob/pdflatex/pdflatex.html) or [XeLaTeX](http://www.xelatex.org/))

## Custom environments
- `addfigure` and `addlfigure`: Portrait and landscape figure environments with 4 arguments: (1) width, (2) image file name, (3) caption (with optional label), and (4) figure note
- `tptable` and `ltptable`: Portrait and landscape "three-part" table environments with captions and notes with the same width as the table
- `hypothesis`: Hypothesis environment with automatic numbering that can be changed at any point from normal hypothesis to sub-hypothesis numbering via `\subhypothesis` and `\normhypothesis` commands

## Advantages over MS Word

Here is a [StackExchange](https://academia.stackexchange.com/questions/5414/what-are-the-advantages-or-disadvantages-of-using-latex-for-writing-scientific-p) discussion on advantages of LaTeX over Word. LaTeX produces `.pdf` documents. If you need to convert this output to `.docx`, you can open the `.pdf` file in Word and it will be automatically converted.

## Used packages
- `authblk`: Support for footnote style author/affiliation blocks when there are 4 or more authors
- *under construction*

## Inspirations
