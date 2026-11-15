# Resume

The active resume uses a layout inspired by [Jake's Resume](https://github.com/jakegut/resume), with serif typography, ruled small-cap headings, compact bullets, and a centered contact header. Content remains in sections/; formatting is in jake-resume.sty. The archived resume2023.tex still uses Awesome CV.

## Compile

Install MiKTeX on Windows, enable missing-package installation, and open a new terminal in this directory:

```powershell
pdflatex -interaction=nonstopmode -halt-on-error resume-positron.tex
```

Alternatively, upload the repo to Overleaf, select resume-positron.tex as the main document, and use pdfLaTeX. The archived resume2023.tex requires XeLaTeX.

The checked-in resume.pdf predates this conversion. Compiling resume-positron.tex creates resume-positron.pdf. Review page count and line wrapping after compiling; all existing content was preserved.


