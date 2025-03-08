# Grading

{% hint style="info" %}
We will evaluate your submissions based on **test results and design quality**.
{% endhint %}

## Testing results (60%)

**In section** [**Testing**](debug-and-test/testing.md)**, you use `make check` to run our test suite on your Pintos implementation, but it only tells you each test case passes or fails.** During your development, this is definitely ok, because your goal is to pass tests as many as possible.

**But after your development, we need a way to assign different weights to these test cases and collect all the scores as your final testing grade. And this is exactly what `make grade` does.**

<mark style="color:red;">**We require you to write down your**</mark>**&#x20;`make grade`&#x20;**<mark style="color:red;">**score in your design document**</mark>

{% hint style="danger" %}
<mark style="color:red;">**Notes for Windows**</mark>

In windows, if you issue `make grade` to check your score locally, you may encounter the error: `/bin/sh: 1: ../../tests/make-grade: not found, due to the CRLF problem.`

In order to solve this problem, you can download the tool `dos2unix` [here](https://waterlan.home.xs4all.nl/dos2unix.html#UNIX2DOS), and follow the instructions in [this blog](https://www.cnblogs.com/kerrycode/p/5077969.html) to get you out of the trouble.
{% endhint %}

## Design Doc & Coding style results (40%)

{% hint style="info" %}
**We will judge your design based on the design and the source code that you submit.** We will evaluate your entire design presentation and areas of your source code.

It is better to spend one or two hours writing a good design document than try to rush through writing the design document in the last 15 minutes.
{% endhint %}

### Design Document

**We provide a design document template for each project.** For each significant part of a project, the template asks questions in four areas:

#### **Data Structures**

The instructions for this section are always the same:

> Copy here the declaration of each new or changed `struct` or `struct` member, global or static variable, `typedef`, or enumeration. Identify the purpose of each in 25 words or less.

* The first part is mechanical. Just **copy&#x20;**_**new or modified**_ **declarations into the design document, to highlight for us the actual changes to data structures**. Each declaration should include the comment that should accompany it in the source code (see below).
* We also ask for a very brief description of the purpose of each new or changed data structure. <mark style="color:red;">**The limit of 25 words or less is a guideline intended to save your time and avoid duplication with later areas.**</mark>

#### **Algorithms**

**This is where you tell us how your code works**, through questions that probe your understanding of your code.

* We might not be able to easily figure it out from the code, because many creative solutions exist for most OS problems. Help us out a little.
* **Your answers should be at a level below the high-level description of the requirements given in the assignment.** We have read the assignment too, so it is unnecessary to repeat or rephrase what is stated there.
* **On the other hand, your answers should be at a level above the low level of the code itself.** Don't give a line-by-line run-down of what your code does. Instead, use your answers to explain how your code works to implement the requirements.

#### **Synchronization**

An operating system kernel is a complex, multithreaded program, in which synchronizing multiple threads can be difficult. **This section asks about how you synchronize a particular type of activity.**

#### **Rationale**

Whereas the other sections primarily ask "what" and "how," the rationale section concentrates on "why." **This is where we ask you to justify some design decisions, by explaining why the choices you made are better than alternatives.**

* You may be able to state these **in terms of time and space complexity**, which can be made as rough or informal arguments (formal language or proofs are unnecessary).
* An incomplete, evasive, or non-responsive design document or one that strays from the template without good reason may be penalized. Incorrect capitalization, punctuation, spelling, or grammar can also cost points. See section [Project Documentation](../appendix/project-documentation.md), for a sample design document for a fictitious project.
