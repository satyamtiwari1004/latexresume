résumé
======

This, you may be surprised to know, is my résumé. To see it in action,
visit [it on my website](https://github.com/satyamtiwari1004/latexresume/resume.pdf).

Building
--------

This repository contains the LaTeX source for my resume.

## Prerequisites
- **XeLaTeX**: Make sure you have a TeX distribution installed. On Mac, [MacTeX](https://tug.org/mactex/) is recommended.

## How to Compile
To generate the PDF from the LaTeX source, run the following command in the project directory:

```sh
xelatex resume.tex
```

This will produce `resume.pdf` in the same directory.

## Useful Commands (Executed on Mac)
```sh
# Compile the LaTeX file
xelatex resume.tex

# (Optional) Clean up auxiliary files
rm *.aux *.log *.out
```

## Notes
- If you update the `.tex` files, re-run the `xelatex` command to regenerate the PDF.
- For best results, use XeLaTeX instead of pdfLaTeX, as this template uses custom fonts and Unicode features.

Acknowledgements
----------------

The latex version of this résumé is based extensively on the awesome résumé of
[Jarrell Waggoner](https://github.com/malloc47/cv).
