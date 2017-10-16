---
title: LaTeX y R en Wordpress
author: Javier Brolo
date: '2013-03-12'
slug: latex-y-r-en-wordpress
categories: []
tags: []
header:
  caption: ''
  image: ''
---

Un tip para quienes desean utilizar $latex \LaTeX$ y R en sus entradas de Wordpress.

**Para ingresar formulas con $latex \LaTeX$:**

Colocar el código de $latex \LaTeX$ entre "$latex" y "$".

Por ejemplo:

  * "$latex" \Upsilon = \displaystyle\sum\limits_{i=0}^n i^3 "$" (sin comillas "")

Produce:

  * $latex \Upsilon = \displaystyle\sum\limits_{i=0}^n i^3$

**Para ingresar código de R**

Colocar código de R entre "[" sourcecode language="r" "]" y "[" /sourcecode "]", sin comillas "" en los brackets [ ].

Por ejemplo:

  * sourcecode language="r"]

  * # histograma

  * h <- rnorm(n=500, m=1, sd=1)

  * hist(h)

  * [/sourcecode]

Produce:

````r
# histograma
h <- rnorm(n=500, m=1, sd=1)
hist(h)
````
