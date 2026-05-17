\documentclass[11pt]{article}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[margin=1in]{geometry}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{titlesec}
\usepackage{enumitem}
\usepackage{fontawesome5}
\usepackage{parskip}
\usepackage{ragged2e}

% Colors
\definecolor{primary}{RGB}{41, 72, 126}
\definecolor{accent}{RGB}{102, 153, 204}
\definecolor{darkgray}{RGB}{80, 80, 80}

% Hyperref
\hypersetup{
    colorlinks=true,
    linkcolor=primary,
    urlcolor=accent,
    citecolor=primary,
    pdftitle={Curriculum Vitae - Jamal Agbanwa},
    pdfauthor={Jamal Agbanwa}
}

% Section formatting
\titleformat{\section}
    {\normalfont\Large\bfseries\color{primary}}
    {}{0em}{}[\titlerule]
\titlespacing*{\section}{0pt}{12pt}{6pt}

\titleformat{\subsection}
    {\normalfont\large\bfseries\color{darkgray}}
    {}{0em}{}

\setlist[itemize]{leftmargin=*, itemsep=4pt}
\setlist[enumerate]{leftmargin=*, itemsep=4pt}

\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\fancyfoot[C]{\color{darkgray}\small \thepage}

\begin{document}

% Header
\begin{center}
    \color{primary}
    {\Huge \textbf{Curriculum Vitae}} \\
    \vspace{0.3cm}
    {\LARGE \textbf{Jamal Agbanwa}} \\
    \vspace{0.6cm}
    \begin{tabular}{c}
        \faIcon{envelope} \href{mailto:agbanwajamal03@gmail.com}{agbanwajamal03@gmail.com} \\
        \faIcon{github} \href{https://github.com/JAgbanwa}{github.com/JAgbanwa} \\
        \faIcon{wordpress} \href{https://jamalagbanwa.wordpress.com}{jamalagbanwa.wordpress.com}
    \end{tabular}
\end{center}

\vspace{0.8cm}

% Profile
\section*{\faIcon{user} Profile}
\justifying
Independent mathematician specializing in Diophantine equations and explicit parametric constructions, with a focus on the sums of three cubes problem and generalizations of taxicab numbers.

\vspace{0.6cm}

% Education
\section*{\faIcon{graduation-cap} Education}
\textbf{Postgraduate Taaljaar Nederlands voor Anderstaligen} \hfill 2021--2022 \\
Linguapolis, Antwerp

\vspace{0.8cm}

% Research
\section*{\faIcon{flask} Research}

\subsection*{Journal Submissions}
\begin{itemize}
    \item \textbf{A Parameterization of the $3 \times 3$ Magic Square of Squares Problem} \\
    Submitted to \textit{Notes on Number Theory and Discrete Mathematics}, April 2026.
    
    \item \textbf{Parametric Constructions for Taxicab Numbers via Pell Equations} \\
    Submitted to \textit{Journal of Integer Sequences}, May 2026.
\end{itemize}

\subsection*{Preprints}
\begin{itemize}
    \item \textbf{A Closed-Form Symbolic Generator for $A^n + B^n = C^n + D^n$} \\
    arXiv:2506.19173, June 2025.
    
    \item \textbf{A Parametric Framework for the Sum of Three Cubes Problem} \\
    In preparation (target submission 2026).
\end{itemize}

\subsection*{Ongoing Research}
\begin{itemize}
    \item Explicit parametric solutions to the sums of three cubes problem, focusing on stubborn cases ($k=192, 375, 600$, and others) using turning-point and Cardano-style methods.
    \item Generalizations of taxicab numbers connected to Pell-type equations.
    \item Advances on the $3 \times 3$ magic square of squares problem.
\end{itemize}

\vspace{0.6cm}

% Achievements
\section*{\faIcon{trophy} Achievements}
\begin{itemize}
    \item Four sequences contributed to the On-Line Encyclopedia of Integer Sequences (OEIS), including new families related to taxicab numbers and Pell equations (A384106, A389865, A393694, A395378).
    \item Direct feedback on research from Professor Terence Tao (UCLA), 2025.
    \item Positive engagement from researchers at KU Leuven, Princeton, and University of Leicester.
\end{itemize}

\vspace{0.6cm}

% Skills
\section*{\faIcon{cogs} Skills}
\begin{itemize}
    \item Independent research in number theory and Diophantine equations
    \item Development of parametric and algebraic constructions
    \item Computational tools: SageMath, Wolfram Alpha, Desmos
    \item Professional mathematical writing and \LaTeX{} typesetting
    \item Self-directed study of advanced topics
\end{itemize}

\vspace{0.6cm}

% Languages
\section*{\faIcon{language} Languages}
\begin{itemize}
    \item English — Fluent
    \item Dutch — Professional working proficiency
\end{itemize}

\vspace{\fill}

\begin{center}
\color{darkgray}
\small
References and additional materials available upon request \\
Last updated: \today
\end{center}

\end{document}
