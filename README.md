# `return` statement generator for Go

`goreturn` generates a `return` statement for a function with zero values.

## Installation

```console
$ go get -u github.com/110y/goreturn
```

## Usage

This generates a return statementat for a function placed at 1000 bytes in `main.go`.

```console
$ goreturn -pos 1000 < main.go
return nil
```
