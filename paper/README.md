# Final paper

This directory contains:

- The bibliographical database: [bibliography.bib](bibliography.bib).
- The LaTeX template for the final paper: [rt-npe.tex](rt-npe.tex)

First and foremost, change the name of the LaTeX file so it also contains your team name, e.g. `rt-npe-pjm-05.tex` for the 5th team supervized by Pieter-Jan Maenhaut.

Collaboration tip: if you assign different sections of the paper to different team members, it can be useful to keep them in separate files. That way, the probability of merge conflicts will be greatly diminished when each team member is changing the document in parallel.

The main document would contain e.g.:

```latex
\include{introduction}
\include{literature-review}
\include{methodology}
% ...
```

A file `introduction.tex` would then contain the introduction, e.g.:

```latex
\section{Introduction}
\label{sec:introduction}
% ...
```

The same goes for the other sections.

