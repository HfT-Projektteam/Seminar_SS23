# hft-latex-template

## Tooling
(this is based on personal preferences)
- Visual Studio Code (see extension recommendations) 
    - LaTeX Workshop
    - LTex LanguageTool 
    - (German) - Code Spell Checker
### Literature
- Zotero (free, sync only free with webdav)
    - BetterBibLatex Plugin (for automatic bibtex export)

## Latex Knowledge Cache
**Acronyms:**
``` latex
    \acro{api}[API]{Application Programming Interface}
    \acroplural{api}[APIs]{Application Programming Interfaces}
``` 

**Reference Acronym:**
```latex
    Hier wird einen Abkürzung zum ersten Mal referenziert: \ac{api}. Und dann zum zweiten Mal: \ac{api}.
```

**Bilder:**
``` latex
    \begin{figure}[ht]
        \centering
        \includegraphics[width=\textwidth, scale=0.3]{<path to picture>.png}
        \caption{Some caption}
        \label{fig:some label}
    \end{figure}
```

**Cite:**
``` latex
    Zitieren \cite{pohlmann_quantensichere_2019}
```

You may have to run *biber* with `biber <name of document without .tex` after compiling the document and after that compile the document again.
