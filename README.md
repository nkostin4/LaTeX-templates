# N. Kostin's LaTeX Templates

![Example LaTeX](images/klein_gordon.png?raw=true)

## Why So Many Packages?

The `preamblex.tex` file that I input into nearly every document (my full preamble) is extremely long. You probably won't need so many packages (or all the CSS colors). That said, LaTeX on its own is fairly bloated, and I don't think it's even worth optimizing for compilation time. As such, every document I write contains the line `\input{preamblex}` so that I always have access to all these packages.

## What's in Here?

So far this repo contains the following:
+ A super comprehensive preamble file called `preamblex.tex`
+ Short articles
  + References with `biber`, accompanied by bibliography file
  + An article containing many examples on good practice
+ Report template
+ Homework coverpages for university coursework
  + A short bibliography file with some textbooks I've used in uni
+ My CV/résumé
