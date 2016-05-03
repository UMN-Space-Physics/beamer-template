# Beamer Template

Beamer is a package for using LaTeX to make powerpoint presentations. This template includes a few example slides, and shows a few useful tricks -- backup slides that don't count toward the page count, superimposing a credit over an image's corner, highlighting parts of equations, etc. 

The slides themselves are laid out in `talk.tex`. 

Macros are defined in `my_definitions.tex`. These are shortcuts for words that get used a lot, like putting the proper accent in Alfvén. 

The `makefile` keeps track of compilation using `latexmk`. 

Figures are stored in the `figures` directory. PDF images are best. 

In Bash, just type `make` to compile the PDF. On Windows, any TeX environment (TeXmaker, etc) should be able to figure it out. 

No built-in Beamer theme is close to UMN colors. However, a semi-official UMN Beamer theme has been created by Konstantin Golyaev, and can be found at `http://www.kgolyaev.com/node/7`. 
