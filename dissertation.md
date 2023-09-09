---
title: title
subtitle: subtitle
author:
  - name: student name
    affiliations:
      - name: Centre for Advanced Spatial Analysis
        address: University College London
#bibliography: references.bib
#csl: harvard-cite-them-right.csl
link-citations: True

format: 
  titlepage-pdf:
    documentclass: scrbook

    #Formatting the title page
    classoption: ["oneside", "open=any"]
    number-sections: true
    toc: true
    toc-depth: 2
    lof: true
    lot: true
    titlepage: "bg-image"
    titlepage-bg-image: "img/casa.jpg"
    titlepage-logo: "img/ucl-logo.jpg"
    titlepage-theme: 
      bg-image-size: "0.4\\paperwidth"
      logo-size: "0.5\\paperwidth"
      title-fontstyle: "huge"
      elements: ["\\titleblock", "\\authorblock", "\\affiliationblock",  "\\vfill", "\\logoblock", "\\vfill", "\\footerblock"]
      affiliation-space-after: "0pt"
    titlepage-header: "The Publisher"
    titlepage-footer: |
      Module Title: Dissertation 22/23\
      Course Code: CASA0010\
      Date: Due Date\
      Academic Supervisor: Supervisor Name\
      Word Count: x 
      \
      This dissertation is submitted in part as a requirement for the MSc in the Centre for Advanced Spatial Analysis, Bartlett Faculty of the Built Environment, UCL.
    coverpage-include-file:
      - tex/copyright.tex
    titlepage-include-file:
      - tex/abstract.tex

    #Formatting the coverpage
    coverpage: "great-wave"
    coverpage-title: "title"

    coverpage-footer: "student name"
    coverpage-bg-image: "img/TheGreatWaveoffKanagawa.jpeg"
    coverpage-theme:
      page-html-color: "FFFFFF"

      title-fontsize: 30
      title-align: "right"
      title-bottom: "10in"
      header-style: "none"
      author-style: "none"
      footer-fontsize: 20
      footer-align: "right"
      footer-bottom: "8.0in"
      date-style: "none"
      bg-image-fading: "north"
    keep-tex: false

    # Code to format headers on pages without titles (A single #)
    include-in-header:
      text: |
        \usepackage{fancyhdr}
        \pagestyle{fancy}
        \fancyhead[L]{Student Number: Student Number}
        \fancyfoot[L]{MSc Dissertation}
        \addtokomafont{disposition}{\rmfamily}
    
    # Code to change the size of the page borders. 
    geometry:
      - top=25mm
      - left=20mm
      - right=20mm
      - bottom=25mm
      - heightrounded
    colorlinks: true
    highlight-style: github
    papersize: a4

# Setting the figure positions to 'here'.
fig-pos: 'H'
---

# Introduction

# Literature Review

# Methodology

# Results

# Disussion

# Conclusion

# References {.unnumbered}

# Appendix {.unnumbered}

