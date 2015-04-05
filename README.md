
# latex-cheatsheet

> **Latex** for **All**
> 
> This is a **quick** but **incomplete** reference. This is by design.


## i need help

So you need some help with your LaTeX? You can:

1. Use the [table of contents](#toc) below to find the item of interest
* Use the [resources](#res) to find more information
* Use [Google](https://www.google.com) like everyone else
* Head over to [StackOverflow](http://stackoverflow.com) and read through [tagged questions](http://stackoverflow.com/questions/tagged/latex)


<a name="toc"></a>
## table of contents:

1. [document structure](#ds)
* [comments](#comm)
* [paragraphs](#para)
* [new lines](#newl)
* [lists](lists)
* [mathematical expressions](#expr)
* [images](#img)
* [symbols](#sym)
* [resources](#res)
* [licensing](#lic)


<a name="ds"></a>
## document structure

An example of a minimal document would be:

```latex
\documentclass{class}

% this area is called the "preamble"
% the "class" in the \documentclass{} command above ⬆ must be
% with a valid class name. See notes below for built-in classes.

\begin{document}

% your content will go here

\end{document}
```

* `\documentclass{class}` **must** be the first command in the LaTeX file
* built-in document classes: `article`, `report`, `book`, `letter`, `slides`

[⬆ table of contents](#toc)


## syntax:

<a name="comm"></a>
### comments

* ignored during compilation

```latex
% anything after the % is ignored
```
[⬆ table of contents](#toc)


<a name="para"></a>
### paragraphs

* leave one empty line between two sections of text

```latex
This will one paragraph

And this another
```
[⬆ table of contents](#toc)


<a name="newl"></a>
### new lines

* use `\\` at end of line

```latex
This forces a\\
new line
```
[⬆ table of contents](#toc)


### text decorations:

#### italics

```latex
\textit{text in italics}
```

#### boldface

```latex
\textbf{text in boldface}
```

#### underlined

```latex
\underline{underlined text}
```

[⬆ table of contents](#toc)


<a name="lists"></a>
### lists:

#### unordered list

```latex
\begin{itemsize}
\item{An item}
\item{Another item}
\end{itemsize}
```

#### ordered list:

```latex
\begin{enumerate}
\item{First item}
\item{Second item}
\end{enumerate}
```

[⬆ table of contents](#toc)


<a name="expr"></a>
### mathematical expressions:

#### inline

* occur within a sentence
* placed between dollar-signs `$`

```latex
A mathematical expression, such as $\frac{\pi}{2}$, can appear within a line
```

#### equations

* on a separate line
* centered on the page
* placed between `\[` and `\]`

```latex
\[area = {\pi}*r^2\]
```

#### embedded text

* placed between `\text{` and `}`

```latex
\{x\in\mathbb{R}:x>0\text{ and }x\le 1\}
```

#### text decorations:

##### boldface

```latex
\mathbf{R}
```

##### blackboard bold

```latex
\mathbb{R}
```

[⬆ table of contents](#toc)


<a name="img"></a>
### images

* requires the .tex file be in the same location as the image during compilation

```latex
\begin{figure}
\includegraphics{imagename.png}
\caption{An optional caption goes here}
\end{figure}
```
[⬆ table of contents](#toc)


<a name="sym"></a>
### symbols:


#### text

1. dollar sign: `\$`
* percent: `\%`
* ampersand: `\&`
* pound (hashtag): `\#`
* backslash: `\textbackslash`

[⬆ table of contents](#toc)


#### general mathematics

1. addition: `+`
* subtraction: `-`
* plus or minus: `\pm`
* multiplication (times): `\times`
* multiplication (dot): `\cdot`
* division (symbol): `\div`
* division (slash): `/`
* equal: `=`
* not equal: `\ne`
* less than: `<`
* greater than: `>`
* less than or equal to: `\le`
* greater than or equal to: `\ge`
* fraction: `\frac{numerator}{denominator}`
* square root: `\sqrt{x}`
* _n_th root: `\sqrt[n]{x}`
* exponentiation (superscript): `a^b`
* subscript: `a_b`
* absolute value: `|x|`
* logarithmn: `\log_{a}b`
* natural logarithmn: `\ln(x)`

[⬆ table of contents](#toc)


<a name="res"></a>
## resources:

### readings

* [Quick Guide to Latex](http://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf)
* [Latex CheatSheet](http://www.stdout.org/~winston/latex/latexsheet.pdf)

### software

* [TexMaker](http://www.xm1math.net/texmaker/)
* [ShareLatex](http://www.sharelatex.com/)

[⬆ table of contents](#toc)


<a name="lic"></a>
## licensing:

__The MIT License (MIT)__

Copyright (c) 2015 GochoMugo <mugo@forfuture.co.ke>

