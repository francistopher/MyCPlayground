## Printing "Hello World!"

When a baby is born it either cries or says goo goo ga ga. When a fellow lonely newbie conceives their first program it prints "Hello, World!". We start off by using the keyword "include" to include the standard input/output library using the "#" symbol. This library is used for inputting data into memory and outputting data onto the screen. The name of the library goes in between the "< >".

```c

#include <stdio.h>

```

Now we need a container of some sort that will execute our code. And this container has the name "main", which is known as the main function. The main function has a return type of "int" which stands for integer, it's returning the integer 0 with the keyword "return". "void" means that the function doesn't take in any values. "{ }", what lies in between the braces is the code that will be executed when the function main is called.

```c

int main(void) {
    return 0;
}

```
You're gonna get something like this. Because we are returning 0, 0 stands for 0 errors by convention. 

```linux

....Program finished with exit code 0

```

If f(x) is equal to x + 1, then f(1) equals 2. If printf(text); is equal to a function that prints data on the terminal, then printf("Hi\n"); will print "Hi". We use the special character combination "\n" to move the carriage to the next line, I do this because it's a good practice. Remember that in C every statement ends with a semicolon.

```c
#include <stdio.h>

int main (void) {
    
    printf("Hello, World!\n");
    return 0;

}
```

