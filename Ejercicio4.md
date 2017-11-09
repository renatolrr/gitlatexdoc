#Cómo hacer un curriculum con LaTeX
  
##Plantilla  
  
```
documentclass[twoside,a4paper,openright,10pt]{report}
\usepackage[USenglish]{babel}
\usepackage[latin1]{inputenc}
\usepackage{colortbl}
\usepackage{enumitem}

\setlength{\textwidth}{190mm}
\setlength{\textheight}{270mm}
\setlength{\oddsidemargin}{-15mm}
\setlength{\evensidemargin}{-15mm}
\setlength{\topmargin}{-30mm}

\pagestyle{empty}

\begin{document}

\begin{table}[ht]
\centering
\begin{tabular}{p{40mm} p{140mm}}

\multicolumn{2}{l}{\textbf{nombre APELLIDOS}, Spanish Nationality (Driving license)}\\
\multicolumn{2}{l}{10 Brantim road, 67820, New York, USA}\\
\multicolumn{2}{l}{+01 555 555 555}\\
\multicolumn{2}{l}{\texttt{xxx@university.com}}\\ \\
\multicolumn{2}{c}{\textbf{\textit{\large Industrial computing engineer. I want to develop software for industrial applications.}}}\\
\multicolumn{2}{c}{\textbf{\textit{\large My aim is to be involved in all stages of the workflow from specification to coding.}}}\\ \\

\multicolumn{2}{c}{\cellcolor{black} \textcolor{white}{Education}}\\ \\

\textbf{1998-2004} & Graduate School of Software Engineering, XXX University, USA.\\
 & Master degree in \textbf{Software Engineering}: specialized in \textbf{Embedded Systems}.\\
\\

\multicolumn{2}{c}{\cellcolor{black} \textcolor{white}{Work Experience}}\\ \\
\textbf{Nov. 2010-Present} & Engineer at \textbf{XX} (Software Company), New York, \textbf{USA}. Development of advanced control software:\\
& \vspace{-2mm} \begin{itemize}[noitemsep,nolistsep]
\item Implementation new features per request from control group.
\item Testing on bench.
\item Evaluation of upgrade to the new software version: in progress.
\vspace{-4mm}
\end{itemize}\\

\textbf{Nov. 2009-Oct. 2010} & Engineer at \textbf{XX} (Software Company), New York, \textbf{USA}. Development of advanced control software:\\
& \vspace{-2mm} \begin{itemize}[noitemsep,nolistsep]
\item Implementation new features per request from control group.
\item Testing on bench.
\item Evaluation of upgrade to the new software version: in progress.
\vspace{-4mm}
\end{itemize}\\

\textbf{Oct. 2004-Oct. 2009} & Engineer at \textbf{ZZZ} New York, \textbf{USA}.\\

\\
\multicolumn{2}{c}{\cellcolor{black} \textcolor{white}{University Experience}}\\ \\

\textbf{Jun. 2006-Jun. 2007} & Project on ZZZZ, XXX University.\\
\textbf{Jan. 2006-Jun. 2006} & Project on ZZZZ, XXX University.\\
\textbf{Sep. 2005-Jan. 2006} & Project on ZZZZ, XXX University.\\

\\
\multicolumn{2}{c}{\cellcolor{black} \textcolor{white}{Skills}}\\ \\

\textbf{Programming} & Languages: C, C++, C\#, Java, Python.\\
& Software: Linux, Eclipse.\\

\textbf{Programming} & Languages: C, C++, C\#, Java, Python.\\
& Software: Linux, Eclipse.\\

\textbf{Programming} & Languages: C, C++, C\#, Java, Python.\\
& Software: Linux, Eclipse.\\

\textbf{Digital Electronics} & Methodology for designing electronic systems:
\begin{itemize}[noitemsep,nolistsep]
\item Circuit design: ZZZ.
\item System design: YYY.
\item Implementation on XXX.
\end{itemize}\\
& \vspace{-7mm} Methodology for designing electronic systems:
\begin{itemize}[noitemsep,nolistsep]
\item Circuit design: ZZZ.
\item System design: YYY.
\item Implementation on XXX.
\vspace{-4mm}
\end{itemize}\\
& Methodology for designing electronic systems:
\begin{itemize}[noitemsep,nolistsep]
\item Circuit design: ZZZ.
\item System design: YYY.
\item Implementation on XXX.
\vspace{-4mm}
\end{itemize}\\

\textbf{Languages} & \textbf{Spanish:} mother tongue.\\
& \textbf{English:} fluent.\\
& \textbf{French:} fluent.\\
& Worked in an international environment.

\\
\multicolumn{2}{c}{\cellcolor{black} \textcolor{white}{Interests and Activities}}\\ \\

\textbf{Sports} & Curling, Croquet, Extreme Ironing, Hot Dog Eating.\\

\end{tabular}
\end{table}

\end{document}
```
  
Fuente: http://minisconlatex.blogspot.fr  
