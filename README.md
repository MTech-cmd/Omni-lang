# What is this
This is a series of projects that I will try to solve in as many languages as possible.\
I won't solve every challenge in every language but I will try to.\
I will solve the first challenge (Hello) in every language.\

# TOC
- [List of languages](#the-languages)
- [The Challenges](#the-challenges)

## The languages
I have chosen these languages based on variety and personal preference. There is also a guide in this document on how to run these files.\
The languages are:
- [Assembly](#assembly)
- [Bash](#bash)
- [Brainfuck](#brainfuck)
- [C](#c)
- [C#](#c-1)
- [C++](#c-2)
- [COBOL](#cobol)
- [Dart](#dart)
- [Go!](#go)
- [Haskell](#haskell)
- [Haxe](#haxe)
- [HolyC](#holyc)
- [HTML](#html)
- [Java](#java)
- [JavaScript](#javascript)
- [Kotlin](#kotlin)
- [Lua](#lua)
- [Markdown](#markdown)
- [Perl](#perl)
- [PHP](#php)
- [PowerShell](#powershell)
- [Python](#python)
- [Ruby](#ruby)
- [Rust](#rust)
- [Swift](#swift)
- [TypeScript](#typescript)

Though I will most likely reduce the most important ones to:
- C++
- Haxe
- Kotlin
- TypeScript
- PHP
- Python

I must solve a challenge in all these in order to continue to the next.\
I will try to solve for the following languages as well though I will use cross-compilers (Like with Kotlin and Haxe) for these ones\
(yes this is an excuse to avoid JavaScript)

- C
- C#
- Dart
- Go!
- Java
- JavaScript
- Perl
- Ruby
- Rust
- Swift

## The Challenges
The challenges are in order of completion and difficulty and I will include the languages I managed to solve the challenge in. They are:
- [Hello](#hello)
- [Echo Echo](#echo-echo)
- [FizzBuzz](#fizzbuzz)
- [Calculator](#calculator)

### Hello
Print out the phrase 'Hello, X!' followed by a newline. Where X is equal to the program language you're solving for.\
So for Python it needs to print out the phrase 'Hello, Python!' in the terminal.\
For HTML it must display 'Hello, HTML!' in a browser. etc
Completion:

- Bash
- C
- C#
- C++
- Dart
- HTML
- Java
- JavaScript
- Markdown
- PHP
- Python
- TypeScript

### Echo Echo
Ask the user for input on the same line and display that input again on a newline.\

```
Input: This is Echo Echo for C#
Echo: This is Echo Echo for C#
```
Completion:
- NA

### FizzBuzz
Make a program that prints out the numbers 1 to 100 but replaces the number with 'Fizz' when dividable by 3, 'Buzz' when dividable by 5 and 'FizzBuzz' when divisable by both.\
DO NOT HARDCODE.
Completion:
- NA

### Calculator
Ask the user for a number, an operator and another number and print out the full equation on a newline.\
The following operators must be usable: + - * / % and if the user gives an invalid input it must terminate the program and display why.\
If the user tries to divide by 0 it must terminate the program and display why.
Completion:
- NA

### Assembly
WIP

### Bash
For Bash run any Bash or Zsh terminal, The standard for OS X and most LinuxGNU.

### Brainfuck
WIP

### C
For C use GCC and compile it to binaries using the following command:
```
gcc program.c -o program.out
```
Then you can execute the binaries using the following command:
```
./program.out
```

### C#
For C# use dotnet-sdk with the following command:
```
dotnet build
```
Now you can find the binaries in 
```
bin/Debug/net8.0/Program
```

### C++
For C++ use GCC and compile it to binaries using the following command:
```
g++ program.cpp -o program.out
```

### COBOL
WIP

### Dart
Install Dart and make a .dart file.\
Compile using the following command:
```
dart compile exe program.dart
```

### Go!
WIP

### Haskell
WIP

### Haxe
WIP

### HolyC
WIP

### HTML
Open the HTML file in Firefox or any browser.

### Java
Install jdk-openjdk and compile it to a Java Class using the following command:
```
javac Program.java
```
Create a manifest override file that contains meta-data for the Manifest Version, Created By and Main Class\
Compile to jar using the following command:
```
jar -cfm program.jar manifest-overrides.txt Program.class
```
Now you can run the program with:
```
java -jar program.jar
```

### JavaScript
Install Node and NPM.\
Through NPM install postject.\
Make a sea-config.json files containing data for the main and the output.\
Generate the blob with the following command:
```
node --experimental-sea-config sea-config.json
```
Copy the Node executable with the following command:
```
cp $(command -v node) program
```
Inject the blob into the executable using the following command:
```
npx postject program NODE_SEA_BLOB sea-prep.blob \ --sentinel-fuse NODE_SEA_FUSE_fce680ab2cc467b6e072b8b5df1996b2
```

### Kotlin
WIP

### Lua
WIP

### Markdown
Open the Markdown file in Typora or any Markdown viewer

### Perl
WIP

### PHP
Install PHP and run the script with the following command:
```
php program.php
```
Or add the following line to the top of the file to run the script automatically in Bash/Zsh:
```
#!/usr/bin/php
```

### PowerShell
WIP

### Python
Install python and use the following command:
```
python program.py
```
Or add the following line to the top of the file to run the script automatically in Bash/Zsh:
```
#!/usr/bin/env python
```

### Ruby
WIP

### Rust
WIP

### Swift
WIP

### TypeScript
Install Node and NPM.\
Through NPM install postject and typescript.\
Compile the ts file to js with the following command:
```
tsc program.ts
```
Make a sea-config.json files containing data for the main (program.js) and the output(sea-prep.blob).\
Generate the blob with the following command:
```
node --experimental-sea-config sea-config.json
```
Copy the Node executable with the following command:
```
cp $(command -v node) program
```
Inject the blob into the executable using the following command:
```
npx postject program NODE_SEA_BLOB sea-prep.blob \ --sentinel-fuse NODE_SEA_FUSE_fce680ab2cc467b6e072b8b5df1996b2
```

### Bonus
As a bonus you can always compile them to the closest binaries and away from the source code (and make a run script for both) and make a program that checks whether your program actually works.