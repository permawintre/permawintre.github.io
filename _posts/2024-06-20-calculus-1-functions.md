---
layout: post
title: Ch01. Functions
date: 2024-06-20 11:26 +0900
---


Thomas calculus in SI Units 14th ed 내용을 바탕으로 한다.  
### 함수의 정의
<div class="box">
$ \text{A function }f\text{ from a set }D\text{ to a set }Y\text{ is a rule that assigns a unique (single) element }\\f(x)\in Y\text{ to each element }x\in D $
</div>

### 함수의 그래프  
$$f$$가 domain $$D$$인 함수일 때 그래프는 Cartesian plane위에서 $$f$$의 input-output pair로 정의된다. set notation으로는 $$\{(x, f(x))|x\in D\}$$이다.  

### Vertical line test  
정의역의 한 점에 vertical line을 그렸을 때 그래프와의 교점은 반드시 하나가 나와야 함.  

### Piecewise-defined function  
다음과 같은 함수를 말한다.  
$$f(x)=\left\lbrace \begin{array}{ll} -x, & x<0 \\ x^2, & 0\leq x\leq 1\\ 1, & x1\\ \end{array}\right.$$  

### 증가함수/감소함수
<div class="box">
  $\text{Let }f\text{ be a function defined on an interval }I\text{ and let }x_1\text{ and }x_2\text{ be any two points in }I.\\
  \text{1. If }f(x_2)>f(x_1)\text{ whenever }x_1<x_2\text{, then }f\text{ is said to be increasing on }I\\
  \text{2. If }f(x_2)<f(x_1)\text{ whenever }x_1<x_2\text{, then }f\text{ is said to be decreasing on }I$
</div>

정의 때문에 $$I$$가 single point가 될 수 없음은 당연하고, 등호를 포함하지 않음에 유의한다. 등호를 포함하지 않는 경우 특히 _strictly_ increasing or decreasing이라 칭한다.  

### Even function and Odd functions
<div class="box">
$\text{A function }y=f(x)\text{ is an}\\
\quad\textbf{even function}\text{ of }x\text{ if }f(-x)=f(x),\\
\quad\textbf{odd function}\text{ of }x\text{ if }f(-x)=-f(x),\\
\text{for every }x\text{ in the function's domain.}$
</div>

even function이면 $$y$$축대칭, odd function이면 원점대칭이다.

### Common Functions
<div class="box">
$\text{Two variables }y\text{ and }x\text{ are }\textbf{proportional}\text{ (to one another) if one is always a constant}\\
\text{multiple of the other; that is, if }y=kx\text{ for some nonzero constant }k.$
</div>

    Linear, Quadratic, Cubic, Identity, Constant, Power, Square root, Cube root, Polynomial, Rational, Algebraic, Trigonometric, Exponential, Logarithmic, Transcendental  

많은 함수 종류가 있으나 용어 한번 짚고 넘어가면 좋을 것 같아 넣어봤다. Power은 $$y=x^a$$이고 exponential은 $$y=a^x$$이다. Transcendental(초월함수)에는 catenary(현수선), trigonometric, inverse trigonometric, exponential, logarithmic 등이 포함된다. algebraic은 polynomial로부터 (+, -, *, /, root)의 연산을 취해 나올 수 있는 모든 함수를 말한다. 예를 들어 $$y^3-9xy+x^3=0$$ 또한 가능하다.  

### Composite Functions
<div class="box">
$\text{If }f\text{ and }g\text{ are functions, the composite function }f\circ g\text{("}f\text{ composed with }g\text{") is defined by}$
$$(f\circ g)(x)=f(g(x))$$  
$\text{The domain of }f\circ g \text{ consists of the numbers }x\text{ in the domain of }g\text{ for which }g(x)\\
\text{ lies in the domain of }f$
</div>

### Shifting, Scaling and Reflecting a graph
<div class="box">
 $$\begin{array}{lll}
&\textbf{Vertical Shifts} &\\
&y=f(x)+k &\text{Shifts the graph of }f\text{ up }k\text{ units if }k0 \\
&&\text{Shifts it down }|k|\text{ units if }k<0\\ 
&\textbf{Horizontal Shifts}\\
&y=f(x+h) &\text{Shifts the graph of }f\text{ left }h\text{ units if }h0 \\
&&\text{Shifts it right }|h|\text{ units if }h<0\\
&\textbf{for c}\neq\textbf{1, the graph is scaled:}\\
&y=cf(x) &\text{Stretches the graph of }f\text{ vertically by a factor of }c.\\
&y=\frac{1}{c}f(x) &\text{Compresses the graph of }f\text{ vertically by a factor of }c.\\
&y=f(cx) &\text{Compresses the graph of }f\text{ horizontally by a factor of }c.\\
&y=f(x/c) &\text{Stretches the graph of }f\text{ horizontally by a factor of }c.\\
&\textbf{for c=1, the graph is reflected:}\\
&y=-f(x) &\text{Reflects the graph of }f\text{ across the }x\text{-axis.}\\
&y=f(-x) &\text{Reflects the graph of }f\text{ across the }y\text{-axis.}
\end{array}$$
</div>


### Periodicity
<div class="box">
$\text{A funciton }f(x)\text{ is }\textbf{periodic}\text{ if there is a positive number }p\text{ such that }f(x+p)=f(x)\\
\text{ for every value of }x\text{. The smallest such value of }p\text{ is the }\textbf{period}\text{ of }f.$
</div>

### Trigonometric Identities
Addition Formula, Double-Angle Formula, Half-Angle Formula 등등은 간단하므로 생략. 아래 식은 잘 안쓰므로 리마인드만 합시다.  
$$1+tan^2\theta=sec^2\theta \\ 1+cot^2\theta=csc^2\theta$$

### Special Inequalities
$$-|\theta|\leq sin\theta\leq|\theta|$$ and $$-|\theta|\leq 1-cos\theta\leq|\theta|$$  