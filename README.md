
# latex-cheatsheet

> **Latex** for **All**
> 
> This is a **quick** but **incomplete** reference. This is by design.


## minimal document (document structure)

An example of a minimal document would be:

```latex
\documentclass{class}

% this area is called the preamble

\begin{document}

% your content will go here

\end{document}
```


## syntax:

### comments

* ignored during compilation

```latex
% anything after the % is ignored
```


### paragraphs

* leave one empty line between two sections of text

```latex
This will one paragraph

And this another
```


### new lines

* use `\\` at end of line

```latex
This forces a\\
new line
```


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


### images

* requires the .tex file be in the same location as the image during compilation

```latex
\begin{figure}
\includegraphics{imagename.png}
\caption{An optional caption goes here}
\end{figure}
```


### symbols:


#### text

1. dollar sign: `\$`
* percent: `\%`
* ampersand: `\&`
* pound (hashtag): `\#`
* backslash: `\textbackslash`

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


## resources:

### readings

* [Quick Guide to Latex](http://users.dickinson.edu/~richesod/latex/latexcheatsheet.pdf)
* [Latex CheatSheet](http://www.stdout.org/~winston/latex/latexsheet.pdf)

### software

* [TexMaker](http://www.xm1math.net/texmaker/)
* [ShareLatex](http://www.sharelatex.com/)


## licensing:

__The MIT License (MIT)__

Copyright (c) 2015 GochoMugo <mugo@forfuture.co.ke>

