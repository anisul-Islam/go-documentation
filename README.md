# Go Programming Tutorial

<h2> 1. Introduction to Go Programming </h2>

- What is Go?

  - Simple but fast, popular programming language for cloud engineering
  - statically typed, compiled programming language
  - Developed by google in 2007
  - Open sourced in 2009
  - Often known as golang
  - Syntax has similarity with C,C++
  - Mainly used as a server side or backend language
  - Supports cross-os

- Why Go?

  - For making simple, reliable and efficient computer program/software
  - Helps to create high performance applications but use less resources
  - It helps to write concurrent multithread programs

- Prerequisities

  - Nothing, but knowing C/C++ or any programming language is an advantage

<h2> 2. Go Program structure </h2>

- package declaration - every go program is consist of packages. it is a mandatory thing. it has to be the first statement of go program.
- import packages
- function
- statement

```go
  // main.go
  package main

  import “fmt”

  func main() {

    fmt.Println(“My name is Anisul Islam”)

  }

  output: My name is Anisul Islam

```

<h2> 3. Environment setup </h2>

- IDE / Text Editor -> Any text editor- notepad / notepad++ / VSCode (free), Vim (free) / GoLand (paid)
- Go compiler -> compiler translate the source code into machine/executable code so that machine can understand the instructions
- go extension for VSCode

<h2> 4. First Go Program </h2>

- A simple go program

  ```go
  // filename: main.go
  // a program for printing your details
  package main

  import "fmt"

  func main() {
    fmt.Println("My name is Anisul Islam")
    fmt.Println("I am 32 years old")
    fmt.Print("I am from Bangladesh");
  }


  ```

- running the program
  - go mod init project-name
  - go run fileName.go
- there are 2 types of comment is available in Go -> single line, multiple line comment. comments are ignored by the compiler.
  ```go
    // single line comment
    /*
      multiple
      line
      comment
    */
  ```

<h2> 5. Keywords & Data types </h2>

- Token of any programming language

  - keywords
  - variables
  - data types
  - operators

- keywords: keywords are reserved words.
  <img src="./images/kewords.png">
- Data types:
