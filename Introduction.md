# Introduction

- Go is mostly based on C language but influenced by other languages like C++ and C#.
- Go depends on some OOPs concept

    - Encapsulation  with types and structs, wrapers for complex functionality
    - Polymorphism : with interfaces
    - No type inheritence.

- Go is compiled language

    - Statically typed lang
    - no need to explicitely declare type
    - Feels like interpreted lang
    - No need to pre compile for running code
    - in background application is being compiled to temperory executable (OS specific executable)
    - applicaitons have Statically linked runtime. Runtime component being built while compiling. Hence size of compiled file is much larger than source file.
    - No external virtual machine.

        - e.g Java has OS specific VM
    
- Langugae is object oriented

    - Custom interface is possible
    - Custom types can implement one or more interfaces
    - Custom struct can have member fields

- No type inheretence

    - no operetor or method overloading
    - structured exception handling is not there e.g. try catch,
        - error object returns by method
    - Explicit type conversion is required to required type

- Essential Sytax Rules
    -
    - Go is case sensitive
    - Initial upper case character, means: that field or method is available for the rest of the application.
    - Initial lower case character, means: not available to the rest of the application
    - No semicolon is required
    - Codes are wrapped with braces
    - Starting brace should be on the same line as preceding statement

- Other critical charact
    - 
    - Built-in functions and members which doesn't required to import any header file
    e.g. len(string), panic(error), recover()



