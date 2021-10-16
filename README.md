# Where is my pointer
This script encircles the pointer with a large yellow square that shrinks towards the pointer.

This script ought to be run with the ```timeout``` command.

## Build
Requires libX11
```sh
gcc -std=c99 WhereIsMyPointer.c -o wimpointer -lX11
```
## TODO

- [ ] Fix picom crash

## Credits
https://github.com/ferhatgec/whereismypointer
