<div align="center">
<h1>million digits of pi</h1>

samarth kulshrestha

![release version](https://img.shields.io/github/v/release/samarthkulshrestha/million_digits_of_pi?color=%23a039fa&include_prereleases&style=for-the-badge)
![code quality](https://img.shields.io/codefactor/grade/github/samarthkulshrestha/million_digits_of_pi/main?style=for-the-badge)
![top language](https://img.shields.io/github/languages/top/samarthkulshrestha/million_digits_of_pi?color=%234877f7&style=for-the-badge)
<br>
![license](https://img.shields.io/github/license/samarthkulshrestha/million_digits_of_pi?color=%23f2e85a&style=for-the-badge)
![pre-release date](https://img.shields.io/github/release-date-pre/samarthkulshrestha/million_digits_of_pi?color=%23f76ad4&style=for-the-badge)
![repo size](https://img.shields.io/github/repo-size/samarthkulshrestha/million_digits_of_pi?color=%2346d4a0&style=for-the-badge)
<br/><br/><br/>
![million_digits_of_pi logo](assets/million_digits_of_pi.png)
<br/><br>
</div>

## Introduction

**million_digits_of_pi** is a minimal C++ program that can compute $\pi$ and $e$
(euler's constant) to millions of digits in a quasi-linear runtime using Fast
Fourier Tranforms ([FFT](https://en.wikipedia.org/wiki/Fast_Fourier_transform))
and the [Chudnovsky Algorithm](https://en.wikipedia.org/wiki/Chudnovsky_algorithm).

## Algorithms implemented:

#### FFT-Based Multiplication (Schönhage–Strassen algorithm)


#### Newton's Method
Newton's method, also known as the Newton–Raphson method, named after Isaac
Newton and Joseph Raphson, is a root-finding algorithm which produces
successively better approximations to the roots (or zeroes) of a real-valued
function.

```math
r_1 = r_0 - \left(\frac{r_0\:^2\cdot{x-1}}{2}\right)\times{r_0}
```

<div align="center">
<img src="assets/newton_iter.png" align="center" style="margin: 16px; width: 50%;" />
</div>

#### Binary Splitting

#### Log Factorial Approximation
Returns a very good approximation of $log(x!)$. This approximation gets better
as $x$ gets larger.

```math
log(x!) \approx \frac{\left(x + \frac{1}{2}\right) \times \left(log(x) - 1\right) + \left(log(2\pi) + 1\right)}{2}
```
