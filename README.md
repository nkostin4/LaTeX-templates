# N. Kostin's LaTeX Templates

![Example LaTeX](images/klein_gordon.png?raw=true)

## Major Changes Coming Soon

Stay tuned for major changes! I'm planning to organize and restructure this repo entirely.

## Why So Many Packages?

The `preamblex.tex` file that I input into nearly every document (my full preamble) is extremely long. You probably won't need so many packages (or such a rich variety of colors). That said, LaTeX on its own is fairly bloated, and I don't think it's even worth optimizing for compilation time. As such, every document I write contains the line `\input{preamblex}` so that I always have access to all these packages.

## A Point of Caution with the Beamer Class

Note that the example beamer slideshow (in the presentation directory) has it's own `preambleb.tex` file. Some of the custom environments I've defined in my full `preamblex.tex` file throw errors when used with the beamer class.

## What's in Here?

So far this repo contains the following:
+ A super comprehensive preamble file called `preamblex.tex`
+ Short articles
  + References with `biber`, accompanied by bibliography file
  + An article containing many examples on good practice
+ Report template
+ Beamer presentations template
+ Homework coverpages for university coursework
  + A short bibliography file with some textbooks I've used in uni
+ My CV/résumé

Coming soon:
+ Migrate to using named CSS colors in `preamblex.tex`
  + Current colors will be deprecated 
+ More beamer presentations
  + Include more themes
  + Possibly go through the rigmarole of creating my own theme?
+ Custom logo/artwork with TikZ
