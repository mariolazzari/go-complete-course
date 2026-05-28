# Go complete course

## Introduction

[Udemy course](https://www.udemy.com/course/go-golang-complete-guide/?couponCode=PMNVD3025)


## Installing Go

## Basics

```sh
go mod init hello-go
ge get github.com/fatih/color
go mod tidy
go run .
go build main.go
go build main.go -o hello
```

```go
package main

import (
	"fmt"

	"github.com/fatih/color"
)

func main() {
	fmt.Println("I want a cup of coffee!")
	color.Yellow("I want a cup of coffee!")
}
```
