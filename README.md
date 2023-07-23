\documentclass[letterpaper,11pt]{article}

 

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}

 

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

 

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

 

\urlstyle{same}

 

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

 

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

 

% Ensure that generated PDF is machine readable/ATS parsable
\pdfgentounicode=1

 

% Custom commands
\newcommand{\resumeItem}[1]{\item\small{#1\vspace{-2pt}}}
\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small#4} \\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small#2} \\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}
\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

\begin{document}
\begin{center}
    \textbf{\Huge \scshape SHREYA GUPTA} \\ \vspace{10 pt}
    \small{\raisebox{-0.2\height}{\faPhone} \underline{Mobile: 7251083279} $|$ \raisebox{-0.2\height}{\faEnvelope} \underline{Email: shreya00117@gmail.com} $|$ \raisebox{-0.2\height}{\faLinkedin} \underline{\href{https://bit.ly/3MRRsbv}{LinkedIn}} $|$ \raisebox{-0.2\height}{\faGithub} \underline{\href{https://bit.ly/3CUpYgH}{GitHub}}}
\end{center}

\section{\textbf{EDUCATION}}
\resumeSubHeadingListStart
\resumeSubheading
{\textbf{Pranveer Singh Institute Of Technology, Kanpur, U.P.}}{\textbf{August 2019 -- June 2023}}
{{Bachelor of Technology in Information Technology}}{{7.6 CGPA}}
\resumeSubheading
{\textbf{Harrow Public School, Bareilly, U.P.}}{\textbf{April 2018 -- May 2019}}
{{PCM}}{\textbf{}}
\resumeSubHeadingListEnd

\section{\textbf{WORK EXPERIENCE}}
\resumeSubHeadingListStart
\resumeSubheading
{\textbf{Ericsson India Global Services}}{\textbf{January 2023 -- July 2023}}
{{Intern}}{Noida, India}
\resumeItemListStart \vspace{5 pt}
\resumeItem{\textbf{Skills}: HTML, CSS, JavaScript, Java, JIRA, MySQL, Automation Testing, Groovy}
\resumeItem{Developed automation workflows using Java, that help to generate updated reports and send them on mails. }
\resumeItem{Developed health-check of automation to check the current status for a particular network.}
\resumeItem{Worked on ENABLE tool, an automation tool to create workflows that help perform parsing in the data.}
\resumeItemListEnd

\vspace{5 pt}
\resumeSubheading
{\textbf{GirlScript Summer Of Code 2023}}{\textbf{June 2023 - Ongoing}}
{{Open Source Contributor}}{Remote}
\resumeItemListStart \vspace{5 pt}
\resumeItem{\textbf{Tech Stack Used}: Java, HTML, CSS, JavaScript, Git, GitHub, Machine Learning}
\resumeItem{Contributing to open source projects under the mentorship of experienced mentors.}
\resumeItem{\textbf{Badge}:  GirlScript Summer of Code 2023 (\href{https://certificate.givemycertificate.com/c/8aa16808-3f7e-4862-8049-f78bde93b850}{Certificate})}
\resumeItemListEnd

\vspace{5 pt}
\resumeSubheading 
{\textbf{Social Summer of Code 2023}}{\textbf{May 2023 - Ongoing}}
{{Open Source Contributor}}{Remote}
\resumeItemListStart  \vspace{5 pt}
\resumeItem{\textbf{Tech Stack Used}: Java, HTML, CSS, JavaScript, Machine Learning, Git, GitHub, Artificial Intelligence}
\resumeItem{Contributing to open source projects under the mentorship of experienced mentors.}
\resumeItem{\textbf{Badge}: Social Summer of Code 2023 (\href{https://drive.google.com/file/d/1y4p3lsL23SCQhF957huoIHbGitRwlHSB/view?usp=share_link}{Certificate})}
\resumeItemListEnd

 

\resumeSubHeadingListEnd

 
\vspace{5 pt}

\section{\textbf{PROJECTS}}
\resumeSubHeadingListStart

 

\resumeProjectHeading
{\textbf{Detection of diseases in Chest X-Ray Images}}{Sept. 2022 - Jan. 2023}
\resumeItemListStart
\resumeItem{\textbf{Tech Stack Used}: DenseNet, TensorFlow, MobileNet, Vgg-16}
\resumeItem{Implemented various CNN models for the detection of Pneumonia in X-Ray image dataset.}
\resumeItem{Aimed to reach the highest accuracy on the given dataset by implementing pre-trained models.}
\resumeItem{Enhanced the accuracy of the dataset from 72\% to 92\% using Gaussian filter and image equalization.}
\resumeItemListEnd

 

\resumeProjectHeading
{\textbf{Travel App}}{Sept. 2020 - Jan. 2021}
\resumeItemListStart
\resumeItem{\textbf{Tech Stack Used}: Java, HTML, CSS, JavaScript, Node.js}
\resumeItem{Developed the feature to select a tourist destination based on the current location.}
\resumeItem{Added a module to filter the choice as per the budget.}
\resumeItem{Used Node.js to develop the backend of the application as well as add a database for storing user's data.}
\resumeItemListEnd

 

\resumeProjectHeading
{\textbf{A College Website}}{March 2020 -- June 2020}
\resumeItemListStart
\resumeItem{\textbf{Tech Stack Used}: HTML5, CSS3, JavaScript}
\resumeItem{Implemented 5 modules in the website: Home, Course, Download, Contact, Login}
\resumeItem{Developed a Download module to download PDFs of books.}
\resumeItemListEnd

\resumeSubHeadingListEnd

\section{\textbf{SKILLS}}
\begin{itemize}[leftmargin=0.15in, label={}]
    \item \textbf{Languages}: Java, C, Python, C++, MySQL, JavaScript, HTML, CSS, Groovy
    \item \textbf{Skills}: Node.js, Deep Learning, Data Structures, Object Oriented Programming, Machine learning, Git, GitHub
    \item \textbf{Developer Tools}: Git, VS Code, Eclipse, Android Studio
    \item \textbf{Soft Skills}: Public Speaking, Written communication, Analytical Skills
\end{itemize}

 

\end{document}
