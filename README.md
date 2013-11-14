# PhD thesis

- To build the thesis: `make`
- Clean-up the temporary files: `make clean`
- Figure should have maximum 570px of width
- Numbering for figures in FigureX-Y where X is the chapter number and Y the figure number in the chapter.
- To create figures:
    1. Create a PowerPoint document with width 5.5 in
    2. Add content - font is Euclid and size 12
    3. Adjust heigh to remove white space, maximize when re-sizing
    4. Export as PDF in folder
    5. Done
- Assemble PDFs: `pdfunite fig1-1.pdf fig1-2.pdf sum.pdf`
- Chapter 1: `pdfunite fig1-1.pdf fig1-2.pdf fig1-3.pdf fig1-4.pdf fig1-5.pdf fig1-6.pdf fig1-7.pdf fig1-8.pdf fig1-9.pdf fig1-10.pdf fig1-11.pdf fig1-12.pdf fig1-13.pdf sum.pdf`

## N.B.
- Installed the package `texlive-latex-extra` to make it work.
