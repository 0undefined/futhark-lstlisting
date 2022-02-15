# Futhark lstlisting language definition

This latex package adds futhark language definition for the listings package for
latex. To use it, copy the `futhark.sty` file (and _optionally_ the `style.sty`
to the same folder as your preamble, and after importing the listings package
add
```
\usepackage{futhark}
\usepackage{style}
\lstset{language=futhark,style=futhark}
```
To your preamble. It covers most (if not all) keywords in the futhark prelude,
with the exception of type-functions -- ie. functions such as `i32.max` will not
be highlighted.

See the [example](https://github.com/0undefined/futhark-lstlisting/blob/master/example.tex) for a brief example.
![example.png](https://raw.githubusercontent.com/0undefined/futhark-lstlisting/master/example.png)

The colors are a little wonky, but can easily be changed to your hearts content
in the [style.sty](https://github.com/0undefined/futhark-lstlisting/blob/master/style.sty)-file
