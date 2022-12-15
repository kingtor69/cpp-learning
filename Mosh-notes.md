# *Let’s parlez C++*
## [C++ Tutorial for Beginners – Learn C++ in 1 Hour](https://youtu.be/ZzaPdXTrSb8)
### Section 0: introductions
#### Popular IDEs
* yeah, that's an "integrated development environment," like `venv` for Python or `npm` for Node (I think)
  * MS Visual Studio (not as good on mac)
  * XCode (Apple App store)
  * [CLion](https://jetbrains.com/clion/download/#section=mac) (I'm using free 30 day trial for now since it’s what he’s using, but will probably switch to XCode l8r)

#### First app: `./CLionProjects/FirstProject/`
* C++ 20 is LTS at least as of his video (there is a C++ 23 in his and in mine, but he says it’s not "official" yet)
* this will generate 
  * `./CLionProjects/FirstProject/CMakeSList.txt` which we don’t need, at least not yet
  * and `./CLionProjects/FirstProject/main.cpp` which comes prepopulated with some stuff, but which we’re also going to write from scratch
* C++ is case-sensitive
* started with a function called `main` with 0 parameters (arguments, whatever) and outputting an integer, so it looks like this:
  ```
  int main () {

  }
  ```
  * number of spaces in an indent doesn’t matter
  * left curly-bracket can be on the next line (all the way left)
* `#include <iostream>` above that is loading a dependency from the C++ standard library
* then `std::cout << "Whatever";` displays a string (the c in cout is for character) onscreen
* and `return 0;` is like NodeJS in that 0 means the program ran properly and any other number is an error`
* **the semicolon seems more important than it is in JS**
  * yup, can confirm. It throws an error on compiling
  * BTW, CLion doesn’t work well in vertical.

this is super-slow, so I’m checking in to whether I can do it in VS Code, starting with `C/C++ Extension Pack`

#### compiling
* this is the real deal, compiling to a `.exe` file (or so he says, but I'm not entirely sure what it creates on the Mac version of CLion)
* I haven’t found a way to compile it in VSCode, but I think there is a way, for now, though, I can write in VSCode and it updates in the C++ app here I can run the program with `^R`

#### skipped over theme/appearance stuff in CLion since I’m not going to stick with it
#### course overview:
1. Basics (this video):
   * fundamentals of programming
   * data types
   * decision making statements
   * loops
   * functions 
2. Intermediate:
   * Arrays
   * Pointers
   * Strings
   * Structures
   * Enumerations
   * Streams
3. Advanced:
   * Classes
   * Exceptions
   * Templates
   * Containers
   * and more!

#### [PDF cheat sheet and summary notes](./Ultimate-C-Part-1.pdf)

butt first, before moving on to Section I, I'm downloading Xcode 11.7 so I can compile in VSCode, which I'm sure will be better

### Section I: The Basics
