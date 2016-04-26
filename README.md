# LaTeX Template for NIT Trichy B.Tech Thesis

This is (I think) the first ever LaTeX template for the B.Tech thesis of NIT Trichy (And probably the Masters and PhD theses) too. This template is focused on meeting the specifications for the B.Tech thesis [given here](http://www.nitt.edu/home/academics/rules/Thesis_Guidelines.pdf) but it should be simple to modify it for other degrees as well. 

The template has separate files to generate the titlepage, abstract and bonafide. You can edit the text in those files to add in your own name, roll number and department. The chapters are also organized in separate files and all the images should be placed inside the images folder.

If you add a new chapter file, make sure you remember to insert it into the main.tex file using `\input{ChapterX}` following the style of the previous insertions. 

# How to compile it in Ubuntu 14.04.
I'm compiling using texlive on ubuntu but it should work with MikTeX and other tex comilers on windows and mac as well.
 * Install texlive on ubuntu.
 * Install [latexmk](www.phys.psu.edu/~collins/software/latexmk-jcc/) (a perl script that automates compilation): `sudo apt-get install latexmk`
 * Download this repository as a zip file
 * `cd` to the unzipped folder
 * run `latexmk -pdf -pvc main.tex`
