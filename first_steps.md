# First Steps

We will now see how to run a traditional 'Hello World' program in Python. This will teach you how to write, save and run Python programs.

There are two ways of using Python to run your program - using the interactive interpreter prompt or using a source file. We will now see how to use both of these methods.

## Using The Interpreter Prompt

Open the terminal in your operating system (as discussed previously in the [Installation](./installation.md#installation) chapter) and then open the Python prompt by typing `python3` and pressing `[enter]` key.

Once you have started Python, you should see `>>>` where you can start typing stuff. This is called the _Python interpreter prompt_.

At the Python interpreter prompt, type:

```python
print("Hello World")
```

followed by the `[enter]` key. You should see the words `Hello World` printed to the screen.

Here is an example of what you should be seeing, when using a Mac OS X computer. The details about the Python software will differ based on your computer, but the part from the prompt (i.e. from `>>>` onwards) should be the same regardless of the operating system.

<!-- The output should match pythonVersion variable in book.json -->
```python
$ python3
Python 3.6.0 (default, Jan 12 2017, 11:26:36)
[GCC 4.2.1 Compatible Apple LLVM 8.0.0 (clang-800.0.38)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello World")
Hello World
```

Notice that Python gives you the output of the line immediately! What you just entered is a single Python _statement_. We use `print` to (unsurprisingly) print any value that you supply to it. Here, we are supplying the text `Hello World` and this is promptly printed to the screen.

> 파이썬이 입력한 파이썬 코드(_statement_)를 바로 결고로 보여준다는 점을 확인하세요! 우리는 `print` 문으로 어떠한 값이든 화면에 출력할 수 있습니다. 위의 코드에서 `Hello World` 를 우리가 작성해주었고, 이를 파이썬이 화면에 바로 띄어주게 됩니다.

### How to Quit the Interpreter Prompt

If you are using a GNU/Linux or OS X shell, you can exit the interpreter prompt by pressing `[ctrl + d]` or entering `exit()` (note: remember to include the parentheses, `()`) followed by the `[enter]` key.

If you are using the Windows command prompt, press `[ctrl + z]` followed by the `[enter]` key.
 
## Choosing An Editor
> 코드 편집기 선택하기 

We cannot type out our program at the interpreter prompt every time we want to run something, so we have to save them in files and can run our programs any number of times.

> 우리가 프로그램의 만들고 동작시킬 때 한줄씩 매번 프로그램 코드(interpreter prompt)를 작성할 수는 없습니다. 그래서 우리는 이러한 명령줄을 파일에 저장하여 원하는 만큼 프로그램을 실행시킬 수 있도록 해야 합니다.

To create our Python source files, we need an editor software where you can type and save. A good programmer's editor will make your life easier in writing the source files. Hence, the choice of an editor is crucial indeed. You have to choose an editor as you would choose a car you would buy. A good editor will help you write Python programs easily, making your journey more comfortable and helps you reach your destination (achieve your goal) in a much faster and safer way.

> 파이썬 소스 코드 파일을 생성할 때, 우리는 프로그램 코드를 작성하고 저장할 수 있는 편집기 소프트웨어가 필요합니다. 좋은 코드 편집기를 사용한다면 코드를 작성할 때 우리를 편하게 해줄 것입니다. 그러므로 코드 편집기를 고르는 것은 굉장히 중요한 부분이라고 할 수 있습니다. 우리는 편집기를 살 차리를 고르는 것처럼 골라야 합니다. 좋은 코드 편집기는 파이썬 코드를 쉽게 짤 수 있도록 해주고, 코드를 작성하는 과정을 편하게 해줄 것이며, 우리가 목표로 하는 프로그램을 완성시킬 때까지 빠르고 안전한 길로 이끌어주도록 도와줄 것입니다.

One of the very basic requirements is _syntax highlighting_ where all the different parts of your Python program are colorized so that you can _see_ your program and visualize its running.

> 문법 하이라이팅(syntax hightlighting) 기능은 가장 기본적인 기능 중 하나입니다. 이 기능은 파이썬 프로그램을 각각의 요소마다 색을 다라게 표현하여 코드를 알록달록하게 만들어주는데, 이로 인해 우리는 코드를 한눈에 이해할 수 있도록 도와줍니다.

If you have no idea where to start, I would recommend using [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) software which is available on Windows, Mac OS X and GNU/Linux. Details in the next section.

> 만약 어떤 코드 편집기를 써야 할지 모르겠다면, [PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/)을 사용해볼 것을 추천해드립니다. PyCharm은 Windows, macOS, Linux에서 사용할 수 있습니다. 다음 섹션에서 자세히 알아보도록 하겠습니다.

If you are using Windows, *do not use Notepad* - it is a bad choice because it does not do syntax highlighting and also importantly it does not support indentation of the text which is very important in our case as we will see later. Good editors will automatically do this.

> 만약 Windows를 운영체제로 사용한다면, 메모장(_notepad_)을 **절.대.로. 사용하지 마세요.** 메모장은 문법 하이라이팅 기능도 없으며 나중에 자세히 알아보게될 자동 들여쓰기(indentation) 기능도 지원하지 않습니다. 좋은 코드 편집기들은 이러한 기능들을 모두 지원합니다.

If you are an experienced programmer, then you must be already using [Vim](http://www.vim.org) or [Emacs](http://www.gnu.org/software/emacs/). Needless to say, these are two of the most powerful editors and you will benefit from using them to write your Python programs. I personally use both for most of my programs, and have even written an [entire book on Vim]({{ book.vimBookUrl }}).

> 만약 프로그래밍에 경험이 있으시다면, 이미 [Vim](http://www.vim.org)이나 [Emacs](http://www.gnu.org/software/emacs/)를 사용하고 계실거라 생각합니다. 두말할 필요도 없이 이 코드 편집기들은 엄청나게 강력한 기능을 제공하는 편집기이며 파이썬 코드를 작성할 때 이점이 될 것입니다. 제 개인적으로 위 두 개의 편집기를 가장 많이 사용하고 있고, [책도 Vim으로 전부 작성하고 있습니다]({{ book.vimBookUrl }}).

In case you are willing to take the time to learn Vim or Emacs, then I highly recommend that you do learn to use either of them as it will be very useful for you in the long run. However, as I mentioned before, beginners can start with PyCharm and focus the learning on Python rather than the editor at this moment.

> 만약 Vim이나 Emacs를 배울 시간이 있으시다면, 저는 길게봤을 때, 두 편집기 모두 굉장히 유용하므로 배우는 것을 강력하게 추천합니다. 그러나 전에도 언급했듯이 처음 시작하시는 분들은 PyCharm으로 시작하면서 파이썬을 배우는 것에 지금 당장은 초점을 둘 수 있도록 합니다.

To reiterate, please choose a proper editor - it can make writing Python programs more fun and easy.

> 다시 말씀드리지만, 파이썬 프로그램을 재미있고 쉽게 만들 수 있도록 자신에게 적절한 편집기를 선택하도록 합니다.

## PyCharm {#pycharm}

[PyCharm Educational Edition](https://www.jetbrains.com/pycharm-edu/) is a free editor which you can use for writing Python programs.

When you open PyCharm, you'll see this, click on `Create New Project`:

![When you open PyCharm](./img/pycharm_open.png)

Select `Pure Python`:

![PyCharm New Project](./img/pycharm_create_new_project.png)

Change `untitled` to `helloworld` as the location of the project, you should see details similar to this:

![PyCharm project details](./img/pycharm_create_new_project_pure_python.png)

Click the `Create` button.

Right-click on the `helloworld` in the sidebar and select `New` -> `Python File`:

![PyCharm -> New -> Python File](./img/pycharm_new_python_file.png)

You will be asked to type the name, type `hello`:

![PyCharm New File dialog box](./img/pycharm_new_file_input.png)

You can now see a file opened for you:

![PyCharm hello.py file](./img/pycharm_hello_open.png)

Delete the lines that are already present, and now type the following:

<!-- TODO: Update screenshots for Python 3 -->

```python
print("hello world")
```
Now right-click on what you typed (without selecting the text), and click on `Run 'hello'`.

![PyCharm Run 'hello'](./img/pycharm_run.png)

You should now see the output (what it prints) of your program:

![PyCharm output](./img/pycharm_output.png)

Phew! That was quite a few steps to get started, but henceforth, every time we ask you to create a new file, remember to just right-click on `helloworld` on the left -> `New` -> `Python File` and continue the same steps to type and run as shown above.

> 지금까지 프로그램을 만들기 위한 단계를 거쳐보았습니다. 그러나 지금부터는 새로운 파일을 생성할 때, `helloworld` 오른쪽 클릭 후 :arrow_right: `New` :arrow_right: `Python File` 을 클릭한 후, 위에서 보여드린 방법대로 동일하게 진행하는 방법을 꼭 기억하세요.

You can find more information about PyCharm in the [PyCharm Quickstart](https://www.jetbrains.com/pycharm-educational/quickstart/) page.

> PyCharm에 대한 자세한 정보는 [PyCharm Quickstart](https://www.jetbrains.com/pycharm-educational/quickstart/) 페이지에서 찾아보실 수 있습니다.

## Vim

> Vim 설치하기

1. Install [Vim](http://www.vim.org)
    * Mac OS X users should install `macvim` package via [HomeBrew](http://brew.sh/)
    * Windows users should download the "self-installing executable" from [Vim website](http://www.vim.org/download.php)
    * GNU/Linux users should get Vim from their distribution's software repositories, e.g. Debian and Ubuntu users can install the `vim` package.
2. Install [jedi-vim](https://github.com/davidhalter/jedi-vim) plugin for autocompletion.
3. Install corresponding `jedi` python package : `pip install -U jedi`

> 1. 먼저 [Vim](http://www.vim.org)을 설치하세요.
>   * macOS를 사용하고 계신다면, [HomeBrew](http://brew.sh/)로 `macvim`을 설치해야 합니다.
>   * Windows를 사용하신다면, [Vim website](http://www.vim.org/download.php)에서 "self-installing executable" 문서?파일?을 다운받으셔야 합니다.

## Emacs

1. Install [Emacs 24+](http://www.gnu.org/software/emacs/).
    * Mac OS X users should get Emacs from http://emacsformacosx.com
    * Windows users should get Emacs from http://ftp.gnu.org/gnu/emacs/windows/
    * GNU/Linux users should get Emacs from their distribution's software repositories, e.g. Debian and Ubuntu users can install the `emacs24` package.
2. Install [ELPY](https://github.com/jorgenschaefer/elpy/wiki)

## Using A Source File

Now let's get back to programming. There is a tradition that whenever you learn a new programming language, the first program that you write and run is the 'Hello World' program - all it does is just say 'Hello World' when you run it. As Simon Cozens[^1] says, it is the "traditional incantation to the programming gods to help you learn the language better."

Start your choice of editor, enter the following program and save it as `hello.py`.

If you are using PyCharm, we have already [discussed how to run from a source file](#pycharm).

For other editors, open a new file `hello.py` and type this:

```python
print("hello world")
```

Where should you save the file? To any folder for which you know the location of the folder. If you
don't understand what that means, create a new folder and use that location to save and run all
your Python programs:

- `/tmp/py` on Mac OS X
- `/tmp/py` on GNU/Linux
- `C:\py` on Windows

To create the above folder (for the operating system you are using), use the `mkdir` command in the terminal, for example, `mkdir /tmp/py`.

IMPORTANT: Always ensure that you give it the file extension of `.py`, for example, `foo.py`.

To run your Python program:

1. Open a terminal window (see the previous [Installation](./installation.md#installation) chapter on how to do that)
2. **C**hange **d**irectory to where you saved the file, for example, `cd /tmp/py`
3. Run the program by entering the command `python hello.py`. The output is as shown below.

```
$ python hello.py
hello world
```

![Screenshot of running program in terminal](./img/terminal_screenshot.png)

If you got the output as shown above, congratulations! - you have successfully run your first Python program. You have successfully crossed the hardest part of learning programming, which is, getting started with your first program!

In case you got an error, please type the above program _exactly_ as shown above and run the program again. Note that Python is case-sensitive i.e. `print` is not the same as `Print` - note the lowercase `p` in the former and the uppercase `P` in the latter. Also, ensure there are no spaces or tabs before the first character in each line - we will see [why this is important](./basics.md#indentation) later.

**How It Works**

A Python program is composed of _statements_. In our first program, we have only one statement. In this statement, we call the `print` _statement_ to which we supply the text "hello world".

## Getting Help

If you need quick information about any function or statement in Python, then you can use the built-in `help` functionality. This is very useful especially when using the interpreter prompt. For example, run `help('len')` - this displays the help for the `len` function which is used to count number of items.

TIP: Press `q` to exit the help.

Similarly, you can obtain information about almost anything in Python. Use `help()` to learn more about using `help` itself!

In case you need to get help for operators like `return`, then you need to put those inside quotes such as `help('return')` so that Python doesn't get confused on what we're trying to do.

## Summary

You should now be able to write, save and run Python programs at ease.

Now that you are a Python user, let's learn some more Python concepts.

---

[^1]: the author of the amazing 'Beginning Perl' book
