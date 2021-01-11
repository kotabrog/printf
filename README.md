# printf

## Overview

It is a self-made printf made in C.

## Requirement

- macOS
- clang

## Usage

```
git clone ...
cd printf
make
```
A library called libftprintf.a will be created, so compile it with the main file you want to use.  
For example, if you have main.c and libftprintf.a in your current directory:

```
gcc main.c -L . -lftprintf
```

## Features

- The flag characters: -0#' '+.*
- The length modifier: hh, h, l, ll
- The conversion specifier: cspdiuxX%nfge

## sample

You can see many examples of using printf in main.c

## Author

[twitter](https://twitter.com/Kotabrog)

## Licence

[MIT](https://github.com/kotabrog/printf/blob/main/LICENSE)