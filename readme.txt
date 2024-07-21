# LaTeX Resources
Overview:

This repository contains all the materials used for reference in the LaTeX workshop.

Requirements

    LaTeX Distribution: Ensure you have a LaTeX distribution installed on your system (e.g., TeX Live, MiKTeX).

    Text Editor: You can use any text editor to write LaTeX files. Consider using editors with LaTeX support like TeXstudio or VS Code with LaTeX Workshop extension.

Getting Started

    Install LaTeX: Install a LaTeX distribution appropriate for your OS:
        Linux (Ubuntu):

        bash

    ```sudo apt update
    sudo apt install texlive```

    Windows: Install MiKTeX from miktex.org.
    macOS: Install MacTeX from tug.org/mactex.

Write LaTeX Files: Create a .tex file using your preferred text editor (e.g., example.tex):

latex

\documentclass{article}
\begin{document}
Hello, LaTeX!
\end{document}

Compile LaTeX Files: Use pdflatex or latexmk to compile your .tex files:

bash

```pdflatex example.tex
```

or

bash

```latexmk -pdf example.tex```

View Output: Open the generated PDF file with:

bash

    xdg-open example.pdf

Additional Resources:

    Documentation: https://www.overleaf.com/learn
    Overleaf: Online LaTeX editor with tutorials and templates.
    TeX Stack Exchange: Q&A site for LaTeX users.