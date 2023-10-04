# Paper LaTeX Template

This double-spaced template is based on the [arXiv style](https://github.com/kourgeorge/arxiv-style) which is based on the [NeurIPS](https://nips.cc/) styling. The reference style includes [AEA](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-aea.bst) (lastname, firstname) and [Econometrica](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-econometrica.bst) (lastname, abbreviated firstname).

Based on the NIPS styling, it makes this paper template esthetic and convenient for reading. This template defines the styles and format in the `main.tex` preambles and collects all the imported packages in the `package.sty` making the source more transparent and easier to customize.

Various LaTeX syntaxes are also demonstrated throughout the document such as spacing, hyperlinked footers, abbreviations, coloring, listing, table-of-contents customization, hyper-referencing, figure and table formatting with decimal alignment, mathematics symbols, and graphic elements. Users can refer to the syntax during editing.

🎉 The compiled paper PDF can be viewed [here](https://www.haochehsu.com/other/Paper_LaTeX_Template.pdf).

For **Dissertation LaTeX Template**, please go to this [link](https://github.com/howardhsumail/Dissertation-LaTeX-Template.git).

---

### 🖋 The Template
This template includes:
  - Settings: `package.sty`
  - Content: `main.tex`, `reference.bib` (references database)
  - Style files:
    - arXiv style: `arxiv.sty`
    - Bibliography style: `aea.bst` and `ecta.bst`

### 📐 Usage

Users only need to customize the `package.sty` in the `Style` folder and edit the 2 **Content** files. The bibliography style is located in `main.tex`: 

```tex
\bibliographystyle{Style/aea} # Style/ecta
```

#### Online

For online editing, [download](https://github.com/howardhsumail/Paper-LaTeX-Template/archive/refs/heads/main.zip) the template, upload all the files and folders to [Overleaf](https://www.overleaf.com/), and compile the `main.tex` as demonstrated [here](https://www.overleaf.com/read/tyrxpyssfgpp).

#### Offline

For local editing, [download](https://github.com/howardhsumail/Paper-LaTeX-Template/archive/refs/heads/main.zip) the template and edit it with [Texmaker](https://www.xm1math.net/texmaker/) or [TeXstudio](https://www.texstudio.org/) (requires [MacTeX](https://www.tug.org/mactex/) for Mac and [MiKTeX](https://miktex.org/download) for Windows) or [Texpad](https://apps.apple.com/us/app/texpad-latex-editor/id458866234?mt=12).

### ⚙️ Font Size

The font size of this template is **11pt**. The default (NIPS styling) is 10pt. To modify the font size, go to the "FONT SIZE" preamble in `main.tex` and either comment out `\input{size11.clo}` (11pt) or select `\input{size12.clo}` (12pt).

### 📒 General Notes

For help, comments, bug reporting, and change requests, please [contact](mailto:howard@hsu.xyz) the [author](https://haochehsu.com). You can use or redistribute this project, however, the author takes no responsibility for whatever template usage. Finally, you are very welcome to contribute to this template.
