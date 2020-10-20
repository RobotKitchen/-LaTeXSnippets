# -LaTeXSnippets


Remove numbers from sections

```
\section*{Title}
\subsection*{Subtitle}

```

Remove spacing in itemize

```
\begin{itemize}[noitemsep]
  \item
\end
```
Inserting pdf pages

```
\includegraphics[page={20}, width=0.9\textwidth, angle=0]{thepdf.pdf}
```

Black box surrounding text

```
\noindent\fbox{%
    \parbox{\textwidth}{%
    \begin{center}

    \end{center}
    }%
}
```
