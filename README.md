Some programming examples in Golang
===========================

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

## Contents
0. [Hello, World](#hello_world)
1. [Variables](#variables)

## Hello World

0. Hello World program

	Solution (Golang): [hello_world.go](https://github.com/ramon-pessoa/golang_programming/blob/master/go/src/hello_world/hello.go)

0. Variables

	Solution (Golang): [variables.go](https://github.com/ramon-pessoa/golang_programming/blob/master/go/src/variables/variables.go)

Go back to [Contents](#contents).
