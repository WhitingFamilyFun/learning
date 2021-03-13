# Programming Basics

There are many different languages you can use to code. I'm going to be teaching you one of my favorites called Dart. It is an easy language to learn, and it also makes it easy to make web apps, Android, iOS, Windows, Linux, and macOS apps.

This is one of the most simple programs that you can write in Dart.

## Example 1:
```dart
main() {
   print('hello');
}
```
All programs start somewhere, and run a set of instructions one at a time, until the program finishes.

The first bit creates a `function` called `main`.
A function is a way to combine a sequence of instructions into one instruction.

This function called `main` is the first instruction that runs in any program.

A function consists of a name then a set of parentheses and then an open and closing brace.

## Example 2:
```dart
aFunctionName() {}
```

In Dart all names have to start with a letter or underscore, and can only contain letters, underscores, and numbers.

Usually names start with a lowercase letter, and since you can't use spaces programmers usually separate the words with uppercase letters for each new word.

## Example 3:
```dart
aNameSeparatedByUppercaseLetters1234
```

Typically we keep names shorter, but they should be descriptive or easy to understand.

Functions have both inputs and an output. Simple functions don't have any inputs or outputs.
The function `main` is simple like that.

All programs manipulate data in some way:

Data in programs is made up of a many different types.
The most simple are letters and numbers

* Numbers can be of two different types:
   * `int` an integer 
   * `double` numbers with decimal places
* A sequence of letters is called a `String`
   
The function `print` that we saw in Example 1 takes an input and outputs it, the input can be of any type.

To run a Dart program write or copy the code from Example 1 into a file in VSCode. Just above the `main` function will pop up a link to run the program. When you click that button it should open a tab along the bottom called the `Debug Console`. You will see the output of the program down there. For example 1 you will see `hello`.


You can alternately go to [www.dartpad.dev](www.dartpad.dev) to try running it in your browser. However,
for app development, I highly recommend running it on your computer.
For information on how to install the tools and apps you need to use Dart go [here](INSTALL.md)

