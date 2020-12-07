# C Coding Style

## Table of Content

- [Table of Content](#table-of-content)
- [C Features](#c-features)
- [Indentation](#indentation)
- [Line length](#line-length)
- [Comments](#comments)
- [Braces and Spaces](#braces-and-spaces)
  * [Braces](#braces)
  * [Space](#space)
- [Functions](#functions)
- [Usefull links](#usefull-links)

## C Features

Use ANSI C or C99 without extension.

## Indentation

Indents using tabs and tabs are 4 characters.

## Line length

Line length **MUST** be **BELOW** 80 colummns.

## Comments

Comments use `/* ... */` not `//`

:warning: Be aware that comments should be used only when it's necessary, code must always be self documented.

## Braces and Spaces

### Braces

`{` and `}` are always, **ALWAYS**, on their own line.

```c
if (my_func() < 0)
{
    (...)
}
```

### Space

Use space after: `if`, `switch`, `case`, `for`, `do`, `while`.

But not with: `sizeof`, `typeof`, `alignof`, `__attribute__`.

## Usefull links

- [ANSSI - guide - Règles de programmation pour le développement sécurisé de logiciels en langage C - v1.2](https://www.ssi.gouv.fr/uploads/2020/05/anssi-guide-regles_de_programmation_pour_le_developpement_securise_de_logiciels_en_langage_c-v1.2.pdf)
- [JPL Institutional Coding Standard for the C Programming Language](https://andrewbanks.com/wp-content/uploads/2019/07/JPL_Coding_Standard_C.pdf)
- [MISRA C:2004 and MISRA AC AGC Coding Rules](https://mathworks.com/help/bugfinder/ug/misra-c-coding-rules.html)