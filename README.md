# cs4all
Computer Science and Engineering is for all to learn, explore and enable interesting innovations.   

We explore and share pointers on how to get started quickly and continue a self-paced journey.   

Irrespective of the background, feel free to explore a course [CS50](https://cs50.harvard.edu/) by Prof David Malan (.../2021/2022).   
Prof David is awesome to introduce concepts, engage the students and the energy level is that you would love and remember. The best things in the world are free! Notice how he uses two laptops, two displays with a switcher and bit-bulbs are fun.   

Whether you are a sophomore or a senior undergrad or a fresh student into the college for a UG/PG degree, without any bias or hesitation, you can take this lovely course [CS50's Understanding Technology](https://cs50.harvard.edu/technology/2017/).    

----

You can teach CS for yourself, literally. Explore [teachyourselfcs.com](https://teachyourselfcs.com)

[OSSU](https://github.com/ossu/computer-science) shows a path to self-taught and self-paced education in Computer Science. There is a curated curriculum, fundamental concepts in Core CS, and a platform for discussion with other students. 

A [Scripting Course](https://github.com/learnbyexample/scripting_course#ebooks) for primer on Linux, Scripting, Vim, Perl, etc. 

Some [Free Programming Books](https://github.com/EbookFoundation/free-programming-books) available online for reference. 

----

Some Core CS books:  
[Algorithms by Jeff Erickson](http://jeffe.cs.illinois.edu/teaching/algorithms/) 

[Computer Architecture - A Quantitative Approach, 5e by Hennessy and Patterson](http://acs.pub.ro/~cpop/SMPA/Computer%20Architecture%20A%20Quantitative%20Approach%20(5th%20edition).pdf)

[System Programming wiki-book by Angrave](https://github.com/angrave/SystemProgramming/wiki)

[Operating Systems - Three Easy Pieces by Remzi](http://pages.cs.wisc.edu/~remzi/OSTEP/) 

[Open Data Structures](https://opendatastructures.org/) 

----

Some cool readings:  

[High Performance Browser Networking](https://hpbn.co) by Ilya Grigorik 

[The Internet Myth](https://unglue.it/work/442013/)

[Tomorrow's Professor](https://tomprof.stanford.edu/) - an eNewsletter, 100 times a year 

----

Nice visualizations:  

MIT's [Scratch project](https://scratch.mit.edu/) to learn or teach basics of programming using drag and drop widgets 

[Submarine Cable Map](https://www.submarinecablemap.com) to visualize Fibre cables connecting the world through internet 

[Julia's Drawings](https://drawings.jvns.ca/) - a comic take on Computer Science related topics  

----

Writing Tools to create Musical Docs  

LaTeX: [tutorial](https://www.latex-tutorial.com/tutorials/)  
[Overleaf](overleaf.com) - an online LaTeX editor  
[Latexsheet](http://wch.github.io/latexsheet/latexsheet-a4.pdf)  

**Note on Bibliography**  
Make sure .tex (main latex source), .bib (bibliography entries), and .bst (bibliography style) files are in the same directory. The following sequence can be handy. 

```
\documentclass{article}

% premble for packages
\usepackage{amsmath}      % for dealing with mathematics
\usepackage{amsthm}       % for dealing with theorem environments
\usepackage{hyperref}     % for linking the cross references
\usepackage{graphics}     % for dealing with figures
\usepackage{algorithmic}  % for describing algorithms
\usepackage{subfig}       % for getting the subfigures e.g., "Figure 1a and 1b" etc.
\usepackage{url}           % for better support in handling and breaking URLs
\usepackage{comment}       % for commented text in .tex file

% add bibliographystyle required for example somestyle.bst
\bibliographystyle{somestyle}

\title

\begin{abstract}
Abstract goes here. No citations, table or figure references in abstract. 
\end{abstract}

\begin{document}

\maketitle

\section{......}
......
\subsection{......}

% add bibliography .bib file name without file extension .bib
\bibliography{mybib}

\end{document}
```
