# Lesson 1 - Introduction to Computer Science

### Section 1:  What is computer science? Why learn computer science?
> Computer science is the study of computation, automation, and information. ([Wikipedia](https://en.wikipedia.org/wiki/Computer_science "Wikipedia"))

Computer science initially started in the 1960s.  Computer science was made to be able to automate mathematical calculations previously calculated by humans. In this course, you'll learn the basics of computer science and be able to use these basics to code in C++. Hopefully by the end of this course you will be able to compete in competitions such as [USACO](http://usaco.org "USACO"), [Codeforces](https://codeforces.com/ "Codeforces"), [Teamscode](http://Teamscode "Teamscode"), and etc. This course might require a basic understanding of math so be prepared. Yeah.

### Section 2: Datatypes
> Datatypes are by far the most important part of any coding language.

In a language, we always want to store our data some way or another. The best way to do this is using a datatype; or SQL (or any other database) if you're running something like a website. C++ has a datatypes, such as int (for numbers), char (for characters), string (for strings, like sentences and words), bool (for true or false values), and many more. However, most of these other datatypes are based on the main 4: bool, char, string, and int. *You can think of datatypes as a container.*
<img src="Pictures\DatatypeDrawing1.jpg" class="img-responsive" alt="Datatype Drawing">

Checkout my github repo on how to find any datatypes size [here](https://github.com/Streakwind/CppDatatypeSize "here")!

Using datatypes, we can create variables. This will be discussed later.
For right now though, just know that a variable is defined like this.

<img src="Pictures\variableDrawing1" class="img-responsive" alt="Variable drawing">

Note: `//` declares a comment. Comments are only for clarity and the compiler does not read it.
````cpp
int myInt = 0; //int = integer
string myStr = "Hi!" //str = string, word, character, sentence, paragraph, essay... yeah
bool myBool = true //true or false?
char myChar = '!' //char = character
````
Finish sections 1 & 2s quiz in the quiz folder.

### Section 3: Setting up your first C++ code
Read the comments!
```cpp
//I was taught to add these two lines... add it for clarity, it looks pretty :)

#include <iostream>
//add this line please, clarity
using namespace std; //so you don't need to do std::cout, pain
//this line too! clarity
int main () { //this method is always read by the compiler
string myStr = "Hello!" //can be defined like this
myStr = "Hello, world!" //goes from "Hello!" to "Hello, world!"

cout << "Hello, world!" << endl //c-out -> console-out; endl->endline
cout << "->" << myStr << endl; //ouput: ->Hello, world!

return 0; //return this if the compiler succesfully ran through the code
}
```
And it's that simple!

Finish Section 3s quiz in the quiz folder.
