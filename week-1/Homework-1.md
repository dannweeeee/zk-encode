# Some Modular Arithmetic

## Questions

1. Working with the following set of Integers S = {0,1,2,3,4,5,6}
   What is the result of the following operations ?
   a) 4 + 4
   b) 3 x 5
   c) what is the inverse of 3 ?

2. For S = {0,1,2,3,4,5,6} Can we consider 'S' and the operation '+' to be a group ?

3. What is -13 mod 5 ?

4. For the polynomial x^3 − x^2 + 4x − 12 Find a positive root ? What is the degree of this polynomial ?

## Answers

**1(a)**.

```
4 + 4 = 8
8 % 7 = 1
∴ 4 + 4 ≡ 1 mod 7
```

**1(b)**.

```
3 * 5 = 15
15 % 7 = 1
∴ 3 * 5 ≡ 1 mod 7
```

**1(c)**.

```
Using a^-1 ≡ a^(p-2)(modp)
∴ 3^(7-2) = 3^5 = 242 ≡ 5 mod 7
```

**2**.

```
Yes, we can consider 'S' and the operation '+' to be a group as it follows all of the group properties.
```

**3**.

```
Since the result cannot be a -ve number, we add 5 to -13 until we get a +ve number.
∴ -13 % 5 ≡ 2 mod 5
```

**4**.

```
Since 2^3 + 2^2 + 4(2) - 12 = 8 - 4 + 8 - 12 = 0
∴ x = 2 is a root.
∴ The degree of polynomial is the highest exponent which is 3.
```
