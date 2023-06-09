---
title: | 
 | Jeremy D Harris, PhD
author: |
 | [Here is my CV](https://github.com/Jeremy-D-Harris/cv_jdh_2022/blob/main/CV_JDH_Feb2023.pdf)
# date: '2023-04-23'
# runtime: shiny
#bibliography:/Users/malishev/Documents/Melbourne Uni/Thesis_2016/library.bib
fontsize: 12
# font-family: Courier;
# style: style="font-family:Courier"
geometry: margin=1in
documentclass: article
linkcolor: pink
urlcolor: blue
citecolor: red
output:
  html_document:
    highlight: pygments
    css: style.css  
    # code_folding: hide
    toc: yes
    toc_depth: 4
    number_sections: no
    toc_float: yes
    keep_md: true
  pdf_document:
    includes:
      in_header: # add .tex file with header content
    highlight: tango
    template: null
    toc: yes
    toc_depth: 4
    number_sections: true
    fig_width: 4
    fig_height: 5
    fig_caption: true
    df_print: tibble 
    citation_package: biblatex # natbib
    latex_engine: xelatex #pdflatex # lualatex
    keep_tex: true # keep .tex file in dir 
  word_document:
    highlight: tango
    keep_md: yes
    pandoc_args: --listings
    #reference: mystyles.docx
    toc: yes
    toc_depth: 4
inludes:
  # before_body: before_body.tex
  in_header: before_body.tex
subtitle: 
tags:
- nothing
- nothingness
params: 
  dir: "/Users/jharris387/Dropbox (Personal)/computing-resources/website"
  date: !r Sys.Date()
  version: !r getRversion()
  email: "jeremy.harris@gatech.edu"
  doi: https://github.com/jeremy-d-harris/
classoption: portrait
# ^['https://github.com/jeremy-d-harris/'] # footnote
vignette: >
  %\VignetteIndexEntry{Personal Website}
  %\VignetteEncoding{UTF-8}
  %\VignetteEngine{knitr::rmarkdown}
---

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ TeX: { equationNumbers: {autoNumber: "all"} } });
</script>


<!-- NOTE: Setting up webpage using Rmarkdown. Going by section... -->
<br>
<br>
<img src="JDHarris_headshot_crop.jpeg" align="left" alt="isolated" width="150"/>
<br>
<br>
<!-- <p style="font-family:Times"> -->
<p style="font-size: 18px">
   &ensp; Research Scientist II, [Weitz Lab](https://weitzgroup.biosci.gatech.edu/) <br>
   &ensp; Biological Sciences <br>
   &ensp; Georgia Tech, Atlanta, GA 
</p>
<br>

---

<br>

## About
<br>
<!-- <p style="font-size: 10px"> -->
Broadly, I use math models to study biological systems. In my PhD, I studied spatiotemporal patterns in neural firing rate models, advised by [Professor Bard Ermentrout](https://sites.pitt.edu/~phase/). During my postdoc'ing, I transitioned to studying virus-host dynamics across scales & systems. <br>

I am currently in the [Weitz lab](https://weitzgroup.biosci.gatech.edu/) at GA Tech in biological sciences. I did my first postdoc in biology at Emory University, supervised by [Professor Katia Koelle](https://scholarblogs.emory.edu/koellelab/group-members/) (2017-2020) after receiving my PhD in applied math at University of Pittsburgh (2017).
<!-- </p> -->


#### Weblinks <br>
- [Here is my github - trying to use actively!](https://github.com/Jeremy-D-Harris/)
- [linkedin page - not using actively :( ](https://www.linkedin.com/in/jeremy-d-harris)
- [orcid](https://orcid.org/0000-0002-6836-3620)
<!-- - [linkedin](https://www.linkedin.com/in/jeremy-d-harris) -->
<br>

---

<br>

## Research
<br>
<p>
I use math models to study the ecology and evolution of infectious diseases. Infectious diseases occur often occur across multiple scales. For instance, in epidemics models there is the individual level, where transmission is often quantified by the reproduction number, $R_0$ ("strength") and the population level, where transmission is quantifed by the observed exponential growth rate of new cases, "$r$" ("speed"). Hence, models can be used to bridge these scales, telling us about <em>hidden variables </em> from those observed. 
</p>
<br>

<!-- ### In the [Weitz Lab](https://weitzgroup.biosci.gatech.edu/) <br> -->
#### Weitz Lab (2020-Present) <br>
<details closed>
<p>
- <b> epidemic models </b>
  - asymptomatic transmission in COVID-19 using a generation interval framework <br>
  - effects of variation in transmissibility and susceptibility <br>
- <b> virus-microbe dynamics and entanglement </b>
  - latent period variability in one-step experiments
  - multiple phages form lysogens on a shared host $\rightarrow$ complex population dynamics
  - cellular responses to different bulk MOI $\rightarrow$ varying infection outcomes, e.g., lysis inhibition, pseudolysogeny 
</p>
</summary>
<br>

<!-- ### In the [Koelle lab](https://scholarblogs.emory.edu/koellelab/) <br> -->
#### Koelle lab (2017-2020) <br>
<!-- to make a collapsible section -->
<!-- <details closed> -->
<p>
<details closed>
- cellular responses to multiple infections in influenza  
- emergent population dynamics
</summary>
</p>
<br>

#### Recent Publications <br>
<!-- <details closed> -->
<p style="font-size: 10px">
- <u>Harris, J. D.</u>* , Park, S. W.*, Dushoff, J., & Weitz, J. S. (2023). How time-scale differences in asymptomatic and symptomatic transmission shape SARS-CoV-2 outbreak dynamics. Epidemics, 100664. [DOI](https://doi.org/10.1016/j.epidem.2022.100664) <br>
- Martin, B. E.* , <u>Harris, J. D.</u>*, Sun, J., Koelle, K., & Brooke, C. B. (2020). Cellular co-infection can modulate the efficiency of influenza A virus production and shape the interferon response. PLoS pathogens, 16(10), e1008974. [DOI](https://doi.org/10.1371/journal.ppat.1008974)
</p>

<br>

<p> *these folks contributed equally</p>
<!-- </summary> -->

---


## Teaching

<br>
<p>
- [QBioS Foundations Course](https://qbios.gatech.edu/course-information) (Fall 2021 & 2022) <br>
  Modules taught:
  - organismal behavior & sensing <br>
  - excitability: neurons <br>
  - excitability: cardiac cells <br>
  - biomechanics of movement <br>
  
- [ICTP-SAIFR Training Program in Quantitative Biology and Ecology](https://www.ictp-saifr.org/qbioprogram/) (Summer 2022)
  Module taught:
  - organismal behavior & sensing <br>
</p>
<br>
<br>



