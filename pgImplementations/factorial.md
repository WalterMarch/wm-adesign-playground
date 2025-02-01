# Factorial of a Positive Integer

Write a program to compute the factorial of positive integer `n` where:

* Factorial of 0 is 1.
* Factorial of n (written `n!`) is:

```text
n! = n * (n-1) * (n-2) * ... * 1
```

Additionally,

```text
n! = n * (n-1)!
```

## Pseudocode design

```text
function factorial(n):
    output = 1
    if n > 1:
        output = n * (factorial(n-1))
    return output

print(factorial(6))
```

## Implementations

[+] [C#](https://github.com/WalterMarch/wm-csharp-playground/tree/main/factorial)
[+] [Java](https://github.com/WalterMarch/wm-java-playground/tree/main/factorial)
[+] [JavaScript](https://github.com/WalterMarch/wm-javascript-playground/tree/main/factorial)
[] [Kotlin](https://github.com/WalterMarch/wm-kotlin-playground/tree/main/factorial)
[] [Pascal](https://github.com/WalterMarch/wm-pascal-playground/tree/main/factorial)
[] [Perl](https://github.com/WalterMarch/wm-perl-playground/tree/main/factorial)
[] [Python](https://github.com/WalterMarch/wm-python-playground/tree/main/factorial)
[] [Scala](https://github.com/WalterMarch/wm-scala-playground/tree/main/factorial)
[] [TypeScript](https://github.com/WalterMarch/wm-typescript-playground/tree/main/factorial)