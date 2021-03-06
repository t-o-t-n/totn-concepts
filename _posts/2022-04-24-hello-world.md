---
layout: post
title: 'Hello, World Program in C++'
---

# First Hello World Program in C++

The first **Hello, World** Program is special for everyone out there! 😄

Today we are gonna be writing the **Hello, World!** program in C++.

I know you must be expecting something more advanced here, but since this is gonna be my first post in TOTN concepts, I am gonna start with this Hello World program itself. ✅

## Create a new file called hello_world.cpp

Just right click in the left pane of the VS Code editor and click on the `New File` option.

This should create a new file for you. You can put the name of the file to be **hello_world.cpp**

## Declare the Header files first.

The very first step that you need to make sure is that the **required header file to run the program are present in the code.**

Because if they aren't present, then your code is gonna throw an error!

Add the below 2 lines to your code.

```cpp
#include <iostream>
using namespace std;
```

## Define the main() function.

This can be called the **Entry point of the program**.

You can define the statements in the order in which they need to be processed.

Now, since our requirement is just a plain Hello World display to the user. We just need to put a `printf` statement or a `cout` statement in the code, along with the string that we want to print.

```cpp
int main() {
    cout << "Hello, World!" << endl;
}
```

That's it. We are done with **our First C++ Hello World program!**

You just need to compile it and run it using.

```bash
g++ hello_world.cpp
```

And execute it using -

```bash
./a.exe
```

If you are on a MacOS or Ubuntu kinda system, then the executable generated would be **./a.out**

You can run that using -

```bash
g++ hello_world.cpp
./a.out
```

If you do not want to type two commands everytime you compile and run your code. You can do something like -

```bash
g++ hello_world.cpp && ./a.exe
```

That's it! We are done with the very first Hello, World program.

Thanks for seeing this simple program! See you in the next. 😉
