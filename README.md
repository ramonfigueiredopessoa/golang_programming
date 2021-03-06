Some programming examples in Golang
===========================

## Contents
1. [Run or compile or install golang code](#run-or-compile-or-install-golang-code)
2. [Hello, World](#hello-world)
3. [Variables](#variables)
4. [Conditional](#conditional)
5. [Arrays](#arrays)
6. [Loops](#loops)
7. [Functions](#functions)
8. [Structs](#structs)
9. [Pointers](#pointers)
10. [Solutions for coding problems](#solutions-for-coding-problems)

## Run or compile or install Golang code

To install Golang in MacOS using homebrew (https://brew.sh/)
```sh
brew install go
```

To show to golang workspace
```sh
go env GOPATH

Output (example)
/Users/ramonpessoa/go
```

To run golang code (interpreter)
```sh
go run hello.go
```

To build and run golang code (Linux and MacOS)
```sh
go build hello.go
./variables
```

To build and run golang code (Windows)
```sh
go build hello.go
variables.exe
```

To install golang code (inside the folder bin. For example, inside the /Users/ramonpessoa/go/bin folder)
```sh
cd /Users/ramonpessoa/go/src/variables
go install
cd /Users/ramonpessoa/go/bin
./variables
```

## Hello World

1. Hello World program

	Solution (Golang): [hello_world.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/hello_world/hello.go)

## Variables

1. Variables

	Solution (Golang): [variables.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/variables/variables.go)

## Conditional

1. if, if else, else

	Solution (Golang): [if_ifelse_else.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/conditional/if_ifelse_else.go)

## Arrays

1. Arrays

	Solution (Golang): [arrays.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/arrays/arrays.go)

## Loops

1. Loops

	Solution (Golang): [loops.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/loops/loops.go)

## Functions

1. Functions

	Solution (Golang): [functions.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/functions/functions.go)

## Structs

1. Functions

	Solution (Golang): [structs.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/structs/structs.go)

## Pointers

1. Pointers

	Solution (Golang): [pointers.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/pointers/pointers.go)

## Solutions for coding problems

1. Problem #1 [Easy]: Given a list of numbers and a number k, return whether any two numbers from the list add up to k. 
	* For example, given [10, 15, 3, 7] and k of 17, return true since 10 + 7 is 17. 
	* Bonus: Can you do this in one pass?

	a. Solution (Golang) [verify_if_two_numbers_in_a_list_add_up_to_k.go](https://github.com/ramonfigueiredopessoa/golang_programming/blob/master/go/src/solutions_for_coding_problems/verify_if_two_numbers_in_a_list_add_up_to_k.go)

Go back to [Contents](#contents).