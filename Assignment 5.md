Part 1: (10 points)
Proove each of the following. Indicate which proof method you are using and show your work.

 Show that the square root of 2 is irrational.
  Contradiction
  2^(1/2)=b/a
  2=b^2/a^2
  2a^2=b^2
  since 2a^2 is even, b^2 is even
  let b=2c
  2a^2=(2c)^2
  2a^2=4c^2
  a^2=2c^2
  since 2c^2 is even, a^2 is even, and therefore a is even
  two even numbers cannot be relatively prime
  2^(1/2) cannot be expressed as a rational fraction so it is irrational

 If n = 25, 100, or 169, then n is a perfect square and is the sum of two perfect squares.
  Exhaustive
  n = 25, 5^2=25, 0^2=0, 0+25=25
  n = 100, 10^2=100, 0^2=0, 0+100=100
  n = 169, 13^2=169, 0^2=0, 0+169=169

 The sum of two odd integers is even. Hint: By definition, even integers can be expressed as 2n, thus odd integers can be expressed as 2n + 1
  Direct Proof
  2m+1=x
  2n+1=y
  2n+1+2m+1
  2n+2m+2
  2(n+m+1)
  3 odd numbers makes another odd number so n+m+1=q
  2q is the definition of an even number

 The sum of an even integer and it's square is even
  Contradiction
  n+n^2 is even
  n=2m
  2m+(2m)^2
  2m+4m^2
  2(m+2m^2)
  p=m+2m^2
  2p is even by definition
  
 If n squared is odd, then n is odd
  contradiction
  n=2x
  n^2=odd
  (2x)^2=odd
  4x^2=odd
  (2x)(2x)=odd
  wrong because 2x is even

Part 2: (10 points)
 Prove by induction that 1 + 5 + 9 + ... + (4n-3) = n(2n-1)
  n=1
  4(1)-3=1
  1=1
  4k-3=2k^2-k
  (4(k+1)-3) = (k+1)(2(k+1)-1)
  (4k+4-3)=(k+1)(2k+2-1)
  4k+1=(k+1)(2k+1)
  4k+1=2k^2+3k+1
  1 + 5 + 9 + ... + (4k-3) + 4k+1 = k(2k-1) + 4k+1
  k(2k-1) + 4k+1
  2k^2-k+4k+1
  2k^2+3k+1

 Prove that for any positive integer number n, n^3 + 2n is divisible by 3
  n>0, n^3 + 2n / 3
  n=1, 1^3+2(1)=3, 3/3=1
  n=k, k^3+2k
  n=k+1, (k+1)^3+2(k+1)
  (k^2+2k+1)(k+1)+2k+2
  (k^3+2k^2+k+k^2+2k+1)+2k+2
  (k^3+3k^2+3k+1)+2k+2
  (k^3+2k)+(3k^2+3k+3)
  (k^3+2k)+3(k^2+k+1)
  (proven)+3(k^2+k+1)
  second is divisible by 3 since it is multiplied by 3

 Prove that for n >= 1, 9^n - 1 is divisible by 8 for all non-negative integers Hint: 4^(3+1) = 4 * 4^3 Hint: If 9^n - 1 = 8m, then 9^n = 8m + 1
  n > 0, (9^n - 1) = 8m
  n=1
  (9-1)/8
  8/8=1
  n=k
  (9^k - 1)
  n=k+1
  (9^(k+1) - 1)
  9^k*9-1
  (8m + 1)*9 -1
  72m + 9 -1
  72m + 8
  8(9m + 1)
  divisible by 8 because it is multiplied by 8
  
