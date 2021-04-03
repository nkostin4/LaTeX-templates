# N. Kostin's LaTeX Templates

![Example LaTeX](images/klein_gordon.png?raw=true)

## Why Do I Include So Many Packages?

The `preamblex.tex` file that I input into nearly every document (my full preamble) is extremely long. Most users will not need so many packages or such a rich variety of colors. That said, LaTeX is a fairly bloated program, and I don't think it's even worth optimizing for compilation time. On those grounds, I include pretty much every package I've worked with (or at least know how to use) in pretty much all my documents.

## A Point of Caution with the Beamer Class

Note that the example beamer slideshow (in the presentation directory) has it's own `preambleb.tex` file. Some of the custom environments I've defined in my full `preamblex.tex` file throw errors when used with the beamer class.

## What's in Here?

So far this repo contains the following:
+ A comprehensive preamble file
+ A comprehensive bibliography file
+ Standard homework template for university coursework
+ Beamer presentations
+ Short articles (includes example on good practice)

Coming soon:
+ My CV/résumé
