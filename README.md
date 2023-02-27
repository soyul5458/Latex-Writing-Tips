# Latex-Writing-Tips


1. Latex labels: a prefix should be used to avoid duplicates of labels in different chapters/sections in the thesis/paper.
  * Equations: e.g., \label{intro-eq1}, \label{review-eq1}.  
  * Figures: e.g., \label{fig:intro-fig1}, \label{fig:review-StabilityRegions}.  
  * Sections: e.g., \label{sec:intro-Conclusion}, \label{fig:review-Notations}.  
  * Tables: e.g., \label{sec:intro-FeedbackGains}, \label{fig:review-ListsOfSymbols}.  

2. New Commands: Create new commands for Corollary/Lemma/Proposition/Remark/Theorem/
  * Here are the command placed before "\begin{document}":  
  * \newtheorem{theorem}{Theorem}
    \newtheorem{lemma}{Lemma}
    \newtheorem{proposition}{Proposition}
    \newtheorem{corollary}{Corollary}
    \newtheorem{remark}{Remark}  
  * To start a new remark, for example, \begin{remark} remark content \end{remark}  

3. New Commands: Create short forms for long equations
  * For example, \newcommand{\vectorZZ}{\left[\begin{array}{c} \mathbf{z} \\ \mathbf{z}_s\end{array}\right]}.  
  * WHen using "\vectorZZ" in the paper, it will display "\left[\begin{array}{c} \mathbf{z} \\ \mathbf{z}_s\end{array}\right].  

## Reference labels:
Suggested format - Last name of the first author + year of publication + the first letters of the first three words of the title.
  * For example, the label for the following paper is "Lam2012son".  
  * H.K. Lam, 'Stabilization of nonlinear systems using sampled-Data output-feedback fuzzy controller based on polynomial-fuzzy-model-based control approach' IEEE Transactions on Systems, Man, and Cybernetics, Part B, vol 42, no. 1, pp. 258 - 267, 2012.  

## Title of references:
Put those letters or words in the article title (bibtex) to be displayed in capitals in parentheses
  * For example, the word "LMI" in the article title should be displayed in capitals, use {LMI}.  
  * For example, the word "Lyapunov" in the article title should be dislayed in capitals, use {L}yapunov.  
1. Pay attention to the punctuation marks in sentences involving equations.
  * For example, "The characteristic is determined by $$f(x(t)) = a x(t) + b$$." where a full stop is required at the end.  
2. When an expression such as $j = 1, 2, \ldots, c$.  You should use $j$ = 1, 2, $\ldots$, $c$, otherwise the font face of the "comma" in the first expression will be different from the text font face.  
3. When overhead symbols are used, for example, $\hat{\mathbf{x}}$ should be used instead of $\mathbf{\hat{x}}$, otherwise the "hat" will be in bold face as well.  

## Reference Format:
See [IEEE Referencing Guide](https://nms.kcl.ac.uk/hk.lam/HKLam/images/Files/IEEE%20Referencing%20Guide.pdf)

## General writing tips

1. The Introduction section should consist of the following:  
  a. Problem statement: it defines the problem to be handled and why the problem is important with the support of existing applications if any.    
  b. Literature review: it discusses what work and methods are available to deal with the problem.  Do not just simply saying “Method 1 was found in [1]. Method 2 was found in [2]” etc.  Give more details by briefly telling the how they do it, their pros and cons, limitations, etc, which will be some good evidence to support the motivation of your work and proposed approach.  It is good to categorise the existing methods to give an overall picture.  For example, you may say “The existing approaches can be categorised into three main categories.  Category 1 is to deal with the problem using . . . [references] . . . ”.    
  c. Your approach and motivations: In the literature review, you have reviewed the limitations of the existing methods. It is the motivations of proposing your own for improvement and deal with the problem.  Here, you briefly tell your method in words and without equations.  Tell what limitations of the existing works and difficulties of the problem your method can handle.    
  d. Paper organisation:  it tells the structure of the paper and briefly presents what will appear in each sections. This would be the last paragraph of the introduction section.    

2. Be consistent of using terms, format (citations, equations, figures, tables, references, etc), English (American  or Bristish).  For example, regarding terms, when you use “fuzzy logic system” in the paper, just use “fuzzy logic system” throughout the paper but not sometimes “ fuzzy system”, “fuzzy inference system”, etc, although they refer to the same thing.
3. Define the short forms/abbreviations for terms at their first time of appearance.  After that point, only use the abbreviation only.  For example, define “fuzzy-model-based” as FMB.  From that point on, only use “FMB”.
4. Define all variables appeared in the paper (used in equations, figures, tables, etc.).  Variables should stick to standard format, say, scalar variables in italic, vector/matrix in bold. They must be in the same face throughout the paper even in the figures and tables.
5. Define the dimensions for variables, say in latex format , $\mathbf{X} \in \Re^{n \times n}$, 
6. Do not use contraction, e.g., “don’t”, “can’t”, use “do not”, “cannot”.
7. Each caption for figure/table must be unique.
8. Figures/tables are used in the paper to help explain ideas/results.  Do not just let them sit in the paper and ask the readers to interpret them.  For example, if you just say “The concept is illustrated in Fig. X” and nothing to follow, which is a bad example.  You ask the reader to understand by himself/herself.  After saying “The concept is illustrated in Fig. X”, you should describe the figure (what is in the figure? What do you want to tell through the figure? Define all variables in the figure, etc).  The same applies to Tables.  You should describe what is in the table and how to read the table.  Then, present the results, discussions and observations.
9. Figures plotting time responses for example must have labels for all axises.
10. Use recently published journal papers as references for literature review except for those important papers or references for background theory.
11. All information for a reference should be provided, i.e., auhtors’ names, article title, conference/journal title, volume number, issue number, page numbers, month of publication, year of publication.
  a. Book title should be in title sentence. The first letter of every word should be in capital except adverb. For example, “Stability Analysis of Fuzzy Control Systems using Lyapunov Approach”.    
  b. Paper title for Conferences/journals should be in sentence case. Only the first letter of the first word should be in capital, except nouns in the middle of the title. For example, “Stability analysis of fuzzy control systems using Lyapunov approach”.  
  c. The first letter of a noun in the title should be in capital. For example, “Lyapunov” in the above example; LMI, etc. In the latex file, use “{L}yapunov” and {LMI} in the bibtex file.  
12. All references in the reference list must be cited in the paper.

[reference](https://nms.kcl.ac.uk/hk.lam/HKLam/index.php/latex-writing-tips)


