# template für eine titelseite im htw dd design
* erstellt mit lyx (tex files werden bereitgestellt)
* titelseite über include in das documment einbinden
* logo ersetzen
* ein Beispiel mit, das andere ohne Logo

```latex
\begin{document}
\include{tex/Titelseite}
\newpage{}
\include{tex/Titelseite-Logo}
%...
\end{document}
```

[Beispiel PDF](output/example.pdf)

Logos können [hier gefunden werden.](https://www.htw-dresden.de/de/intern/marketing/corporate-design.html)
