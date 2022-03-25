# N. Kostin's LaTeX Templates

![Example LaTeX](images/klein_gordon.png?raw=true)

## Why So Many Packages?

The `preamblex.tex` file that I input into nearly every document (my full preamble) is extremely long. You probably won't need so many packages (or all the CSS colors). That said, LaTeX on its own is fairly bloated, and I don't think it's even worth optimizing for compilation time. As such, every document I write contains the line `\input{preamblex}` so that I always have access to all these packages.
