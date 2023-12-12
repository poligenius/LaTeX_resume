# AltaCV, LaTeX CV/Résumé class

v1.1 (25 July 2023), by Marco Marini (poligeniushelp@gmail.com)

## Intro

This repo is to give you, LaTeX lover, a cool idea for a resume.
You can use this template to create in few minutes your own personal cv.

Below you can fine a selection of point to follow to personalize your cv, have fun.
For any question you can write me at [poligeniushelp@gmail.com](mailto:poligeniushelp@gmail.com).

## Resume Look
![Screenshot 2023-12-12 alle 20 11 59](https://github.com/poligenius/LaTeX_resume/assets/48245313/2f275e6f-24b3-4c78-9e07-a1a1647f61ab)


## Editor
In case you don't know LaTeX, don't worry, you can use [Overleaf](https://overleaf.com), it is a cool online free editor,
just create an account, create a new project and load the files inside this repo.

To have the files on your pc just clone this repo:

1) select the location where you want to store the file in your terminal

   ```bash
   cd Projects/resume
   ```

2) clone the repo

   ```bash
   git clone https://github.com/poligenius/LaTeX_resume.git
   ```

After you have loaded the files you will need only to change the content of the files in order to write whatever you want in your resume.
It is really intuitive, in case you need more info on what to modify you can check the following sections.

## Requirements and Compilation

* At line 76 of main you can insert your personal info
* page1sidebar.tex contains the code for the right part of the cv
* remember to substitute the image with your photo and use a png format
* If you would like to change the colors go at line 48 of main.tex
* AltaCV uses [`fontawesome`](http://www.ctan.org/pkg/fontawesome) and [`academicons`](http://www.ctan.org/pkg/academicons); they're included in both TeX Live 2016 and MikTeX 2.9.
* Loading `academicons` is optional: enable it by adding the `academicons` option to `\documentclass`.
* Can now be compiled with pdflatex, XeLaTeX and LuaLaTeX!
* However if you're using `academicons`, you _must_ use either XeLaTeX or LuaLaTeX. If the doc then compiles but the icons don't show up in the output PDF, try compiling with LuaLaTeX instead.
* The samples here use the [Lato](http://www.latofonts.com/lato-free-fonts/) font.

## Donations
The code is here for you to be read, edited, modified, reused, for free, do whatever you want!
However, if you'd like to [offer me](https://paypal.me/MarcoMariniING?country.x=IT&locale.x=it_IT) a coffee or a beer, then cheers! xD
