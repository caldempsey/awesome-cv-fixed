# Awesome CV [![Example](https://img.shields.io/badge/example-pdf-green.svg)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume.pdf)


[**Awesome CV**](https://github.com/posquit0/Awesome-CV) is LaTeX template for a **CV(Curriculum Vitae)** or **resume** or **cover letter** inspired by [Fancy CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv). It is easy to customize your own template, especially since it is really written by a clean, semantic markup.

## Changes

Changes made to AwesomeCV include editing the skills section and fixing compilation errors for the skills section. Skills section demonstrated odd vertical alignment which has been resolved by editing awesome-cv.cls. The resume section has been removed as resumes can be built using the CV import tools (judged superfluous). This change makes the template easier to understand and edit using documentation provided (needless complexity of too many files for unfamiliar users who just want to 'get on with it'). 

To compile the CV please install xelatex and use "xelatex [or xelatex.exe if on Windows] cv.tex" respectively. This file also contains details on how to construct your CV. Essentially the process of compiling your CV (which will be output as "cv.pdf") is procedural beginning at cv.tex, and then following the import statements found in cv.text in sequence.

For example where at the end of the procedural cv.tex declares...

```
\input{cv/summary.tex}
\input{cv/skills.tex}
\input{cv/experience.tex}
\input{cv/education.tex}
\input{cv/projects.tex}
```

This just means the CV will be compiled using execution of those files in that order. You could edit this to suit your needs...

```
\input{cv/skills.tex}
\input{cv/education.tex}
\input{cv/experience.tex}
\input{cv/projects.tex}
```

For the job seekers out there, happy hunting! 
