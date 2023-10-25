# Homework-2

## Questions

1. Modular arithmetic - you just need to find examples, you don't need to prove anything. <br />
   (a) Is it true that all odd squares are ≡ 1 (mod 8)? <br />
   (b) What about even squares (mod 8)?

2. Try out the vanity bitcoin address example at asecurity or the Ethereum version

3. What do you understand by the following? For a proof size, which of these would you want ?
   1. O(n)
   2. O(1)
   3. O(log n)

## Answers

**1(a)**.

```
Assuming that k is in Z and n is odd for n = (2k+1)
The square of n^2, (2k+1)^2 = 4k^2+4k+1 = 4k(k+1)+1
Since k is odd and k+1 is even, then 4k(k+1) will be equal 0 and +1 will be equal to 1.
∴ (2k+1)^2 ≡ 1 mod 8 is true for all odd squares.
```

**1(b)**.

```
Assuming that n is even and k can be even or odd, we can let n = 2k.
Then n^2 = (2k)^2 = 4k^2
Let's say k is odd, k^2 is still odd.
Knowing that k^2 is odd, we can let k^2 = 2n+1, then 4k^2 = 4(2n+1) = 8n+4 ≡ 0 mod 8
∴ (2k)^2 ≡ 0 mod 8 is NOT true for all even squares.
```

**3**

```
1. O(n) - Linear time complexity, this means that in the worse case the time is **linear** with relation to the input size.
2. O(1) - Constant time complexity, this means that the time is **constant** no matter what the input size is.
3. O(log n) - Logarithmic time complexity, this means that the time is **logarithmic** with relation to the input size.

For a proof size, we would typically prefer efficient algorithms with lower time complexity especially for large inputs. 
Therefore, O(1) is the most desirable, as the run time is constant, regardless of input size.
```
