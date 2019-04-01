# Documentation

[en]  
The Go programming language is an open source project to make programmers more productive.  

[jp]  
Goプログラミング言語は、プログラマーたちの生産性を上げるためのオープンソースプロジェクトです。  

[en]  
Go is expressive, concise, clean, and efficient. Its concurrency mechanisms make it easy to write programs that get the most out of multicore and networked machines, while its novel type system enables flexible and modular program construction.　 

[jp]  
Goは表現力が豊かで、簡潔で、綺麗そして効率的です。並行処理メカニズムにより、マルチコアやネットワークマシンを最大限に活用するプログラムを簡単に書けます。また、その革新的な型システムにより、柔軟でモジュール式のプログラム構築が可能になります。　　

[en]  
Go compiles quickly to machine code yet has the convenience of garbage collection and the power of run-time reflection.  

[jp]  
Goはマシンコードにすばやくコンパイルしますが、ガベージコレクションの便利さとランタイムリフレクションの機能もあります。   

[en]  
It's a fast, statically typed, compiled language that feels like a dynamically typed, interpreted language.  

[jp]  
それは静的型付けのように早いコンパイル言語で、動的型付けを解釈した言語のようにコンパイル言語、高速で静的に型付けされコンパイルされた言語です。　　

## Installing Go

### [Getting Started](./install/)  

[en]  
Instructions for downloading and installing the Go compilers, tools, and libraries.  

[jp]  
Goコンパイラやツール、ライブラリたちをダウンロードしてインストールする説明書。  

## Learning Go

### A Tour of Go [[en](https://tour.golang.org/)][[jp](https://go-tour-jp.appspot.com/)]

[en]  
An interactive introduction to Go in three sections.   

[jp]  

[en]  
The first section covers basic syntax and data structures; the second discusses methods and interfaces; and the third introduces Go's concurrency primitives.   

[jp]  

[en]  
Each section concludes with a few exercises so you can practice what you've learned.   

[jp]  

[en]  
You can take the tour online or install it locally with:  

```
$ go get golang.org/x/tour
```

[jp]  

```
$ go get golang.org/x/tour
```

[en]  
This will place the tour binary in your workspace's bin directory.  

[jp]  


### How to write Go code 

[en]  
Also available as a screencast, this doc explains how to use the go command to fetch, build, and install packages, commands, and run tests.  

[jp]  


### Editor plugins and IDEs

[en]  
A document that summarizes commonly used editor plugins and IDEs with Go support.  

[jp]  


### Effective Go

[en]  
A document that gives tips for writing clear, idiomatic Go code.  

[jp]  

[en]  
A must read for any new Go programmer.   

[jp]  


[en]  
It augments the tour and the language specification, both of which should be read first.  

[jp]  



### Diagnostics

[en]  
Summarizes tools and methodologies to diagnose problems in Go programs.  

[jp]  


### Frequently Asked Questions (FAQ) 

[en]  
Answers to common questions about Go.  

[jp]  


### The Go Wiki

[en]  
A wiki maintained by the Go community.  

[jp]  


#### More

[en]  
See the Learn page at the Wiki for more Go learning resources.  

[jp]  


## References 

### Package Documentation 

[en]  
The documentation for the Go standard library.  

[jp]  

### Command Documentation

[en]  
The documentation for the Go tools.  

[jp]  

### Language Specification

[en]  
The official Go Language specification.  

[jp]  

### The Go Memory Model

[en]  
A document that specifies the conditions under which reads of a variable in one goroutine can be guaranteed to observe values produced by writes to the same variable in a different goroutine.  

[jp]  

### Release History

[en]  
A summary of the changes between Go releases.  

[jp]  

## Articles

### The Go Blog

[en]  
The official blog of the Go project, featuring news and in-depth articles by the Go team and guests.  

[jp]  

#### Codewalks

[en]  
Guided tours of Go programs.  

- First-Class Functions in Go  
- Generating arbitrary text: a Markov chain algorithm  
- Share Memory by Communicating  
- Writing Web Applications - building a simple web application.  

[jp]  


#### Language

[en]  
- JSON-RPC: a tale of interfaces
- Go's Declaration Syntax
- Defer, Panic, and Recover
- Go Concurrency Patterns: Timing out, moving on
- Go Slices: usage and internals
- A GIF decoder: an exercise in Go interfaces
- Error Handling and Go
- Organizing Go code

[jp]  


#### Packages

[en]  
- JSON and Go - using the json package.
- Gobs of data - the design and use of the gob package.
- The Laws of Reflection - the fundamentals of the reflect package.
- The Go image package - the fundamentals of the image package.
- The Go image/draw package - the fundamentals of the image/draw package.

[jp]  

#### Tools

[en]  
- About the Go command - why we wrote it, what it is, what it's not, and how to use it.
- Debugging Go Code with GDB
- Data Race Detector - a manual for the data race detector.
- A Quick Guide to Go's Assembler - an introduction to the assembler used by Go.
- C? Go? Cgo! - linking against C code with cgo.
- Godoc: documenting Go code - writing good documentation for godoc.
- Profiling Go Programs
- Introducing the Go Race Detector - an introduction to the race detector.

[jp]  

#### More

[en]  
See the Articles page at the Wiki for more Go articles.

[jp]  

## Talks

### A Video Tour of Go

[en]  
Three things that make Go fast, fun, and productive: interfaces, reflection, and concurrency. 

[jp]  


[en]  
Builds a toy web crawler to demonstrate these.

[jp]  


### Code that grows with grace


[en]  
One of Go's key design goals is code adaptability; that it should be easy to take a simple design and build upon it in a clean and natural way. 

[jp]  


[en]  
In this talk Andrew Gerrand describes a simple "chat roulette" server that matches pairs of incoming TCP connections, and then use Go's concurrency mechanisms, interfaces, and standard library to extend it with a web interface and other features. 

[jp]  

[en]  
While the function of the program changes dramatically, Go's flexibility preserves the original design as it grows.

[jp]  


### Go Concurrency Patterns

[en]  
Concurrency is the key to designing high performance network services. 

[jp]  


[en]  
Go's concurrency primitives (goroutines and channels) provide a simple and efficient means of expressing concurrent execution. 

[jp]  


[en]  
In this talk we see how tricky concurrency problems can be solved gracefully with simple Go code.


[jp]  


### Advanced Go Concurrency Patterns

[en]  
This talk expands on the Go Concurrency Patterns talk to dive deeper into Go's concurrency primitives.

[jp]  


#### More

[en]  
See the Go Talks site and wiki page for more Go talks.

[jp]  


## Non-English Documentation

[en]  
See the NonEnglish page at the Wiki for localized documentation.

[jp]  
