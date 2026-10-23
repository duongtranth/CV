# Tran The Duong — Curriculum Vitae

English CV covering computer vision, multi-object tracking, robotics, and control.

- [View / download the CV](Tran_The_Duong_CV.pdf)
- [Download the LaTeX project for Overleaf](Tran_The_Duong_CV_LaTeX.zip)
- [Personal website](https://sites.google.com/view/theduongtran/home)

## Edit the CV

| File | Contents |
| --- | --- |
| `main.tex` | Layout, packages, and page structure |
| `sections/profile.tex` | Education, research experience, master's thesis, and manuscripts in preparation |
| `sections/robotics.tex` | Robotics/control projects and earlier engineering experience |
| `sections/portfolio.tex` | Additional tracking research, coursework, skills, and awards |

## Build on Overleaf

1. Download `Tran_The_Duong_CV_LaTeX.zip`.
2. In Overleaf, choose **New Project → Upload Project**.
3. Select `main.tex` as the main document and **pdfLaTeX** as the compiler.
4. Edit the relevant section and recompile.

## Build locally

With a LaTeX distribution and latexmk installed:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error -jobname=Tran_The_Duong_CV main.tex
```

Commit the updated source and PDF together after rebuilding.

## Template credits

Adapted from [Jake's Resume](https://github.com/jakegut/resume) by Jake Gutierrez, based on [sb2nov/resume](https://github.com/sb2nov/resume). The template's MIT license is retained in `LICENSE.txt`. Personal CV content belongs to Tran The Duong.
