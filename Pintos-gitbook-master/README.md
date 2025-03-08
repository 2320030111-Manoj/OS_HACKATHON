# 🌈 Welcome to Pintos

![](.gitbook/assets/klh.jpg)

## Introduction

**Pintos is a simple operating system framework for the 80x86 architecture.** It supports **kernel threads**, **loading and running user programs**, and **a file system**, but it implements all of these in a very simple way. In the Pintos projects, you will strengthen its support in all three of these areas. You will also add a virtual memory implementation.

**Pintos could, theoretically, run on a regular IBM-compatible PC**. Unfortunately, it is impractical to supply every student a dedicated PC for use with Pintos. Therefore, we will run Pintos projects in a system simulator, that is, a program that simulates an 80x86 CPU and its peripheral devices accurately enough that unmodified operating systems and software can run under it. In class we will use the [Bochs](http://bochs.sourceforge.net) and [QEMU](http://fabrice.bellard.free.fr/qemu/) simulators. Pintos has also been tested with [VMware Player](http://www.vmware.com).

## History

Pintos was originally developed at Stanford by Ben Pfaff [blp@cs.stanford.edu](mailto:blp@cs.stanford.edu) to substitute for the old OS course project Nachos. After more than a decade of iterations, Pintos has been adopted by over fifty institutes as the OS course project, including Stanford, UC Berkeley, Carnegie Mellon, Johns Hopkins, and so on. You can read the original [Pintos paper](https://benpfaff.org/papers/pintos.pdf) (Yes, they even write a paper for it !) to learn the details of Pintos' design philosophy and its comparison with other instructional operating system kernels, e.g., JOS, Nachos, GeekOS, and so on.

{% hint style="info" %}
**Why the name "Pintos"?:**

First, like nachos, pinto beans are common Mexican food. Second, Pintos is small and a "pint" is a small amount. Third, like drivers of the eponymous car, students are likely to have trouble with blow-ups. —— Ben Pfaff
{% endhint %}

## PSet Overview

**In each PSet, we will release all the test cases to support your local development.**

**A large part of your score will be determined by the quality of your design document and your code.** Don't worry, we will provide document templates for you to limit your document to hundreds of words long.

**In a word, we hope this hackathon will be a challenging but rewarding experience for all of you guys.**

## <mark style="color:red;">Cheating and Collaboration</mark>

{% hint style="danger" %}
<mark style="color:red;">**This hackathon has zero tolerance for cheating.**</mark>
{% endhint %}

<mark style="color:red;">**The basic policies for your submissions are as follows:**</mark>

* <mark style="color:red;">**Never copy project code or text found on the Internet**</mark><mark style="color:red;">, e.g., GitHub.</mark>
* <mark style="color:red;">**Never share code or text on the project.**</mark> <mark style="color:red;">That also means do not make your solutions public on the Internet.</mark>
* <mark style="color:red;">**Never use others' code or text in your solutions.**</mark> 
* <mark style="color:red;">You may read but</mark> <mark style="color:red;">**not**</mark> <mark style="color:red;">copy Linux or BSD source code.</mark> <mark style="color:red;">**You must cite any document or code that inspired your code**</mark><mark style="color:red;">. As long as you cite what you used, it's not cheating. In the worst case, we deduct points if it undermines the PSet.</mark>

**On the other hand, we encourage collaboration in the following form:**

* Explain a concept to another student, or ask another student to explain a concept to you.
* Discuss algorithms or approaches for an exercise. But you should not exchange, look at, or copy each other's code.
* Discuss testing strategies and approaches.
* Help someone else debug if they've got stuck. But you should not give that student code solution.

The hackathon staff will actively detect possible ethics violations.

## What's next?

In the next chapter, you will set up your local development environment, boot Pintos and get familiar with its debugging and testing tools. You will use these utilities throughout the semester again and again and again. So read carefully and patiently \~\~
