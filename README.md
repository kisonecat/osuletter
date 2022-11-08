# osuletter class

This LaTeX document class produces the appropriate letterhead for the
math department.

It expects to be compiled (twice!) with `xelatex` because it uses
`fontspec` to pull in the fonts `Buckeye Sans` and `Buckeye Serif`p.

It also expects the file `signature.pdf` to be available in order to
place a picture of your signature on the bottom of the page.

# Minimal working example

```latex
\documentclass[12pt]{osuletter}

\signature{Prof. First Last}

\begin{document}
\begin{letter}{}
\opening{Dear Recipient,}

My words go here.

\closing{Sincerely,} 
\end{letter}
\end{document}
```
