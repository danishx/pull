Git 101 Session

Updating again

# Context
[1- Headings](#1--headings)\
[2- Block of wordscitation](#2--block-of-words)\
[3- Line Breaks](#3--line-breaks)\
[4- Combine Two things](#4--combine-two-things)\
[5- Face of Text](#5--face-of-text)\
[6- Bullet](#6--bullets-points-list)\
[7- Line/page breaka](#7--line-breaks-or-page-breaks)
[8- Linka](#8--links-and-hyperlinks)\
[9- Figure Links](#9--images-and-figures-with-link)\
[10- Adding code/code blocks](#10--adding-code-or-code-block)\
[11- Tables](#11--adding-tables)
[12- Installation](#12--install-extensions)

# 1- Headings
How to give headings in markdown files?
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
###### so on

# 2- Block of words

This is a normal text in markdown

>This is a block of special text
>
>This is a second line

# 3- Line breaks

This is a 40 days line course data science with python.\
This is a second line

# 4- Combine two things

Blovk of words and heading

> ## Heading 2

# 5- Face of text

**bold**

*Italic*

***Bold and Italic***

or you can use these symbols

_(Underscore)

__Bold__

_Italic_

___Bold and Italic___

# 6- Bullets points/ List

- Day1
- Day2
- Day3
- Day4
- Day5
    - Day5a
        - Sublist (Anything)
    - Day5b
- Day 6

>Numbering of list

> __using * or +__
* one

1. Day1
2. Day2
3. Day3
1. Day5
    1. Day5a
    2. Day5b
1. Day6
1. Day7
1. Day88

# 7- Line breaks or page breaks

This is page 1.

---
___
***
This is page 2.

# 8- Links and Hyperlinks

[link](https://www.youtube.com/watch?v=sCLY-afpGzU)

[My Youtube channel](https://www.youtube.com/watch?v=sCLY-afpGzU)

[channel]:https://www.youtube.com/watch?v=sCLY-afpGzU

youtube channel is [here][channel].

# 9- Images and Figures with link

Image:
[Image](test.jpg)

<!-- coment out line with ctrl + / -->

# 10- Adding code or code block

To print a string use `print("Codanics")`

`print("Hello World")`

This code will show color according to python language syyntax

```python
x = 5 + 6
y = 3 + 2
z = x + y
print(z)
```
This code will show color according to R language syntax

```R
x = 5 + 6
y = 3 + 2
z = x + y
print(z)
```

<!-- for midle-align use : -->
# 11- Adding tables

| Species | petal_length | sepal_length
| :-------: |:-------------: | :------------:  
| Virginica | 18.2 | 19.2
| Satosa | 20.2 | 17.2
| Versicolor | 12.2 | 21.2
| Satosa | 20.2 | 17.2
| Virginica | 18.2 | 19.2


# 12- Install extensions

**Sample Text**

_Italic_

**_Italic and bold_**

[Link](https://www.youtube.com/watch?v=sCLY-afpGzU)

![Image](test.jpg)

`Image`


Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3

 
Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3

 # 13- How to change color
 
 <span style="color:red">
 This is for color
 </span>


# 14- Adding equations in MD

> In-line math

$this_{is}^{inline}$

> Math block

$$
\int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
$$