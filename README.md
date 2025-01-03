Hello World
================
Last update: 2025-01-03

## Intro

This is the space where I put together my notes and shared ideas about
technology, education, and research.

### Academic writing in R Markdown: A quick start guide

<a
href="https://docs.google.com/document/d/1SnHqZ_aLyog7oTKQciTlyt4eNtAA-fOAylwiQl-m2GE/edit?usp=sharing"
target="_blank">Getting started with academic writing in R Markdown</a>
is a quick start guide for researchers who want to spend their time on
writing the manuscript rather than formatting and citations.

### My computational methods and data science approach

R is a popular choice for data science and research, with R packages
offering powerful tools for data analysis and visualisation. For
example, I can perform
<a href="https://cocolaberica.github.io/ascilite22" target="_blank">a
quick tweet analysis for ASCILITE 2022 conference</a>.

For easy reference to all 657 built-in colours for plots and
visualisations in R, I generated an
<a href="https://cocolaberica.github.io/rcolortable" target="_blank">R
color table</a>.

I use computational methods to process the large volumes of data
collected from social media, and here is
<a href="https://github.com/CoCoLabErica/LIWC2015" target="_blank">my
implementation of LIWC2015 (Linguistic Inquiry and Word Count)</a>
program for computerised text analysis.

### Non-technical resources for teachers and researchers

I write articles about technology and education, such as <a
href="https://educational-innovation.sydney.edu.au/teaching@sydney/what-teachers-and-students-should-know-about-ai-in-2023/"
target="_blank">some important concepts about current AI technology like
ChatGPT</a>.

I also like to find and test interesting things that can be embedded and
shown in a webpage for teaching and learning, e.g., online 3D models
viewers, useful HTML & CSS effects, and online code editors.

These ideas and resources do not require any technical knowledge or
coding skills (e.g., just copy-and-paste the given HTML code to embed
and show the objects in a website or LMS).
<a href="https://sites.google.com/view/cocolaberica"
target="_blank">Here is my playground</a> for quick testing and
demonstration.

## What else?

This is a GitHub Flavoured Markdown converted from an R Markdown, which
can embed R code chunks (blocks of runnable code) within the document.
Just a simple code testing:

``` r
x <- "Let's break  this sample text into words   so that the text can be analysed"
strsplit(x, split=" +") # split at whitespace
```

    ## [[1]]
    ##  [1] "Let's"    "break"    "this"     "sample"   "text"     "into"    
    ##  [7] "words"    "so"       "that"     "the"      "text"     "can"     
    ## [13] "be"       "analysed"

``` r
words <- unlist(strsplit(x, split=" +")) # can use unlist() to convert the resulting list to a vector for further processing
print(words)
```

    ##  [1] "Let's"    "break"    "this"     "sample"   "text"     "into"    
    ##  [7] "words"    "so"       "that"     "the"      "text"     "can"     
    ## [13] "be"       "analysed"

Using Markdown makes it easy to show the code chunks and their output.

I knit my R Markdown with `output: github_document` in the YAML header
and then push this to
<a href="https://github.com/CoCoLabErica/cocolaberica.github.io"
target="_blank">my github.io public repository</a> - free and easy.
Visit
<a href="https://pages.github.com/" target="_blank">GitHub Pages</a> to
learn how to host a webpage or blog on GitHub.

------------------------------------------------------------------------

This page is created from an R Markdown written by
[@CoCoLabErica](https://www.youtube.com/@CoCoLabErica/about).
