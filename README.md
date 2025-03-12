[Up\documentclass{scrreprt}
\usepackage{listings}
\usepackage{underscore}
\usepackage{graphicx}
\usepackage[bookmarks=true]{hyperref}
\usepackage[utf8]{inputenc}
\usepackage[english]{babel}
\hypersetup{
    bookmarks=false,    % show bookmarks bar?
    pdftitle={Software Requirement Specification},    % title
    pdfauthor={Jean-Philippe Eisenbarth},                     % author
    pdfsubject={TeX and LaTeX},                        % subject of the document
    pdfkeywords={TeX, LaTeX, graphics, images}, % list of keywords
    colorlinks=true,       % false: boxed links; true: colored links
    linkcolor=blue,       % color of internal links
    citecolor=black,       % color of links to bibliography
    filecolor=black,        % color of file links
    urlcolor=purple,        % color of external links
    linktoc=page            % only page is linked
}%
\def\myversion{1.0 }
\date{}
%\title{%

%}
\usepackage{hyperref}
\begin{document}

\begin{flushright}
    \rule{16cm}{5pt}\vskip1cm
    \begin{bfseries}
        \Huge{SOFTWARE REQUIREMENTS\\ SPECIFICATION}\\
        \vspace{1.5cm}
        for\\
        \vspace{1.5cm}
        Academic Tracking System (ATS)\\
        \vspace{1.5cm}
        \LARGE{Version \myversion}\\
        \vspace{1.5cm}
        Prepared by : 1.[name] ([ID])\\
        2. [name] ([ID])\\
        \vspace{1.5cm}
        Instructor: Sayed Erfan Arefin
        \\Course: CPS 420\\
        \vspace{1.5cm}
        \today\\
    \end{bfseries}
\end{flushright}

\tableofcontents

\chapter{Introduction}

\section{Purpose}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

\section{Product Scope}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

\section{References}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum." You can have a look at Figure \ref{fig:IICT WEBSITE}. you can also have a look at the Section \ref{sec:IICTxx WEBSITE}.


\begin{figure}
    \centering
    \includegraphics[width=10cm]{1.JPG}
    \caption{Entire work-flow}
    \label{fig:IICT WEBSITE}
\end{figure}



\chapter{Overall Description}

\section{Product Perspective}
\label{sec:IICTxx WEBSITE}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."




\section{Product Functions}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

\subsection{Product Functions}
"Lorem ipsum dolor sit amet, consectetur adipi"


\subsubsection{P12eroduct Functions}
"Lorem ipsum dolor sit amet, consectetur adipi"


\subsection{Product Functions}
"Lorem ipsum dolor sit amet, consectetur adipi"

\begin{figure}[h!]
    \centering
    \includegraphics[width=15cm]{3.JPG}
    \caption{Data Flow Diagram}
    \label{fig:Data Flow Diagram}
\end{figure}
Before using the main function of the software result process, users have to be registered. 
\newline
All users have - login\_parameter, user\_name, first\_name, last\_name, user\_id, role, post, email, phone\_number, present\_address, parmanent\_address, blood\_group, password\_hash and timeStamp.
\newline
Students have some extra informations after complete his/her registration , such as - user\_id(foreign key), registration\_id, year, semester, course\_array and drop\_course\_array. These are the information that contains his/her result of his taken courses and program.
\newline
Each programs has some data - program\_name, program\_id, course\_id, nunmber\_of\_semester, total\_credit and course\_length. There will be onew or many course\_id in each programs.
\newline
Courses table contains - course\_name, course\_id, course\_code, credit, semester and teacher\_id.
\newline
Every course has its own Credit Values. Those have been 2 types - lab, theory.
\newline
Result is the main feature of all. It contains the values of all the exams of a particular student. It has data field - student\_id, course\_id, term\_test, attendance, marks(A), marks(B), teacher\_id(A), teacher\_id(B), entry\_date(A), entry\_date(B), publish\_date, semester	and result\_state.

\section{User Classes and Characteristics}
The website will be operate in any Operating Environment - Mac, Windows, Linux etc. 

\section{Constraints}
Student activities have 3 steps -
\begin{itemize}
    \item From Fill Up Process
    \item Courses Payment
    \item Student Profile
\end{itemize}
Top selected Student first fill his/her form, bank payment. After verification, student pays for their selected courses. Then he can enter his profile. 
\newline


\section{Assumptions}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

\chapter{Requirements}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."


\chapter{References}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

\chapter{Index}
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

\end{document}loading srs.tex…]()
