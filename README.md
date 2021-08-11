# N. Kostin's LaTeX Templates

![Example LaTeX](images/klein_gordon.png?raw=true)

## Why So Many Packages?

The `preamblex.tex` file that I input into nearly every document (my full preamble) is extremely long. You probably won't need so many packages (or such a rich variety of colors). That said, LaTeX on its own is fairly bloated, and I don't think it's even worth optimizing for compilation time. As such, every document I write contains the line `\input{preamblex}` so that I always have access to all these packages.

## A Point of Caution with the Beamer Class

Note that the example beamer slideshow (in the presentation directory) has it's own `preambleb.tex` file. Some of the custom environments I've defined in my full `preamblex.tex` file throw errors when used with the beamer class.

## What's in Here?

So far this repo contains the following:
+ A comprehensive preamble file
+ A comprehensive bibliography file
+ Standard homework template for university coursework
+ Beamer presentations
+ Short articles (includes example on good practice)
+ My CV/résumé
