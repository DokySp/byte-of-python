---
description: About Python
---

# 파이썬에 대해

Python is one of those rare languages which can claim to be both _simple_ and _powerful_. You will find yourself pleasantly surprised to see how easy it is to concentrate on the solution to the problem rather than the syntax and structure of the language you are programming in.

> 파이썬은 _심플함_ 과 _강력함_ 모두를 갖춘 몇 안되는 언어 중 하나라고 할 수 있습니다. 여러분은 프로그래밍 문법이나 언어의 구조에 신경쓰는 것 보다 문제를 해결하는 것에 쉽게 집중할 수 있다는 점에 놀라는 자신의 모습을 찾게 될 것입니다.


The official introduction to Python is:

> 파이썬의 공식 소개 문서에는 아래와 같이 쓰여있습니다 :

> Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python's elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.

> 파이썬은 배우기 쉽고, 강력한 프로그래밍 언어입니다. 파이썬은 효율적인 고수준의 데이터 구조를 가지고 있으며, 간단하지만 효과적인 객체지향에 대한 접근법을 가지고 있습니다. 파이썬의 인터프리터 환경에서 우아한 문법과 동적인 타이핑은 파이썬을 스크립팅하거나 많은 플랫폼에 많은 분야에서 빠르게 앱을 개발하는데 이상적인 언어로 만들어줍니다.

I will discuss most of these features in more detail in the next section.

> 앞으로 이러한 특징들에 대해 다음 섹션에서 더욱 자세하기 소개해보도록 하겠습니다.

## Python이라는 이름의 비하인드 스토리

Guido van Rossum, the creator of the Python language, named the language after the BBC show "Monty Python's Flying Circus". He doesn't particularly like snakes that kill animals for food by winding their long bodies around them and crushing them.

> Python의 아버지인 귀도 반 로썸(Guido van Rossum)은 BBC의 TV 프로인 "Monty Python's Flying Circus"에서 Python이라는 이름을 짓게 되었다고 합니다. 그는 긴 몸을 감아서 동물을 부셔버리는 뱀(파이썬)을 딱히 좋아하지는 않는다고 합니다.

## 파이썬의 특징 

### 심플하다

Python is a simple and minimalistic language. Reading a good Python program feels almost like reading English, although very strict English! This pseudo-code nature of Python is one of its greatest strengths. It allows you to concentrate on the solution to the problem rather than the language itself.

> Python은 심플하고 미니멀한 프로그래밍 언어입니다. 잘 짜여진 파이썬 프로그램을 보면 마치 그냥 (꽤나 엄격한 문법을 가진)영어로 된 글을 읽는 것 같다고 합니다. Python이 수도코드(pseudo-code)같다는 것은 강력한 파이썬의 특징 중 하나입니다. 이러한 특징은 여러분이 파이썬 코딩을 할 때 언어 그 자체(문법, 구조 등)보다 문제에 집중할 수 있도록 도와줍니다.

### 배우기 쉽다

As you will see, Python is extremely easy to get started with. Python has an extraordinarily simple syntax, as already mentioned.

### 무료이며 오픈소스이다

Python is an example of a _FLOSS_ \(Free/Libré and Open Source Software\). In simple terms, you can freely distribute copies of this software, read its source code, make changes to it, and use pieces of it in new free programs. FLOSS is based on the concept of a community which shares knowledge. This is one of the reasons why Python is so good - it has been created and is constantly improved by a community who just want to see a better Python.

### 고수준(High-Level) 언어이다

When you write programs in Python, you never need to bother about the low-level details such as managing the memory used by your program, etc.

### Portable

Due to its open-source nature, Python has been ported to \(i.e. changed to make it work on\) many platforms. All your Python programs can work on any of these platforms without requiring any changes at all if you are careful enough to avoid any system-dependent features.

You can use Python on GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE and PocketPC!

You can even use a platform like [Kivy](http://kivy.org) to create games for your computer _and_ for iPhone, iPad, and Android.

### 인터프리터 언어이다

This requires a bit of explanation.

A program written in a compiled language like C or C++ is converted from the source language i.e. C or C++ into a language that is spoken by your computer \(binary code i.e. 0s and 1s\) using a compiler with various flags and options. When you run the program, the linker/loader software copies the program from hard disk to memory and starts running it.

Python, on the other hand, does not need compilation to binary. You just _run_ the program directly from the source code. Internally, Python converts the source code into an intermediate form called bytecodes and then translates this into the native language of your computer and then runs it. All this, actually, makes using Python much easier since you don't have to worry about compiling the program, making sure that the proper libraries are linked and loaded, etc. This also makes your Python programs much more portable, since you can just copy your Python program onto another computer and it just works!

### 객체지향 언어이다

Python supports procedure-oriented programming as well as object-oriented programming. In _procedure-oriented_ languages, the program is built around procedures or functions which are nothing but reusable pieces of programs. In _object-oriented_ languages, the program is built around objects which combine data and functionality. Python has a very powerful but simplistic way of doing OOP, especially when compared to big languages like C++ or Java.

### Extensible

If you need a critical piece of code to run very fast or want to have some piece of algorithm not to be open, you can code that part of your program in C or C++ and then use it from your Python program.

### 이식성이 강하다.

You can embed Python within your C/C++ programs to give _scripting_ capabilities for your program's users.

### 확장 라이브러리가 많다

The Python Standard Library is huge indeed. It can help you do various things involving regular expressions,documentation generation, unit testing, threading, databases, web browsers, CGI, FTP, email, XML, XML-RPC, HTML, WAV files, cryptography, GUI \(graphical user interfaces\), and other system-dependent stuff. Remember, all this is always available wherever Python is installed. This is called the _Batteries Included_ philosophy of Python.

Besides the standard library, there are various other high-quality libraries which you can find at the [Python Package Index](http://pypi.python.org/pypi).

### 요약

Python is indeed an exciting and powerful language. It has the right combination of performance and features that make writing programs in Python both fun and easy.

## Python 3 vs 2

You can ignore this section if you're not interested in the difference between "Python version 2" and "Python version 3". But please do be aware of which version you are using. This book is written for Python version 3.

Remember that once you have properly understood and learn to use one version, you can easily learn the differences and use the other one. The hard part is learning programming and understanding the basics of Python language itself. That is our goal in this book, and once you have achieved that goal, you can easily use Python 2 or Python 3 depending on your situation.

For details on differences between Python 2 and Python 3, see:

* [The future of Python 2](http://lwn.net/Articles/547191/)
* [Porting Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html)
* [Writing code that runs under both Python2 and 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
* [Supporting Python 3: An in-depth guide](http://python3porting.com)

## 프로그래머들이 말하는 Python

You may find it interesting to read what great hackers like ESR have to say about Python:

* _Eric S. Raymond_ is the author of "The Cathedral and the Bazaar" and is also the person who coined the term _Open Source_. He says that [Python has become his favorite programming language](http://www.python.org/about/success/esr/). This article was the real inspiration for my first brush with Python.
* _Bruce Eckel_ is the author of the famous 'Thinking in Java' and 'Thinking in C++' books. He says that no language has made him more productive than Python. He says that Python is perhaps the only language that focuses on making things easier for the programmer. Read the [complete interview](http://www.artima.com/intv/aboutme.html) for more details.
* _Peter Norvig_ is a well-known Lisp author and Director of Search Quality at Google \(thanks to Guido van Rossum for pointing that out\). He says that [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815). He says that Python has always been an integral part of Google. You can actually verify this statement by looking at the [Google Jobs](http://www.google.com/jobs/index.html) page which lists Python knowledge as a requirement for software engineers.

