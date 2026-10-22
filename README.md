# Xintong Li — English CV

This repository contains the one-page English version of my CV, maintained in LaTeX for GitHub and Overleaf. The layout is adapted from [billryan/resume](https://github.com/billryan/resume); its MIT license is included in `TEMPLATE-LICENSE`.

## Overleaf

Import `licns657/CV_en` from GitHub, set `main.tex` as the main document, and select **XeLaTeX** as the compiler. After later GitHub updates, use Overleaf's GitHub **Pull** and recompile.

The project uses TeX Gyre fonts and common TeX Live packages, with no local fonts required. `assets/resume_photo.png` supplies the headshot.

## Resume variants

- `main.tex`: original English CV, preserved without changes.
- `cv_codeagent_minionerec.tex`: updated English CV featuring Code Agent inference optimization, style memory, and the MiniOneRec generative recommendation project (2026-10-22).

Both files are standalone documents and share `assets/resume_photo.png`. The updated English version retains the Singapore contact number used in the original English CV.

In the linked Overleaf project, use GitHub **Pull** to retrieve updates. Set **Main document** to the desired `.tex` file and select **XeLaTeX** as the compiler. Selecting a main document does not remove the other version.
