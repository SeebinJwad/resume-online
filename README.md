
\documentclass[11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{hyphenat}
\input{glyphtounicode}

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

\renewcommand{\familydefault}{\sfdefault}
% Ensure that generate PDF is machine readable/ATS parse-able
\pdfgentounicode=1

%-------------------------
% Custom commands

\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}


\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      {\small#3} & {\small #4} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeSubSubheading}[2]{
    \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      {\small#1} & {\small #2} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeEducationHeading}[6]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      {\small#3} & {\small #4} \\
      {\small#5} & {\small #6} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeProjectHeading}[2]{
    \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeOrganizationHeading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & {\small #2} \\
      {\small#3}
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%---------- HEADING ----------

\begin{center}
    \textbf{\Huge \scshape Jawad Kazi} \\ \vspace{3pt}
    \small
    \hspace{.5pt} {(346) 779-4692}
    •
    \href{mailto:jawad.kazi@utexas.edu}{jawad.kazi@utexas.edu}
    •
    \href{SeebinJwad.github.io}{jawadkazi.ml}
    •
    {Austin, Texas}
\end{center}

%----------- EDUCATION -----------

\section{EDUCATION}
  \vspace{3pt}
  \resumeSubHeadingListStart
    
    \resumeEducationHeading
      {THE UNIVERSITY OF TEXAS AT AUSTIN}
      {Austin, Texas}
      {B.S. Economics;   \textbf{GPA: 3.5/4.0}}{Expected May 2024}
      {Certificate in Scientific Computing and Data Science;   \textbf{GPA: 4.0/4.0}}
        
        \resumeItemListStart
             \resumeItem{\textbf{Relevant coursework:} Linear Algebra, Probability Theory, Foundation of Data Analysis, Economics Statistics, Elements of Programming, Engineering Design, Computer Fluency, Calculus I-III, Micro/Macro Economics}
        \resumeItemListEnd
    
  \resumeSubHeadingListEnd



%----------- EXPERIENCE -----------

\section{EXPERIENCE}
  \vspace{3pt}
  \resumeSubHeadingListStart
  
    \resumeSubheading
      {Head and Neck Cancer Research Lab, Baylor College of Medicine}{Houston, Texas}
      {Student Bioinformatic Research Assistant}{Jun 2019 \textbf{--} Sep 2022}
        \resumeItemListStart
            \resumeItem{Designed a big data algorithm and full-stack web-portal, implemented it for clinicians to batch screen patients for eligibility in NOTCH1 cancer drug trials; used Django, HTML/CSS for website, and NumPy, Pandas for algorithm}
            \resumeItem{Built next-generation sequencing analysis pipeline on high performance computer cluster using Linux, C++, and Docker}
            \resumeItem{Proposed a research project in determining cancer type given gene data using novel machine learning algorithms}
            \resumeItem{Co-authored two publications in high-impact journals -  receiving \$10,000 stipend}
        \resumeItemListEnd
    
    \resumeSubheading
      {UpWork Freelance Platform}{Remote}
      {Certified Data Science Freelancer}{Jun 2021 \textbf{--} Aug 2022 (on break)}
        \resumeItemListStart
            \resumeItem{Automated the mining and analysis of pharmaceutical ad content on Facebook Ads and WebMD, over 10,000 pages scraped using Python Selenium in Amazon EC2 with periodic job execution}
            \resumeItem{Established long-term relations with multiple companies such as PranifyRx and Genesis AEC with up to \$2,600 contracts}
        \resumeItemListEnd
    
  \resumeSubHeadingListEnd

%----------- Projects -----------

\section{PROJECTS}
  \vspace{3pt}
  \resumeSubHeadingListStart
  
    \resumeSubheading
      {UT Austin Creation Competition}{Austin, Texas}
      {Solo Programmer in Team of 5}{Feb 2022}
        \resumeItemListStart
            \resumeItem{Led a team of mechanical engineers in deconstructing a printer to scan papers in batch and automatically sort the scanned files based on subject using natural language processing - rule based text classification model}
            \resumeItem{Utilized binary transmission with PySerial library and Arduino and won competition, project in Texas Inventionworks}
        \resumeItemListEnd
    
    \resumeSubheading
      {Graph For All Challenge}{Redwood City, California (Remote)}
      {Solo Programmer}{Jan 2022}
        \resumeItemListStart
            \resumeItem{Deployed pipeline scanning United Nations Documents to connect current global issues with historic diplomatic solutions}
            \resumeItem{Adapted GraphQL technology in the cloud with modern Python data analysis techniques}
        \resumeItemListEnd
        
    \resumeSubheading
      {UT HackTX}{Austin, Texas}
      {Programmer in team of 2}{Jan 2022}
        \resumeItemListStart
            \resumeItem{Collaborated on an web app hosted machine learning model that could provide AI therapy}
            \resumeItem{Applied 4 independent Google APIs to convert user speech to text and provide meaningful sympathetic responses}
        \resumeItemListEnd
        
    \resumeSubheading
      {UT Hack for Humanity}{Austin, Texas}
      {Hackathon Competitor}{Jan 2022}
        \resumeItemListStart
            \resumeItem{Established a methodology for scanning tax documents from the IRS to determine underfunded non-profit organizations}
            \resumeItem{Scraped IRS with Selenium and used Pandas and SciPy to formulate regressions to categorize these non-profits}
            
        \resumeItemListEnd
        
    \resumeSubheading
      {HAMUN website}{Houston, Texas}
      {Solo Programmer and web designer - Technology Officer}{Jan 2022}
        \resumeItemListStart
            \resumeItem{Employed Velo Javascript under Wix to revamp website of 24 years for over 5000 student users so they could easily access their respective committee's information, submit documents, and interact with other users}
        \resumeItemListEnd
    
  \resumeSubHeadingListEnd


%----------- Projects -----------

\section{SKILLS AND INTERESTS}
  \vspace{3pt}
  \resumeSubHeadingListStart
  

        \resumeItemListStart
            % \resumeItem{\textbf{Natural Language Processing - } Hugging Face Tokenizers, spaCy, NLTK, Gensim, Apache OpenNLP}
            % \resumeItem{\textbf{Machine Learning Frameworks/Ecosystems - } Tensorflow, PyTorch, Keras, Scikit-learn}
            \resumeItem{\textbf{Data Science - } Pandas, NumPy, Seaborn, MatplotLib, BeautifulSoup, SciPy, Selenium}
            \resumeItem{\textbf{Linux - } Nvim, Tmux, Qsub/Qstat, Linux customization, External SSD Ubuntu}
            \resumeItem{\textbf{Programming Languages - } Python, Java, R, SQL, Javascript, React, HTML/CSS, Markdown, Git}
            \resumeItem{\textbf{CSS Art - } Over 38 PureCSS Artworks on CodePen using HTML/CSS, Pugjs, SASS/SCSS}
            \resumeItem{\textbf{Creative Writing - } Over 100 posts and 1.3 million reads on Quora (Ahmed-Kazi-33) about my favorite TV shows}
        \resumeItemListEnd
    
  \resumeSubHeadingListEnd
  
\end{document}
