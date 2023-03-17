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
``` latex
    % Acronyms
    \acro{api}[API]{Application Programming Interface}
    \acroplural{api}[APIs]{Application Programming Interfaces}

    % Picture
    \begin{figure}[ht]
        \centering
        \includegraphics[width=\textwidth, scale=0.3]{<path to picture>.png}
        \caption{Some caption}
        \label{fig:some label}
    \end{figure}
```