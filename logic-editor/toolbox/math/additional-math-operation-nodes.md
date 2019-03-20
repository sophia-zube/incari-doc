# Additional Math Operation Nodes

## Modulo

Takes two numerical input types; `a` \(_the dividend_\) and `b` \(_the divisor_\) and returns the _remainder_ of the[ Euclidean division](../../../getting-started/terminology.md) of `a` and `b`.

Euclidean division simply means that the result of a division is a _floored_ whole number. With regular division, If 3 people share 10 slices of pizza, they would each have ~3.33 slices of pizza. With Euclidean division, however, they would each have 3 slices, with 1 slice remaining; therefore, a modulo operation of 3 and 10, would give us 1, the remainder.

### Uses

Modulo has a lot of uses in logic. The simplest example would be to determine if a number is odd or even. By using 2 as our _divisor_, we can see if a number is even \(0\) or odd \(1\).

| `a` | `b` | Result | Assertion |
| :--- | :--- | :--- | :--- |
| 12 | 2 | 0 | Even |
| 7 | 2 | 1 | Odd |
| 1839 | 2 | 1 | Odd |

Another common use is converting a time format from 24-Hour to 12-Hour and making calculations on what time it will be in x amount of hours.

| `a` | `b` | Result |
| :--- | :--- | :--- |
| 8 | 12 | 8 |
| 19 | 12 | 7 |
| 18 + 9 | 12 | 3 |

We can also use modulo operations to ensure that rotation stays within 0[°](https://www.degreesymbol.net/) - 360[°](https://www.degreesymbol.net/).

| `a` | `b` | Result |
| :--- | :--- | :--- |
| 720 | 360 | 0 |
| 1260 | 360 | 180 |
| 9999 | 360 | 279 |



