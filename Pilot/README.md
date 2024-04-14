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
- [Pascal](#pascal)
- [Perl](#perl)
- [PHP](#php)
- [PowerShell](#powershell)
- [Python](#python)
- [Ruby](#ruby)
- [Rust](#rust)
- [Swift](#swift)
- [TypeScript](#typescript)

### The Challenge
Print out the phrase 'Hello, X!' followed by a newline. Where X is equal to the program language you're solving for.\
So for Python it needs to print out the phrase 'Hello, Python!' in the terminal.\
For HTML it must display 'Hello, HTML!' in a browser. etc
Completion:

- Bash
- C
- C#
- C++
- Dart
- Go!
- Haxe
- HTML
- Java
- JavaScript
- Markdown
- PHP
- Python
- TypeScript

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
Install Go!.\
Make a new go mod with the following command:
```
go mod init program
```
Make a .go file.\
Compile with the following command:
```
go build -o program program.go
```

### Haskell
WIP

### Haxe
Install Haxe and haxelib.\
Use haxelib to install hxcpp with the following command:
```
haxelib install hxcpp
```
make a build.hxml file with a main argument and a cpp argument
Use the following command:
```
haxe build.hxml
```

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

## Pascal
WIP

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