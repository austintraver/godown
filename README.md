# godown

[![Build Status](https://travis-ci.org/mattn/godown.png?branch=master)](https://travis-ci.org/mattn/godown)
[![Codecov](https://codecov.io/gh/mattn/godown/branch/master/graph/badge.svg)](https://codecov.io/gh/mattn/godown)
[![GoDoc](https://godoc.org/github.com/mattn/godown?status.svg)](http://godoc.org/github.com/mattn/godown)
[![Go Report Card](https://goreportcard.com/badge/github.com/mattn/godown)](https://goreportcard.com/report/github.com/mattn/godown)

## About

Convert HTML into Markdown.

This is work in progress.

## Installation

* Installing the package:

    ```shell
    go get github.com/mattn/godown/cmd/godown
    ```

* Installing the command line interface:

    ```shell
    go install github.com/mattn/godown/cmd/godown@latest
    ```

## Usage

* From inside Go programs:

    ```go
    err := godown.Convert(w, r)
    checkError(err)
    ```

* From the command line:

    ```shell
    godown < input.html > output.md
    ```

---

## TODO

- [ ] Escape strings in HTML

## License

MIT

## Author

Yasuhiro Matsumoto (a.k.a. mattn)
