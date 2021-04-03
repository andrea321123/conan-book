# Functions

Each Conan programs is made of functions and variables.  
The `main` function is the entry point of your program.  
The `fun` keyword allows you to declare functions

```
fun main(): i32 {
    return sum(3, 5);
}

fun sum(a: i32, b: i32): i32 {
    return a + b;
}
```

As you can see, each function must have a return type and optionally a list off parameters (inside the parenthesis).

The `return` keyword allows you to return values to the code that calls the function.

## Next chapter

You can go to the [next chapter](variables.md), or you can return to the [table of contents](index.md).