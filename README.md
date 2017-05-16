The D Foundation supports students in conducting research projects around the D language. Research reports and other documents are stored on a per-organization and per-semester -basis in the repository.

# Repository Structure

The top-level folders are acronyms of the organization, i.e. `upb` for _University POLITEHNICA of Bucharest_. Organization folders contain per-semester folders such as `2016-2017-sem1, i.e. the 1st semester in the 2016-2017 academic year.

When adding a research contribution (report, thesis, paper), create a subfolder named after the project you work on on the semester folder, e.g. `compiler-as-a-library`. In that folder place the LaTeX source code files for the research report. If you write slides in LaTeX Beamer (or another text-based format), create a `slides` subfolder in the report/thesis folder. Be sure to add a `Makefile` file both for the reseach report/thesis and for the slides.

A sample repository structure is:

```
|-- README.md
`-- upb
    |-- 2016-2017-sem1
    |   `-- compiler-as-a-library
    |       |-- Makefile
    |       |-- report.tex
    |       `-- slides
    |           |-- Makefile
    |           `-- compiler-as-a-library.tex
    `-- 2016-2017-sem2
```
