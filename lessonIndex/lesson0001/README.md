# Practise for indexes

Here we will practice how to select elements from a string. We will use the string `Hello, World!` for all the exercises.

Level: Beginner to programming

Who are you: you should be someone who is beginning to program. If you already know how to program in another language, you may skip these exercises.

## Ex 0001

print the first 1st element of a string

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the next line to print H
    // put the right index in the square brackets
    // fmt.Println(string(s[]))
}
```

## Ex 0002

print the 2nd element of a string

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the next line to print e
    // fmt.Println(s)
}
```

## Ex 0003

print the 3rd element of a string

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    sr := []rune(s)
    // Modify the next line to print l
    // fmt.Println(sr)
}
```

## Ex 0004

select the right index to print the underlying int value of the space character

check the [ASCII table](`man ascii`) to find the right index. you can quite a man view of terminal by pressing `q`

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the next line to have the right index to print 32 (the underlying int value of the space character)
    // fmt.Println(s[])
}
```

## Ex 0005

print the first 11th element of a string

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the next line to print the 11th element
    // make sure you know what the 11th element is before you print it
    // check the right answer at the end of this file
    // fmt.Println(s)
}
```

## Ex 0006

print the last 3 elements of a string

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the n in the fmt.Println() line to print the last 3 elements
    // fmt.Println(string(s[n:]))
}
```

## Ex 0007

print the first 3 elements of a string

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the next line to print Hel
    // fmt.Println(string(s[:n]))
}
```

## Ex 0008

print the letters `llo` of the string slice

```go
package main

import "fmt"

func main() {
    s := "Hello, World!"
    // Modify the `n` and `m` in the fmt.Println() line to print llo
    // fmt.Println(string(s[n:m]))
}
```

## Answers

- Ex 1: H
- Ex 2: e
- Ex 3: l
- Ex 4: 32 => to get to the answer you should have put the index(6) of the space character (check ascii table under the decimal value of the space character)
- Ex 5: l
- Ex 6: ld!
- Ex 7: Hel
- Ex 8: llo => to get to the answer you should have put the index(2) of the l character and the index(5). when you put index 5, it will select everything from index 2 to 5 (index 5 is not included in the range).
