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

> 보시다시피, Python은 시작하기 굉장히 쉽습니다. Python은 앞에서 언급했다시피 이상적인 문법 구조를 가지고 있습니다.

### 무료이며 오픈소스이다

Python is an example of a _FLOSS_ \(Free/Libré and Open Source Software\). In simple terms, you can freely distribute copies of this software, read its source code, make changes to it, and use pieces of it in new free programs. FLOSS is based on the concept of a community which shares knowledge. This is one of the reasons why Python is so good - it has been created and is constantly improved by a community who just want to see a better Python.

> 파이썬은 _FLOSS_ \(Free/Libré and Open Source Software\)의 예시입니다. 간단하게 보면, 여러분은 무료로 이 소프트웨어의 복사본에 기여할 수 있으며, 코드를 읽을 수 있고, 변경할 수도 있으며, 새로운 무료 프로그램을 만드는데 일부로 사용할 수도 있습니다. FLOSS는 지식을 공유하는 커뮤니티를 기반으로 하고 있습니다. 이렇게 파이썬이 개선되는 것을 원하는 커뮤니티에 의해 지속적으로 제작되어지고 개발되어진다는 것은 파이썬의 장점이 되는 이유 중 하나입니다.

### 고수준(High-Level) 언어이다

When you write programs in Python, you never need to bother about the low-level details such as managing the memory used by your program, etc.

> Python으로 코딩할 때, 저수준(low-level) 단의 메모리 관리 등의 자세한 내용의 것들 때문에 귀찮은 일이 생기지 않습니다.

### Portable

Due to its open-source nature, Python has been ported to \(i.e. changed to make it work on\) many platforms. All your Python programs can work on any of these platforms without requiring any changes at all if you are careful enough to avoid any system-dependent features.

You can use Python on GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE and PocketPC!

You can even use a platform like [Kivy](http://kivy.org) to create games for your computer _and_ for iPhone, iPad, and Android.

> 오픈소스라는 특징 때문에, Python은 많은 플랫폼으로 이식되어졌습니다. 여러분이 작성한 모든 Python 프로그램들은 시스템에 의존적인(system-dependent)요소들을 배제하여 개발한다면 특별한 수정 없이도 다양한 플랫폼에서 구동이 가능합니다.
> 
> Python은 GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE와 PocketPC에서도 사용할 수 있답니다!

### 인터프리터 언어이다

This requires a bit of explanation.

A program written in a compiled language like C or C++ is converted from the source language i.e. C or C++ into a language that is spoken by your computer \(binary code i.e. 0s and 1s\) using a compiler with various flags and options. When you run the program, the linker/loader software copies the program from hard disk to memory and starts running it.

Python, on the other hand, does not need compilation to binary. You just _run_ the program directly from the source code. Internally, Python converts the source code into an intermediate form called bytecodes and then translates this into the native language of your computer and then runs it. All this, actually, makes using Python much easier since you don't have to worry about compiling the program, making sure that the proper libraries are linked and loaded, etc. This also makes your Python programs much more portable, since you can just copy your Python program onto another computer and it just works!

> 이 특징을 설명하려면 약간의 예시가 필요합니다.
> 
> C나 C++같은 컴파일 언어로 작성된 프로그램들은 원본 소스 언어(C, C++ 언어)에서 컴파일러에 다양한 설정들을 맞추어서 컴퓨터가 이해할 수 있는 언어\(0 또는 1로 이루어진 바이너리 코드\)로 바꿔줘야 합니다. 프로그램을 실행하려 할 때, 링커와 로더 소프트웨어가 하드드라이브에서 메모리로 로딩하여 프로그램을 구동하게 됩니다.
> 
> 반면에 Python은 바이너리 코드로 컴파일 할 필요가 없습니다. 그저 프로그램 코드를 _실행_ 하기만 하면 됩니다. 내부적으로 파이썬은 파이썬 코드를 즉각적으로 바이트 코드로 변환한 다음, 컴퓨터가 알아들을 수 있는 언어로 번역하게 되고 프로그램을 구동하게 됩니다. 사실 이 모든 과정이 프로그램 코드를 컴파일링 하는데 신경을 쓸 필요가 없게 해주며, 적절한 라이브러리들이 링킹되고 로드되는 것 등을 특별히 신경쓰지 않아도 되기 때문에 파이썬을 더욱 쉽게 만들어줍니다. 

이러한 특징은 단순히 파이썬 프로그램을 다른 컴퓨터에 복사해도 바로 작동이 되게 해주므로 여러분이 제작한 파이썬 프로그램을 Portable하게 만들어줍니다. 

### 객체지향 언어이다

Python supports procedure-oriented programming as well as object-oriented programming. In _procedure-oriented_ languages, the program is built around procedures or functions which are nothing but reusable pieces of programs. In _object-oriented_ languages, the program is built around objects which combine data and functionality. Python has a very powerful but simplistic way of doing OOP, especially when compared to big languages like C++ or Java.

> Python은 객제지향 프로그래밍을 잘 지원하는 만큼 절차지향 프로그래밍도 잘 지원합니다. _절차지향 언어_ 의 경우, 프로그램이 여러 절차들과 재사용이 가능한 프로그램의 일부 정도인 함수를 중심으로 만들어집니다. _객체지향 언어_ 의 경우, 프로그램은 데이터와 기능을 결합한 객체를 중심으로 만들어집니다. Python은 OOP(객체지향 프로그래밍)를 구현하는데 C++나 Java 같이 거대한 언어들과 비교해보았을 때 굉장히 강력하면서도 간단한 방법을 취합니다.

### Extensible

If you need a critical piece of code to run very fast or want to have some piece of algorithm not to be open, you can code that part of your program in C or C++ and then use it from your Python program.

### 이식성이 강하다.

You can embed Python within your C/C++ programs to give _scripting_ capabilities for your program's users.

> ?
> 여러분이 제작한 C 나  C++ 프로그램에 사용자를 위하여 _스크립팅 기능_ 을 추가해 파이썬 코드를 적용할 수 있습니다.

### 확장 라이브러리가 많다

The Python Standard Library is huge indeed. It can help you do various things involving regular expressions,documentation generation, unit testing, threading, databases, web browsers, CGI, FTP, email, XML, XML-RPC, HTML, WAV files, cryptography, GUI \(graphical user interfaces\), and other system-dependent stuff. Remember, all this is always available wherever Python is installed. This is called the _Batteries Included_ philosophy of Python.

Besides the standard library, there are various other high-quality libraries which you can find at the [Python Package Index](http://pypi.python.org/pypi).

> 파이썬의 기본 라이브러리는 엄청나게 거대합니다. 이렇게 거대한 라이브러리는 어러분이 정규식, 도큐멘테이션 생성기, 유닛 테스팅, 쓰레딩, 데이터베이스, 웹 브라우저, CGI, FTP, E-mail, XML, XML-RPC, HTML, WAV파일, 암호화, GUI \(graphical user interfaces\), 시스템 의존적 요소 등의 다양한 것들을 하는데 도움을 줄 수 있습니다. 이 모든 것을이 Python이 설치가 되어 있다면 항상 사용 가능하다는 것을 기억하세요. 이러한 것을 파이썬에서는 _Batteries Included_ 철학이라고 합니다. _(역주: 건전지가 들어가는 장난감을 샀을 때, 이미 건전지가 들어있다면 바로 사용할 수 있겠죠? 이러한 것을 의미합니다. [참고](https://www.quora.com/What-does-batteries-included-philosophy-mean))_

### 요약

Python is indeed an exciting and powerful language. It has the right combination of performance and features that make writing programs in Python both fun and easy.

> Python은 확실히 흥미로우면서도 강력한 언어입니다. Python은 성능과 프로그래밍을 재미있고 손쉽게 할 수 있는 특징들을 적절한 조합을 가지고 있습니다.

## Python 3 vs 2

You can ignore this section if you're not interested in the difference between "Python version 2" and "Python version 3". But please do be aware of which version you are using. This book is written for Python version 3.

Remember that once you have properly understood and learn to use one version, you can easily learn the differences and use the other one. The hard part is learning programming and understanding the basics of Python language itself. That is our goal in this book, and once you have achieved that goal, you can easily use Python 2 or Python 3 depending on your situation.

> 만약 "Python 2" 버전과 "Python 3" 버전의 차이점에 대해 관심이 없으시다면 이 섹션은 지나가셔도 좋습니다.
> 
> 둘 중 하나의 버전을 적절하게 이해했고 사용법을 배워두었다면, 다른 버전을 쉽게 배울 수 있고, 쉽게 사용할 수 있다는 것을 기억하세요. 프로그래밍을 배우고, 스스로 파이썬의 기초를 이해하는 부분이 어려운 부분입니다. (이러한 어려움을 극복하게 하는 것이)그것이 바로 이 책의 목표이며, 여러분이 이 목표를 이루었을 때, 여러분에 상황에 맞게 Python 2와 3 버전을 손쉽게 사용할 수 있게 될 것입니다.

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

