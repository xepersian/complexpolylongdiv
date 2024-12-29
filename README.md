# The complexpolylongdiv Package
The `complexpolylongdiv` package provides a simple interface for typesetting (complex) polynomial long division.

The official versions of the package are released on [CTAN](https://ctan.org/pkg/complexpolylongdiv).

## Using the Package
The following example illustrates how the package can be used.
````tex
\documentclass{article}
\usepackage{complexpolylongdiv}
\begin{document}
\begin{equation}
\begin{complexpolylongdiv}
&x+1-2i \\
x-1&\complexpolyquotient{x^2-2ix+6}\\
-&\underline{x^2-x}\\
  -&(1-2i)x+6\\
  -&\underline{(1-2i)x-(1-2i)}\\
  &7-2i\\
\end{complexpolylongdiv}
\end{equation}
\end{document}
````

## Reporting Issues
If you think that you have found an issue in the package, please use 
[the package issue tracker](https://github.com/xepersian/complexpolylongdiv/issues) 
to report it.

## Discussions
You may also have conversations, ask questions and post answers
without opening issues using the [Discussions space](https://github.com/xepersian/complexpolylongdiv/discussions).

## Announcements
The announcements for the new releases of the package will
also appear in the Discussions space under the [Announcements
category](https://github.com/xepersian/complexpolylongdiv/discussions/categories/announcements).

