# Naming standards and conventions

*   The following files are provided for your configuration:

    -   `config.sty`: The names of you, your committee members,
	department, and defense month &amp; year.  You may append
	extra-special commands to the file, too
    -   `wsudissertation.sty`: WSU dissertation formatting

*   The root of the manuscript is in:

    -   `00-dissertation.tex`: Comment chapters and bibliography for 
	quick debugging.  Run `pdflatex` on this one.

*   All front matter is given in `0[1-7]-{*,name-of-section}.tex` files.
    These are:

    -   `01-title.tex`: The title page
    -   `02-copyright.tex`: The copyright
    -   `03-signatures.tex`: The signature page
    -   `04-acknowledgements.tex`: Your acknowledgements
    -   `05-abstract.tex`: Your abstract section
    -   `06-lists.tex`: Table of contents and list of figures & tables
    -   `07-dedication.tex`: You dedication page (optional)

*   All of the chapters are:

    -   `11-chapter-1.tex`: e.g. Introduction
    -   `12-chapter-2.tex`: e.g. Literature Review
    -   `13-chapter-3.tex`: e.g. Methods
    -   `14-chapter-4.tex`: e.g. Results and Conclusions

* The bibliography shall be in:

    -   `references/`: Uses `BibTeX` entries 
        ([gscholar.py](https://github.com/venthur/gscholar) is your
	friend)
