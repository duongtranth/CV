# Tran The Duong - Curriculum Vitae

Two-page English CV covering computer vision, multi-object tracking, robotics, and control.

- [View / download the CV](Tran_The_Duong_CV.pdf)
- [Download the LaTeX project for Overleaf](Tran_The_Duong_CV_LaTeX.zip)

## Edit the CV

| File | Contents |
| --- | --- |
| `main.tex` | Typography, spacing, and two-page structure |
| `sections/profile.tex` | Contact information and education |
| `sections/research.tex` | CtrlLab, KAIST tracking research and thesis results |
| `sections/robotics.tex` | KAIST robotics and control projects |
| `sections/portfolio.tex` | Earlier experience, skills, scholarships, and additional projects |


## Build on Overleaf

1. Download `Tran_The_Duong_CV_LaTeX.zip`.
2. Choose **New Project > Upload Project**.
3. Set `main.tex` as the main document and **pdfLaTeX** as the compiler.
4. Edit the relevant section and recompile.

## Build locally

With a LaTeX distribution and latexmk installed:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error -jobname=Tran_The_Duong_CV main.tex
```

Commit the updated source and PDF together after rebuilding.

## Credits and guidance

Adapted from [Jake's Resume](https://github.com/jakegut/resume) by Jake Gutierrez, based on [sb2nov/resume](https://github.com/sb2nov/resume). The template's MIT license is retained in `LICENSE.txt`. Personal CV content belongs to Tran The Duong.

Editorial guidance: [Harvard resume guide](https://careerservices.fas.harvard.edu/resources/create-a-strong-resume/), [MIT accomplishment statements](https://capd.mit.edu/resources/resumes-writing-about-your-skills/), and [MIT CV guidance](https://capd.mit.edu/resources/cvs/). This is a personal LaTeX adaptation, not an official university template.

## Reading order

Page 1 presents education, current tracking research, and robotics/control projects. Page 2 contains supporting experience, technical skills, scholarships, and additional projects.

The editorial revision also uses [MIT EECS Communication Lab guidance](https://mitcommlab.mit.edu/eecs/commkit/cvresume/) on concrete contributions and scan-friendly organization, and [Harvard's engineering example](https://careerservices.fas.harvard.edu/resources/harvard-college-resume-example-engineering/).
