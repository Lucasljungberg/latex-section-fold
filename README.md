# latex-section-fold
Plugin for Sublime Text to support code folding on sections, subsections, and subsubsections

The plugin adds a manual fold button for sections:

```
15 v|\section{Cool story}
16  |Once upon a time ...
17  |...
18 v|\subsection{Story in a story}
19  |...
```
Press the fold button, and it folds into:
```
15 >|\section{Cool story}
18 v|\subsection{Story in a story}
19  |...
```

It doesn't do much else, really.
