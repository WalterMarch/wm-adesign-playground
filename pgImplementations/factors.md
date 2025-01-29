# Factors of a Positive Integer

Write a program to find the factors of a positive integer.

The factors of positive integer `n` are any positive integer `i` less than or equal to `n` where `n modulo i` is equal to 0 (in other words, `i` divides evenly into `n`).

## pseudocode design

If the language has a Set data structure, the following design can be used.

```text
n = 100
factorSet = (1, n)
for i = 2 to n-1:
    if (n modulo i == 0):
        factorSet.append(i)
        factorSet.append(n dividedBy i)

print(sorted(factorSet))
```

For languages without a readily accessible Set data structure, the following design can be used instead. (Readily accessible means accessible both in terms of usability and availability without needing to install extra libraries or packages.)

```text
n = 100
factorArray = [1, n]
for i = 2 to n-1:
    if (i not in factorArray) and (n modulo i == 0):
        factorArray.add(i)
        if (n / i) != i:
            factorArray.add(n / i)

print(sorted(factorArray))
```

## Implementations

[+] [C#](https://github.com/WalterMarch/wm-csharp-playground/tree/main/factors)
[+] [Java](https://github.com/WalterMarch/wm-java-playground/tree/main/factors)
[+] [JavaScript](https://github.com/WalterMarch/wm-javascript-playground/tree/main/factors)
[+] [Kotlin](https://github.com/WalterMarch/wm-kotlin-playground/tree/main/factors)
[+] [Pascal](https://github.com/WalterMarch/wm-pascal-playground/tree/main/factors)
[+] [Perl](https://github.com/WalterMarch/wm-perl-playground/tree/main/factors)
[+] [Python](https://github.com/WalterMarch/wm-python-playground/tree/main/factors)
[+] [Scala](https://github.com/WalterMarch/wm-scala-playground/tree/main/factors)
[+] [TypeScript](https://github.com/WalterMarch/wm-typescript-playground/tree/main/factors)
