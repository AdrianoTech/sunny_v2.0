---
title: 'Sunny: A Python program to ease Ussing Chamber data interpretation'
tags:
  - Python
  - Excel
  - ussing chamber
  - ion transport
  - physiology
authors:
  - name: Adriano Sanna
    orcid: 0000-0000-0000-0000
    equal-contrib: true
    affiliation: "1"
affiliations:
 - name: JLU University Giessen, Institute for Anatomy and Cell Biology, Germany
   index: 1
date: 24 August 2023
bibliography: paper.bib

# Optional fields if submitting to a AAS journal too, see this blog post:
# https://blog.joss.theoj.org/2018/12/a-new-collaboration-with-aas-publishing
doi: 10.3847/xxxxx <- update this with the DOI from AAS once you know it.
journal: The Journal of Open Source Software 
---

# Summary

Ussing Chamber is a device used to record ionic transport in biological membranes. 
These device come with a software that produce files using the .cla extension. 
These file can be imported into excel, but the data elaboration takes a 
significant amount of time for the operator. The presented program, sunny.py, 
can almost instantly convert the .cla files into .xlsx file with a graphic 
user interface (GUI).This conversion allows a complete automatization in data 
analysis: (1) the user will have the new tables having in the first line 
the titles and in the following lines directly the data. Data in this format 
can be directly imported into R (2) the intervals of drugs administration are 
reported in a specific column, making it easier to the operator the experiment 
evaluation (3) delta of the electric Intensity is automatically calculated.


# Statement of need

"Sunny.py" is a program developed to make Ussing Chmaber data analysis faster
and more riable. By importing the Ussing Chamber data (.cla) into excel the 
user encounter many obstacles: (1) data are not ordered in a title-data manner
(2) it´s difficult to find the time of chemicals injection (3) intervals
between two chemical administrations are not specified (4) basic statistic
is not reported. All this work take a significant ammount of time to a 
scientist and considering that the operator is dragging and copying intervals of data, the human
error becomes possible. With Sunny it is to observe a completely automatization of
this process. The user will use an intuitive point and click interface. The 
design is very simple with only 4 buttons: one for selecting the file,
another one for selecting the file destination, a tick-button to save 
the preliminary graph and a button to convert the file. 


# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$

You can also use plain \LaTeX for equations
\begin{equation}\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}
and refer to \autoref{eq:fourier} from text.

# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

If you want to cite a software repository URL (e.g. something on GitHub without a preferred
citation) then you can do it with the example BibTeX entry below for @fidgit.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

Figure sizes can be customized by adding an optional second parameter:
![Caption for example figure.](figure.png){ width=20% }

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References