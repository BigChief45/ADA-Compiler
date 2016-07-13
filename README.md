# Ada Compiler

This program is the 1st stage of an Ada Compiler written in Java. It implements some Java libraries such as [JFlex](http://jflex.de/) (for lexical analysis) and [JavaCup](http://www2.cs.tum.edu/projects/cup/) for defining the language grammars.

This program uses a very basic GUI where you can type in Ada code and save the file to the file system. Once it is saved, it can be processed for analysis by clicking the "Compile" button.

![GUI](https://raw.githubusercontent.com/BigChief45/ADA-Compiler/master/screenshots/gui.jpeg)

**Files must be saved before being compiled**

## Example Ada Code

Below is a basic example code in Ada. More examples can be found in the [Ada Wikipedia page](https://en.wikipedia.org/wiki/Ada_(programming_language)).

```ada
procedure Example is
begin
  a := 10;
end Example;
```
