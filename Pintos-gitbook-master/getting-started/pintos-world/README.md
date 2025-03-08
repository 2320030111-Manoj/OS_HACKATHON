# Build and Run

{% hint style="info" %}
**Let's dive into the Pintos World!**
{% endhint %}

## Code Guidance

Now you've had a taste of the booting process of Pintos. Let's take a closer look at what's inside. Here's the directory structure that you can see in pintos/src:

* <mark style="color:blue;">**"threads/"**</mark>
  * Source code for **the base kernel**
* <mark style="color:blue;">**"userprog/"**</mark>
  * Source code for **the user program loader**
* <mark style="color:blue;">**"vm/"**</mark>
  * **An almost empty directory**. 
* <mark style="color:blue;">**"filesys/"**</mark>
  * Source code for **a basic file system**.
* <mark style="color:blue;">**"devices/"**</mark>
  * Source code for **I/O device interfacing**: keyboard, timer, disk, etc. 
* <mark style="color:blue;">**"lib/"**</mark>
  * **An implementation of a subset of the standard C library**. In both kernel code and user programs, headers in this directory can be included using the `#include <...>` notation. You have little need to modify this part.
* <mark style="color:blue;">**"lib/kernel/"**</mark>
  * **Parts of the C library that are included only in the Pintos kernel.** This also includes implementations of some data types that you are free to use in your kernel code: `bitmaps`, `doubly linked lists`, and `hash tables`. In the kernel, headers in this directory can be included using the `#include <...>` notation.
* <mark style="color:blue;">**"lib/user/"**</mark>
  * **Parts of the C library that are included only in Pintos user programs.** In user programs, headers in this directory can be included using the `#include <...>` notation.
* <mark style="color:blue;">**"tests/"**</mark>
  * **Tests for each project.** You can modify their codes if it helps you test your submissions. <mark style="color:red;">**When grading, we will replace your**</mark>**&#x20;`tests/`** <mark style="color:red;">**directory with the original before we run the tests.**</mark>
* <mark style="color:blue;">**"examples/"**</mark>
  * **Example user programs.**
* <mark style="color:blue;">**"misc/" and "utils/"**</mark>
  * These files may come in handy if you try working with Pintos on your own machine. Otherwise, you can ignore them.

{% hint style="info" %}
You may feel overwhelmed by so many source files and have no idea where to start. Don't worry, now you only need to have a big picture in mind and **the** [**Code Guide**](../../appendix/reference-guide/) **section serves as a more comprehensive reference to the Pintos code. You can read the corresponding part of the reference guide according to the project you are working on or when it becomes important and necessary.**
{% endhint %}

If you want to understand the dependencies of these modules and their functions, you can generate the code documentation with [Doxygen](https://www.doxygen.nl/index.html). **We provide an online code browser based on Doxygen** [**here**](https://pku-os.github.io/pintos-doxygen/html/)**.**
