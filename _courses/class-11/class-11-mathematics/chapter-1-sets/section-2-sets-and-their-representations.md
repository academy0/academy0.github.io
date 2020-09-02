---
layout: class-11-mathematics
chapter: Sets
chapter_number: 1
section: Sets and their Representations
section_number: 2
permalink: /courses/class-11-mathematics/chapter-1/section-2
---

### Sets

{% include definition.html content="A set is a well defined collection of objects."%}

- A _collection_ is a group of objects or things, for example, a pack of cards, a cricket team, a toy set, etc. In mathematics also, we have collections of natural numbers, prime numbers, even numbers, odd numbers, etc.
- A _well defined_ collection is a collection for which we can definitely decide whether a given particular object belongs to it or not. If a collection is not _well defined_ the criteria for deciding whether the object belongs to the collection or not may vary from person to person.
- _Objects, elements_ and _members_ of a set are synonymous terms.
- Sets are usually denoted by capital letters $$A, B, C, X, Y, Z,$$ etc.
- The elements of a set are represented by small letters $$a, b, c, x, y, z,$$ etc.
- $$a \in A$$ denotes '_$$a$$ belongs to $$A$$_', which means $$a$$ is an element (or object or member) of set $$A$$. The Greek symbol $$\in$$ (epsilon) is used to denote the phrase '_belongs to_'.
- $$a \notin A$$ denotes '_$$a$$ does not belong to $$A$$_', which means $$a$$ is not an element of set $$A$$. Symbol $$\notin$$ is used to denote the phrase '_belongs to_'.


{% include illustration.html number="1" content="
**Collection of odd natural numbers less than 10**  
This is a _well defined_ collection therefore a **Set**. We can definitely find all the odd natural numbers less than 10. The set can be described as $$\{1, 3, 5, 7, 9\}$$
"%}

{% include illustration.html number="2" content="
**Collection of continents of the world**  
This is a _well defined_ collection therefore a **Set**. We can definitely list all the continents of the world. The set can be described as $$\{$$**Africa, Antartica, Asia, Australia, Europe, North America, South America**$$\}$$.
"%}

{% include illustration.html number="3" content="
**Collection of the solution of the equation: $$x^2-5x+6=0$$**  
This is a _well defined_ collection therefore a **Set**. We can definitely find the solution for this equation. The set can be described as $$\{2, 3\}$$.
"%}

{% include illustration.html number="4" content="
**Collection of the good cricket players**  
This is not a _well defined_ collection. The criterion _good cricket player_ is vague and can vary from person to person. For one person, the collection can be: $$\{$$**Virat Kohli, Rohit Sharma, Mohd Shami**$$\}$$, and for another person it can be - $$\{$$**Dale Steyn, Steven Smith, Jasprit Bumrah**$$\}$$. Therefore, it is not a **Set**.
"%}

{% include illustration.html number="5" content="
**Collection of the vowels in the English alphabet**  
This is a _well defined_ collection therefore a **Set**. We can definitely list all the vowels in the English alphabet. The set can be described as $$\{a, e, i, o, u\}$$.
"%}

{% include illustration.html number="6" content="
**Collection of the prime numbers less than 10**  
This is a _well defined_ collection therefore a **Set**. The set $$P$$ of prime number less than 10 can be described as $$P = \{2, 3, 5, 7\}$$.

We see that for all natural numbers less that 10, we have $$2 \in P, 3 \in P, 5 \in P$$ and $$7 \in P$$. However, $$1 \notin P, 4 \notin P, 6 \notin P, 8 \notin P$$ and $$9 \notin P$$
"%}

#### **Symbols for special sets in mathematics**  
The symbols and its meaning given below will be used throughout this course.

|$$\mathbb{N}$$|$$\colon\quad\text{the set of all natural numbers}$$|  
|$$\mathbb{Z}$$|$$\colon\quad\text{the set of all integers}$$|  
|$$\mathbb{Q}$$|$$\colon\quad\text{the set of all rational numbers}$$|  
|$$\mathbb{R}$$|$$\colon\quad\text{the set of all real numbers}$$|  
|$$\mathbb{Z^+}$$|$$\colon\quad\text{the set of positive integers}$$|  
|$$\mathbb{Q^+}$$|$$\colon\quad\text{the set of positive rational numbers}$$|
|$$\mathbb{R^+}$$|$$\colon\quad\text{the set of positive real numbers}$$|  


### Sets Representations

There are two methods of representing a set:

1. Roster or tabular form.
1. Set-builder form.

#### **Roster Form**

_In roster form, all the elements of a set are listed, separated by commas and are enclosed within braces $$\{$$ $$\}$$._

{% include illustration.html number="7" content="
The set of all even numbers less than 7 is described in roster form as $$\{2, 4, 6\}$$.
"%}

- In roster form, the order in which the elements are listed is immaterial. Thus the set $$\{2, 4, 6\}$$ can also be written as $$\{2, 6, 4\}$$ or $$\{4, 6, 2\}$$

{% include illustration.html number="8" content="
The set of all natural numbers which divide 42 is $$\{1, 2, 3, 6, 7, 14, 21\}$$.
"%}

{% include illustration.html number="9" content="
The set of all letters forming the work _'SCHOOL'_ is $$\{S,C,H,O,L\}$$.
"%}

- In roster form, an element is not repeated. All the elements are taken are distinct. Therefore, in the previous example the set in roster form is $$\{S,C,H,O,L\}$$ instead of $$\{S,C,H,O,O,L\}$$

{% include illustration.html number="10" content="
The set of all prime numbers is $$\{2, 3, 5, 7, 11, 13, 17,...\}$$. The dots tell us that the list of prime numbers continue indefinitely.
"%}

#### **Set-builder Form**

_In set-builder form, instead of listing all the elements of the set, we describe the elements of the set using the format_ - $$\{x \colon \text{something about}\;x\}$$.

Where '$$x$$' (any other symbol letters $$y$$, $$z$$, etc. also could be used) denotes an element of the set, the colon ('$$\colon$$') stands for '_such that_' and '$$\text{something about}\;x$$' is some charateristic which is possessed by every element of the set.

{% include illustration.html number="11" content="
$$A=\{x:x \text{ is a natural numer and }3<x<10 \}$$ is read as '_the set of all $$x$$ such that $$x$$ is a natural number and $$x$$ lies beween 3 and 10_'. Roster form for the set is $$\{4, 5, 6, 7, 8, 9\}$$
"%}

{% include illustration.html number="12" content="
$$A=\{y:y \text{ is an ocean of the World}\}$$ is read as '_the set of all $$y$$ such that $$y$$ is an ocean of the World_'. Roster form for the set is $$\{$$**Pacific Ocean, Atlantic Ocean, Indian Ocean, Southern Ocean, Arctic Ocean**$$\}$$
"%}

{% include illustration.html number="13" content="
$$A=\{z:z \text{ is a natural number which divides } 42\}$$ is read as '_the set of all $$x$$ such that $$x$$ is a natural number and divides $$42$$_'. Roster form for the set is $$\{1, 2, 3, 6, 7, 14, 21\}$$.
"%}

<hr class="example-section-marker" />

{% include example.html number="1"
question="Write the solution set of the equation $$x^2+x-2=0$$ in roster form."
solution="The given equation can be written as

$$(x-1)(x+2)=0\text{, i.e.,}\;x=1,-2$$

Therefore, the solution set of the given equation can be written in roster form as $$\{1, -2\}$$
"%}


{% include example.html number="2"
question="Write the set $$\{x: x\text{ is a positive integer and }x^2<40\}$$ in the roster form."
solution="The required numbers are $$1, 2, 3, 4, 5, 6$$. So, the given set in the roster form is $$\{1, 2, 3, 4, 5, 6\}$$."%}

{% include example.html number="3"
question="Write the set $$A=\{1, 4, 9, 16, 25, ...\}$$ in set-builder form."
solution="We may write the set $$A$$ as

$$\{x: x\text{ is the square of a natural number}\}$$

Alternatively, we can write

$$\{x: x=n^2,\text{ where }n \in \mathbb{N}\}$$

The required numbers are $$1, 2, 3, 4, 5, 6$$. So, the given set in the roster form is $$\{1, 2, 3, 4, 5, 6\}$$."%}

{% include example.html number="4"
question="Write the set $$A=\{\frac{1}{2},\frac{2}{3}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \frac{6}{7}\}$$ in set-builder form."
solution="We see that each member in the given set has the numerator one less than the denominator. Also, the numerator begin from 1 and do not exceed 6. Hence, in the set builder form the given set is

$$\{x \colon\;x=\frac{n}{n+1},\text{ where n is a natural number and }1 \leq n \leq 6\}$$"%}

{% include example.html number="5"
question="**Match each of the set on the left described in the roster form with the same set on the right described in the set-builder form:**

|**(i)**| $$\;\{P,R,I,N,C,A,L\}$$|**(a)**| $$\;\{x \colon\; x \text{ is a positive integer and is a divisor of }18\}$$|
|**(ii)**| $$\;\{0\}$$|**(b)**| $$\;\{x \colon\; x \text{ is an integer and } x^2-9=0\}$$|
|**(iii)**| $$\;\{1,2,3,6,9,18\}$$|**(c)**| $$\;\{x \colon\; x \text{ is an integer and } x+1=1\}$$|
|**(iv)**| $$\;\{3,-3\}$$|**(d)**| $$\;\{x \colon\; x \text{ is a letter of the word PRINCIPAL}\}$$|"

solution="|**(i)** $$\;\{P,R,I,N,C,A,L\}$$|**(d)**| $$\;\{x \colon\; x \text{ is a letter of the word PRINCIPAL}\}$$|
|**(ii)** $$\;\{0\}$$|**(c)**| $$\;\{x \colon\; x \text{ is an integer and } x+1=1\}$$|
|**(iii)** $$\;\{1,2,3,6,9,18\}$$|**(a)**| $$\;\{x \colon\; x \text{ is a positive integer and is a divisor of }18\}$$|
|**(iv)** $$\;\{3,-3\}$$|**(b)**| $$\;\{x \colon\; x \text{ is an integer and } x^2-9=0\}$$|"%}



