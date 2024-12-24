# Go: Panic on nil map access

This repository demonstrates a common error in Go: panicking due to accessing a nil map.  The `bug.go` file contains code that will panic, while `bugSolution.go` provides a corrected version.

## Bug

The issue stems from accessing or modifying a map without first checking if it's nil.  Go's maps are nil by default, and attempting to use a nil map leads to a runtime panic.

## Solution

The solution involves checking the map for nil before any operations. This can be done using an `if` statement or a conditional expression.
