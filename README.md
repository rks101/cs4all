# cs4all
Computer Science and Engineering is for all to learn, explore and enable interesting innovations - the most important one is **problem solving**.   

We explore and share pointers on how to get started quickly and continue a self-paced journey.   

Irrespective of the background, feel free to explore a course [CS50](https://cs50.harvard.edu/) by Prof David Malan (.../2021/2022).   
Prof David is awesome to introduce concepts, engage the students and the energy level is that you would love and remember. The best things in the world are free! Notice how he uses two laptops, two displays with a switcher and bit-bulbs are fun.   

Whether you are a sophomore or a senior undergrad or a fresh student into the college for a UG/PG degree, without any bias or hesitation, you can take this lovely course [CS50's Understanding Technology](https://cs50.harvard.edu/technology/2017/).    

[Software Construction](https://web.mit.edu/6.005/www/fa15/) course at MIT Fall 2015.   

Note:- Your health is very important, espcially eyes, neck, back, fingers and wrists if type a lot. If you are using a computer desktop, laptop, tablet or phone for more than 3 hours or more every day, repetitive strain injury may affect your fingers, wrists, neck, back, and eyes. Merely a bad posture, if ignored for long, can cause fatigue and pain later. Please take a break often, do exercises, stretches and this page from [Princeton UHS](https://uhs.princeton.edu/health-resources/ergonomics-computer-use) can help in simple reflexes, especially watch videos under section **Desk Stretching Exercises**.      

----

You can teach CS for yourself, literally. Explore [teachyourselfcs.com](https://teachyourselfcs.com)

[OSSU](https://github.com/ossu/computer-science) shows a path to self-taught and self-paced education in Computer Science. There is a curated curriculum, fundamental concepts in Core CS, and a platform for discussion with other students. 

A [Scripting Course](https://github.com/learnbyexample/scripting_course#ebooks) for primer on Linux, Scripting, Vim, Perl, etc. 

Some [Free Programming Books](https://github.com/EbookFoundation/free-programming-books) available online for reference.   

After the first CS or programming course, you can refer [CS Video Courses](https://github.com/Developer-Y/cs-video-courses).   

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

[CO_2 Emissions](https://ourworldindata.org/grapher/co-emissions-per-capita?tab=chart) See chart, map, tabular data and other settings you can play with   

[Julia's Drawings](https://drawings.jvns.ca/) - a comic take (zines) on Computer Science related topics   

[Flavio's bootcamp](https://bootcamp.dev/) for serious to-be-wanna full-stack web developers.    

----

[As We May Think](https://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/) by Vannevar Bush (1945) to foresee the future world and man-made machines.    
[Paul Baran, 1964](https://www.rand.org/pubs/research_memoranda/RM3097.html) a series of memoranda on distributed communications.    

----

My [eglinux](https://github.com/rks101/eglinux) repo for a little practical Linux hands-on.    
[egnet](https://github.com/rks101/egnet) repo for a little practical networking hands-on.    
[CImpl](https://github.com/rks101/Cimpl) repo for a continuous stream of examples and questions.    
[webapps](https://github.com/rks101/webapps) repo for online playgrounds and helpful pointers.    

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
