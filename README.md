# em-poster

Poster template for the Engineering Mechanics graduate school, The Netherlands.

## Usage

```latex
\documentclass[a4paper]{article}

\usepackage{emposter}
\usepackage{multicol}

\title{...}

\author{...}

\affiliation{...}

% university logo, in footer (left)
\university{\includegraphics[height=1.0\logoheight]{...}}
% additional logo's, in footer (right)
\rightlogo{...}

% progress bar in the footer (center):
\progresstype{...}       % MSc/PhD/Postdoc
\progresssections{...}   % total number of progress sections (years)
\progressfraction{...}   % fraction of the bar to be filled

\begin{document}

\maketitle

\begin{multicols}{2}

\section{...}

...

\end{multicols}

\end{document}
```

