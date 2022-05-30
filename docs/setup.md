# Library initialization and destruction

## Library initialization

To get everything started, just call `al_init` with no arguments.

## Library destruction

Once done with the program, call `al_exit` with no arguments.

## Program using alex with no content

```c
#include <alex/alex.h>

int main() {
    al_init();
    // Lexer usage goes here!
    al_exit();
}

```
