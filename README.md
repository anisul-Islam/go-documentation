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
  // a program for printing student details
  package main

  import "fmt"

  func main() {
    fmt.Println("Anisul Islam is a student")
    fmt.Println("Anisul Islam is 32 years old")
    fmt.Println("Anisul Islam has got 3.92/5 in SSC")
    fmt.Print("Anisul Islam originally from Bangladesh");
  }


  ```

- running the program
  - go mod init project-name
  - go run fileName.go

<h2> 5. Tokens - Escape sequences & comments </h2>

- Token of any programming language

  - keywords
  - data types
  - variables
  - Escapse sequences
  - operators

- escape sequences example

  ```go
    package main
    import "fmt"
    func main(){
      fmt.Print("Name \t Age\n")
      fmt.Print("----- \t ------\n")
      fmt.Print("Anis \t 32\n")
      fmt.Print("Rakib \t 29\n")
    }
  ```

- there are 2 types of comment is available in Go -> single line, multiple line comment. comments are ignored by the compiler.
  ```go
    // single line comment
    /*
      multiple
      line
      comment
    */
  ```

<h2> 6. Keywords & Data types </h2>

- keywords: keywords are reserved words.
  ![keywords](./images/keywords.png)
- Data types: boolean, string, numeric - integer, floating, derived types - pointer, array, structure, slice, map, interface etc.
- example of data types

  ```go
    "anisul islam" -> string type
    21 -> int type
    21.5 -> floating type
    true/false -> bool

    // more on int, float
    variation of integer-> int8 (8 bits), int16, int32, int64, uint8 (only positive 0 to 255), uint6, uint32, uint64

    variation of float-> float32, float64
  ```

<h2> 7. Variables </h2>

- syntax of variable declaration: var variable1, variable2, ... variableN dataType
- variable naming convention (camelcasing)
- example

  ```go
    package main
    import "fmt"
    func main(){
      // static variable declaration
      var name, country string
      var age int
      var gpa float32

      // variable initialization
      name = "anisul islam"
      country = "Bangladesh"
      age = 32
      gpa = 3.92

      // dynamic variable declaration + initialization
     //  var name = "Anisul Islam"
     //  var country = "Bangladesh"
     //  var age = 32
     //  var gpa = 3.92

     // var name,country,age,gpa = "anisul islam", "Bangladesh", 32, 3.92

     // shortcuts
     // name := "Anisul Islam"
     // country := "Bangladesh"
     // age := 32
     // cgpa := 3.92

      fmt.Println(name)
      fmt.Println(name, " is a student")
      fmt.Println(name,"is", age, "years old")
      fmt.Println(name, "has got" , gpa "/5 in SSC")
      fmt.Print(name,"originally from ", country);
    }


  ```

<h2> 8. Constants && Getting User Input </h2>

- Constants indicate to fix values

- example

  ```go
    package main
    import "fmt"
    func main(){
      const PI = 3.1416
      fmt.Println("pi = "pi)
    }
  ```

<h2> 9. Operators </h2>

- operator - symbol for doing calculation
- Types of operators

  - Arithmetic Operators -> +, -, \*, /, %
  - Assignment Operators -> =, +=, -=, \*=, /=, %=
  - Unary Operators -> ++, --
  - Relational Operators
  - Logical operators -> &&, ||, !
  - Bitwise operators -> &, |, ^
  - others -> , (comma), & (returns address), \* (pointer)

- example

  ```go
    package main
    import "fmt"
    func main(){
      const PI = 3.1416
      fmt.Println("pi = "pi)
    }
  ```

<h2> 10. Find the area of triangle / circle </h2>
<h2> 11. Calculator program </h2>
<h2> 12. Temperature converter </h2>
<h2> 13. if, else if, else control statement </h2>
<h2> 14. switch control statement </h2>
<h2> 15. Loop control statement </h2>
<h2> 16. Functions </h2>
