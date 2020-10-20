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

Table with fixed size and middle aligment. The aligning options are m for middle, p for top and b for bottom.

```
\begin{table}[h]
    \centering
    \begin{tabular}{|m{15em} | m{15em}|}
         & \\
    \end{tabular}
    \caption{Types of Robots}
    \label{tab:my_label}
\end{table}
```
