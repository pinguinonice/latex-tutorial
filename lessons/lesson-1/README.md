# Lesson 1
[Overview](https://github.com/pinguinonice/latex-tutorial/)  
Lets look at our first (empty) document 
from [Lesson 0](/lessons/lesson-0/) by opening it in TexStudio
	
### Structure of a .tex file:
.tex files contain the main information of our document, like .html in webdesign.

look at the file line by line:  

```
\documentclass[]{article} 
%opening

\title{}
\author{} 


\begin{document}

\maketitle 

\begin{abstract} 

\end{abstract} 

\section{} 

\end{document}
```

A comment, like: `%opening`
always starts with a `%` and will not be interpreted as document content:

```
\documentclass[]{article} %Defining the document class (article)

%opening (a comment)
\title{} % set the title variable 
\author{} % set the author variable 


\begin{document} % the beginning of the document

\maketitle % this creates the title 

\begin{abstract} % Beginning of the abstract

\end{abstract} % end of the abstract

\section{} % new section

\end{document}
```

### Fill in your content


You can fill the template now with your content:


```
\documentclass[]{article} %Defining the document class (article)

%opening (a comment)
\title{How to great the World} % set the title variable 
\author{pinguinonice} % set the author variable 


\begin{document} % the beginning of the document

\maketitle % this creates the title 

\begin{abstract} % Beginning of the abstract
This is a very short description of how to great the world!
\end{abstract} % end of the abstract

\section{English} % new section
Hello World!
\end{document}
```

Press <img src="https://www.wpclipart.com/signs_symbol/arrows/button_arrows/play_buttons/fast_forward_button.png" width="20" height="20" />
to create the document.

the folder with the `.tex` file should contain several new files now:

```
myfirstdocument.aux        myfirstdocument.synctex.gz
myfirstdocument.log        myfirstdocument.tex
myfirstdocument.pdf
```

They are created during the "Render" process. For now we are only interested in the .pdf wich contains our document:

<object data="doc1-1/myfirstdocument.pdf" type="application/pdf" width="300px" height="300px">
</object>














