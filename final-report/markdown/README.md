# Markdown VXML Final Report

There are two markdown files in this directory. You may use either as a template
to write your final report.

  * VXML-Final-Report-minimal.md: A basic markdown template for your report
  * VXML-Final-Report-full.md: A full pandoc formatted report.

These files only differ in the final format of the output they will produce.
Once your report is complete we will be using the -full template to generate a
final PDF version.


## Basic Format

The basic template uses only [basic
markdown](https://daringfireball.net/projects/markdown/syntax) syntax. Writing
markdown is very much like writing plain text, but adds support for formatted
headings, lists, links and images. You can see some examples and documentation
on [this tutorial page](https://github.github.com/gfm/)

We will be using a flavour of markdown which allows you to include both inline
and numbered equations. To add an inline equation, simply surround the
corresponding latex commands with `$` symbols, e.g. $\int f(x)$. For numbered
equations, surround the entire expression with double `$` characters, e.g.
$$
  \sum_{n=1}^\infty \frac{1}{n^2} = \frac{\pi^2}{6}
$$.

These expressions will then be properly rendered in $\LaTeX$ on both the website
and in the PDF version of your final report.


## Full Format

The -full file contains a [pandoc](https://pandoc.org/) header (between the
`---` markers) which allows us to add more structure when producing the final
PDF format of your report (such as logos, headers, etc.). If you are familiar
with pandoc, and have it installed, you can generate a formatted PDF of your
report with a command such as
```
pandoc -O VXML-Final-Report-full.pdf VXML-Final-Report-full.md

If you are *not* familar with pandoc, we recommend that you use the basic
template to produce your report (VXML-Final-Report-minimal.md). The actual
markdown content of your will be the same regardless, and once you have
submitted your report, PIMS staff will merge it into the -full template to
produce the finished PDF.
