# Writing Theses in LaTeX Problem Sheet

Perform all the following exercises in a single LaTeX project. This will build up the basic structure of a thesis.

## Creating a Document

* Create a new LaTeX project in whatever LaTeX editor you prefer
* If you did this in Overleaf, delete any sample text in the document
* Create a new report document
* Select the main font-size to 12pt
* Select the type of page you want to write on (A4)
* Set the margins such that they are symmetric and over 1cm
* Test how it looks with some blindtext or other nonsense text
* Verify page numbers appear on each page


## Line Spacing

* Use the `linespread` command to make the spacing for document 1.5 or 2 times
* Include an indented quotation using the `quote` and `singlespace` environments
* Include a footnote with single-lined spacing


## Title Page

* Make a title page you find aesthetically pleasing
* Ensure it follows all the requirements laid down by Imperial


## Thesis Frontmatter

* Add an abstract
* Add a statement of originality
* Add a copyright statement
* Use `blindtext` or other placeholder text for the content


## Contents and Appendices

* Add some chapters, appendices sections and sub-sections to your document
* Add a table and figure to your document (these can be very simple)
* Add a table of contents, list of figures and list of tables to your document
* Add a chapter to your table of contents named `Supplementary Material` without creating a new chapter in your pdf
* Add a new table to the list of tables in this new chapter without the table appearing in your document
* Add a new figure to the list of figures in this new chapter without the figure appearing in your document

## Bibliography Management

* Create a .bib file with at least one reference in it
* If you use a reference management software, ask it to export your reference library as a .bib file, otherwise, make up a few references by hand
* Cite at least one references in your text
* Extension: Find a new reference, add it to your reference manager, then add it to your .bib file. Cite it in your text.

## Thesis Structure

* Create a directory for each chapter and appendix in your thesis. Create a directory for the frontmatter too.
* Use the `include` command to include each document in your `main.tex` file
* Create a directory in each chapter directory for figures. You will need to update the file paths in your `\includegraphics` commands so the path point to these directories.
* If you're unsure of any syntax, you can consult the [example](https://www.overleaf.com/read/zqkcmdtmtpyc#95f6e5) or ask the tutor.
* Extension: Look through the [example](https://www.overleaf.com/read/zqkcmdtmtpyc#95f6e5) and try to understand how and why it is structured the way it is. Ask the tutor if you have any questions about it.
