Common functions
===

[![Build Status](https://drone.io/github.com/Unknwon/com/status.png)](https://drone.io/github.com/Unknwon/com/latest) [![Go Walker](http://gowalker.org/api/v1/badge)](http://gowalker.org/github.com/Unknwon/com)

This is an open source project for commonly used functions for the Go programming language.

This package need >= **go 1.2rc1**

## Contribute

Your contribute is welcome, but you have to check following steps after you added some functions and commit them:

1. Make sure you wrote user-friendly comments for **all functions** .
2. Make sure you wrote test cases with any possible condition for **all functions** in file `*_test.go`.
3. Make sure you wrote benchmarks for **all functions** in file `*_test.go`.
4. Make sure you wrote useful examples for **all functions** in file `example_test.go`.
5. Make sure you ran `go test -bench="."` and got **PASS** .

## Performance

See results on [drone.io](https://drone.io/github.com/Unknwon/com/latest) by `go test -bench="."`.
