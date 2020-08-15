---
layout: chapter-page
title: "Sets"
subtitle: "Chapter 1"
date: 2020-08-04
categories: courses
permalink: /courses/class-11-mathematics/:title:output_ext
---

## 1&nbsp;&nbsp;&nbsp;&nbsp;Introduction

Set theory is a fundamental theory in mathematics. It is used in almost every branch of mathematics. It is created by German mathematician [Georg Cantor (1845-1918)][georg-cantor].

<figure class="portrait-image">
  <img src="/images/Georg_Cantor_(Porträt).jpg" alt="Georg Cantor" width="200"/>
  <figcaption>Georg Cantor (1845-1918)</figcaption>
</figure>

## 2&nbsp;&nbsp;&nbsp;&nbsp;Sets and their Representations

### Sets

##### **Definition**

###### _A set is a well defined collection of objects._

A _collection_ is a group of objects or things, for example, a pack of cards, a cricket team, a toy set, etc. In mathematics also, we have collections of - natural numbers, prime numbers, even numbers, odd numbers, etc.

A _well defined_ collection is a collection for which we can definitely decide whether a given particular object belongs to it or not. If a collection is not _well defined_ the criteria for deciding whether the object belongs to the collection or not may vary from person to person.

**Notes:**

- _Objects, elements_ and _members_ of a set are synonymous terms.
- Sets are usually denoted by capital letters $$A, B, C, X, Y, Z,$$ etc.
- The elements of a set are represented by small letters $$a, b, c, x, y, z,$$ etc.
- $$a \in A$$ denotes '_$$a$$ belongs to $$A$$_', which means $$a$$ is an element (or object or member) of set $$A$$. The Greek symbol $$\in$$ (epsilon) is used to denote the phrase '_belongs to_'.
- $$a \notin A$$ denotes '_$$a$$ does not belong to $$A$$_', which means $$a$$ is not an element of set $$A$$. Symbol $$\notin$$ is used to denote the phrase '_belongs to_'.

<strong class="illustration">Illustration 1</strong>**Collection of odd natural numbers less than 10**  
This is a _well defined_ collection therefore a **Set**. We can definitely find all the odd natural numbers less than 10. The set can be described as $$\{1, 3, 5, 7, 9\}$$

<strong class="illustration">Illustration 2</strong>**Collection of continents of the world**  
This is a _well defined_ collection therefore a **Set**. We can definitely list all the continents of the world. The set can be described as $$\{$$**Africa, Antartica, Asia, Australia, Europe, North America, South America**$$\}$$.

<strong class="illustration">Illustration 3</strong>**Collection of the solution of the equation: $$x^2-5x+6=0$$**  
This is a _well defined_ collection therefore a **Set**. We can definitely find the solution for this equation. The set can be described as $$\{2, 3\}$$.

<strong class="illustration">Illustration 4</strong>**Collection of the good cricket players**  
This is not a _well defined_ collection. The criterion _good cricket player_ is vague and can vary from person to person. For one person, the collection can be: $$\{$$**Virat Kohli, Rohit Sharma, Mohd Shami**$$\}$$, and for another person it can be - $$\{$$**Dale Steyn, Steven Smith, Jasprit Bumrah**$$\}$$. Therefore, it is not a **Set**.

<strong class="illustration">Illustration 5</strong>**Collection of the vowels in the English alphabet**  
This is a _well defined_ collection therefore a **Set**. We can definitely list all the vowels in the English alphabet. The set can be described as $$\{a, e, i, o, u\}$$.

<strong class="illustration">Illustration 6</strong>**Collection of the prime numbers less than 10**  
This is a _well defined_ collection therefore a **Set**. The set $$P$$ of prime number less than 10 can be described as $$P = \{2, 3, 5, 7\}$$.

We see that for all natural numbers less that 10 - $$2 \in P, 3 \in P, 5 \in P$$ and $$7 \in P$$. However, $$1 \notin P, 4 \notin P, 6 \notin P, 8 \notin P$$ and $$9 \notin P$$

**Symbols for special sets in mathematics**  
The symbols and its meaning given below will be used throughout this course.

$$\mathbb{N}\quad\colon\;\text{the set of all natural numbers}$$  
$$\mathbb{Z}\quad\colon\;\text{the set of all integers}$$  
$$\mathbb{Q}\quad\colon\;\text{the set of all rational numbers}$$  
$$\mathbb{R}\quad\colon\;\text{the set of all real numbers}$$  
$$\mathbb{Z^+}\quad\colon\;\text{the set of positive integers}$$  
$$\mathbb{Q^+}\quad\colon\;\text{the set of positive rational numbers}$$  
$$\mathbb{R^+}\quad\colon\;\text{the set of positive real numbers}$$

### Sets Representations

There are two methods of representing a set:

1. Roster or tabular form.
1. Set-builder form.

#### **Roster Form**

_In roster form, all the elements of a set are listed, separated by commas and are enclosed within braces $$\{$$ $$\}$$._

<strong class="illustration">Illustration 7</strong>The set of all even numbers less than 7 is described in roster form as $$\{2, 4, 6\}$$.

**Note:**

- In roster form, the order in which the elements are listed is immaterial. Thus the set $$\{2, 4, 6\}$$ can also be written as $$\{2, 6, 4\}$$ or $$\{4, 6, 2\}$$

<strong class="illustration">Illustration 8</strong>The set of all natural numbers which divide 42 is $$\{1, 2, 3, 6, 7, 14, 21\}$$.

<strong class="illustration">Illustration 9</strong>The set of all letters forming the work _'SCHOOL'_ is $$\{S,C,H,O,L\}$$.

**Note:**

- In roster form, an element is not repeated. All the elements are taken are distinct. Therefore, in the previous example the set in roster form is $$\{S,C,H,O,L\}$$ instead of $$\{S,C,H,O,O,L\}$$

<strong class="illustration">Illustration 10</strong>The set of all prime numbers is $$\{2, 3, 5, 7, 11, 13, 17,...\}$$. The dots tell us that the list of prime numbers continue indefinitely.

#### **Set-builder Form**

_In set-builder form, instead of listing all the elements of the set, we describe the elements of the set using the format_ - $$\{x \colon \text{something about}\;x\}$$.

Where '$$x$$' (any other symbol letters $$y$$, $$z$$, etc. also could be used) denotes an element of the set, the colon ('$$\colon$$') stands for '_such that_' and '$$\text{something about}\;x$$' is some charateristic which is possessed by every element of the set.

<strong class="illustration">Illustration 11</strong>$$A=\{x:x \text{ is a natural numer and }3<x<10 \}$$ is read as '_the set of all $$x$$ such that $$x$$ is a natural number and $$x$$ lies beween 3 and 10_'. Roster form for the set is $$\{4, 5, 6, 7, 8, 9\}$$

<strong class="illustration">Illustration 12</strong>$$A=\{y:y \text{ is an ocean of the World}\}$$ is read as '_the set of all $$y$$ such that $$y$$ is an ocean of the World_'. Roster form for the set is $$\{$$**Pacific Ocean, Atlantic Ocean, Indian Ocean, Southern Ocean, Arctic Ocean**$$\}$$

<strong class="illustration">Illustration 13</strong>$$A=\{z:z \text{ is a natural number which divides } 42\}$$ is read as '_the set of all $$x$$ such that $$x$$ is a natural number and divides $$42$$_'. Roster form for the set is $$\{1, 2, 3, 6, 7, 14, 21\}$$.

<hr class="example-section-marker" />

<strong class="example">Example 1</strong>**Write the solution set of the equation $$x^2+x-2=0$$ in roster form.**

<strong class="example">Solution</strong>The given equation can be written as

$$(x-1)(x+2)=0\text{, i.e.,}\;x=1,-2$$

Therefore, the solution set of the given equation can be written in roster form as $$\{1, -2\}$$

<strong class="example">Example 2</strong>**Write the set $$\{x: x\text{ is a positive integer and }x^2<40\}$$ in the roster form.**

<strong class="example">Solution</strong>The required numbers are $$1, 2, 3, 4, 5, 6$$. So, the given set in the roster form is $$\{1, 2, 3, 4, 5, 6\}$$.

<strong class="example">Example 3</strong>**Write the set $$A=\{1, 4, 9, 16, 25, ...\}$$ in set-builder form.**

<strong class="example">Solution</strong>We may write the set $$A$$ as

$$\{x: x\text{ is the square of a natural number}\}$$

Alternatively, we can write

$$\{x: x=n^2,\text{ where }n \in \mathbb{N}\}$$

The required numbers are $$1, 2, 3, 4, 5, 6$$. So, the given set in the roster form is $$\{1, 2, 3, 4, 5, 6\}$$.

<strong class="example">Example 4</strong>**Write the set $$A=\{\frac{1}{2},\frac{2}{3}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \frac{6}{7}\}$$ in set-builder form.**

<strong class="example">Solution</strong>We see that each member in the given set has the numerator one less than the denominator. Also, the numerator begin from 1 and do not exceed 6. Hence, in the set builder form the given set is

$$\{x \colon\;x=\frac{n}{n+1},\text{ where n is a natural number and }1 \leq n \leq 6\}$$

<strong class="example">Example 5</strong>**Match each of the set on the left described in the roster form with the same set on the right described in the set-builder form:**

|**(i)** $$\;\{P,R,I,N,C,A,L\}$$|**(a)** $$\;\{x \colon\; x \text{ is a positive integer and is a divisor of }18\}$$|
|**(ii)** $$\;\{0\}$$|**(b)** $$\;\{x \colon\; x \text{ is an integer and } x^2-9=0\}$$|
|**(iii)** $$\;\{1,2,3,6,9,18\}$$|**(c)** $$\;\{x \colon\; x \text{ is an integer and } x+1=1\}$$|
|**(iv)** $$\;\{3,-3\}$$|**(d)** $$\;\{x \colon\; x \text{ is a letter of the word PRINCIPAL}\}$$|

<strong class="example">Solution</strong>  

|**(i)** $$\;\{P,R,I,N,C,A,L\}$$|**(d)** $$\;\{x \colon\; x \text{ is a letter of the word PRINCIPAL}\}$$|
|**(ii)** $$\;\{0\}$$|**(c)** $$\;\{x \colon\; x \text{ is an integer and } x+1=1\}$$|
|**(iii)** $$\;\{1,2,3,6,9,18\}$$|**(a)** $$\;\{x \colon\; x \text{ is a positive integer and is a divisor of }18\}$$|
|**(iv)** $$\;\{3,-3\}$$|**(b)** $$\;\{x \colon\; x \text{ is an integer and } x^2-9=0\}$$|


## 3&nbsp;&nbsp;&nbsp;&nbsp;The Empty Set

##### **Definition**

###### _A set which does not contain any element is called the _empty set_ or the _null set_ or the _void set_.

The empty set is denoted by the symbol $$\emptyset$$ or $$\{\}$$

<strong class="illustration">Illustration 14</strong>We can write a set as follows:  

$$A=\{x \colon \;x \text{ is a student presently studying in both Classes X and XI}\}$$

We observe that a student cannot study simultaneously in both Classes X and XI. Thus, the set $$A$$ is an _empty set_ as it contains no element at all.

<strong class="illustration">Illustration 15</strong>Let $$B=\{x \colon\;1 \lt x \lt 2,\;x\text{ is a natural number}\}$$. Then $$A$$ is the _empty set_, because there is no natural number between $$1$$ and $$2$$.

<strong class="illustration">Illustration 16</strong>Let $$B=\{x \colon\;1 \lt x \lt 2,\;x\text{ is a natural number}\}$$. Then $$A$$ is the _empty set_, because there is no natural number between $$1$$ and $$2$$.

<strong class="illustration">Illustration 17</strong>Let $$B=\{x \colon\;1 \lt x \lt 2,\;x\text{ is a natural number}\}$$. Then $$A$$ is the _empty set_, because there is no natural number between $$1$$ and $$2$$.


## 4&nbsp;&nbsp;&nbsp;&nbsp;Finite and Infinite Sets

## 5&nbsp;&nbsp;&nbsp;&nbsp;Equal Sets

## 6&nbsp;&nbsp;&nbsp;&nbsp;Subsets

## 7&nbsp;&nbsp;&nbsp;&nbsp;Power Set

## 8&nbsp;&nbsp;&nbsp;&nbsp;Universal Set

## 9&nbsp;&nbsp;&nbsp;&nbsp;Venn Diagram

## 10&nbsp;&nbsp;&nbsp;&nbsp;Operations of a Set

## 11&nbsp;&nbsp;&nbsp;&nbsp;Complement of a Set

## 12&nbsp;&nbsp;&nbsp;&nbsp;Practical Problems on Union and Intersection of Two Sets

[georg-cantor]: https://en.wikipedia.org/wiki/Georg_Cantor
