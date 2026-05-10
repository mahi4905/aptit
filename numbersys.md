# NUMBER SYSTEM - TCS NQT PREPARATION

## MODULE 1: TYPES OF NUMBERS

### 1. Natural Numbers
- Counting numbers: 1, 2, 3, 4, 5, ...
- Starting from 1 and going to infinity
- **Key Point:** Zero (0) is NOT a natural number

### 2. Whole Numbers
- All counting numbers + Zero: 0, 1, 2, 3, 4, 5, ...
- **Remember:** 0 is the only whole number that is NOT a natural number
- Every natural number is a whole number

### 3. Integers
- All natural numbers, 0, and negative counting numbers
- {..., -3, -2, -1, 0, 1, 2, 3, ...}
- **Types:**
  - **Positive Integers:** {1, 2, 3, 4, ...}
  - **Negative Integers:** {-1, -2, -3, ...}
  - **Non-Positive Integers:** {0, -1, -2, -3, ...}
  - **Non-Negative Integers:** {0, 1, 2, 3, ...} (Same as Whole Numbers)

### 4. Even Numbers
- Numbers divisible by 2: 2, 4, 6, 8, 10, ...
- **General Form:** 2n (where n is any integer)

### 5. Odd Numbers
- Numbers NOT divisible by 2: 1, 3, 5, 7, 9, 11, ...
- **General Form:** 2n + 1 or 2n - 1

### 6. Prime Numbers
- A number > 1 with exactly two factors: 1 and itself
- **Prime numbers up to 100:** 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97
- **Total:** 25 prime numbers between 1 and 100

**Prime Check Method for number > 100:**
- Let p be the number to check
- Find k = √p (whole number just greater than square root)
- Test if p is divisible by any prime < k
- If YES → p is NOT prime
- If NO → p is prime

**Example:** Is 191 prime?
- √191 ≈ 13.8, so k = 14
- Primes less than 14: 2, 3, 5, 7, 11, 13
- 191 is not divisible by any of these
- Therefore, 191 is PRIME

### 7. Composite Numbers
- Numbers > 1 which are NOT prime
- Have more than 2 factors
- Examples: 4, 6, 8, 9, 10, 12, ...

**Important Notes:**
- 1 is neither prime nor composite
- 2 is the ONLY even prime number
- There are 25 prime numbers between 1 and 100

### 8. Co-prime Numbers
- Two numbers a and b are co-primes if their HCF = 1
- Examples: (2,3), (4,5), (7,9), (8,11)
- **Key:** Numbers don't have to be prime themselves to be co-prime

---

## MODULE 2: PROGRESSIONS

### Arithmetic Progression (A.P.)
- Sequence where difference between consecutive terms is constant
- **First term:** a
- **Common difference:** d
- **General form:** a, (a+d), (a+2d), (a+3d), ...

**Important Formulas:**
1. **nth term:** Tₙ = a + (n-1)d
2. **Sum of n terms:** Sₙ = n/2 × [2a + (n-1)d]
3. **Alternative sum formula:** Sₙ = n/2 × (first term + last term)

### Geometric Progression (G.P.)
- Sequence where ratio between consecutive terms is constant
- **First term:** a
- **Common ratio:** r
- **General form:** a, ar, ar², ar³, ...

**Important Formulas:**
1. **nth term:** Tₙ = arⁿ⁻¹
2. **Sum of n terms (r ≠ 1):** Sₙ = a(rⁿ - 1)/(r - 1) if r > 1
3. **Sum of n terms (r < 1):** Sₙ = a(1 - rⁿ)/(1 - r) if r < 1

---

## MODULE 3: DIVISIBILITY RULES - MASTER THIS!

### Rule 1: Divisibility by 2
**A number is divisible by 2 if its unit digit is 0, 2, 4, 6, or 8**
- Example: 84932 ✓ (ends in 2)
- Example: 65935 ✗ (ends in 5)

### Rule 2: Divisibility by 3
**A number is divisible by 3 if the SUM of its digits is divisible by 3**
- Example: 592482 → Sum = 5+9+2+4+8+2 = 30 ✓ (30 is divisible by 3)
- Example: 864329 → Sum = 8+6+4+3+2+9 = 32 ✗ (32 not divisible by 3)

### Rule 3: Divisibility by 4
**A number is divisible by 4 if the number formed by last TWO digits is divisible by 4**
- Example: 89248 → Last 2 digits = 48 ✓ (48÷4 = 12)
- Example: 749238 → Last 2 digits = 38 ✗ (not divisible by 4)

### Rule 4: Divisibility by 5
**A number is divisible by 5 if unit digit is 0 or 5**
- Example: 20820 ✓, 50345 ✓
- Example: 30234 ✗, 40946 ✗

### Rule 5: Divisibility by 6
**A number is divisible by 6 if divisible by BOTH 2 AND 3**
- Example: 35256 → Ends in 6 (div by 2) ✓, Sum = 3+5+2+5+6 = 21 (div by 3) ✓
- Therefore divisible by 6 ✓

### Rule 6: Divisibility by 8
**A number is divisible by 8 if the number formed by last THREE digits is divisible by 8**
- Example: 953360 → Last 3 digits = 360 ✓ (360÷8 = 45)
- Example: 529418 → Last 3 digits = 418 ✗

### Rule 7: Divisibility by 9
**A number is divisible by 9 if the SUM of digits is divisible by 9**
- Example: 60732 → Sum = 6+0+7+3+2 = 18 ✓ (18÷9 = 2)
- **Note:** If not divisible by 9, the sum gives remainder when divided by 9
- Example: 68956 → Sum = 6+8+9+5+6 = 34 → 34÷9 = remainder 7

### Rule 8: Divisibility by 10
**A number is divisible by 10 if it ends with 0**
- Example: 96410, 10480 ✓
- Example: 96375 ✗

### Rule 9: Divisibility by 11
**A number is divisible by 11 if (Sum of digits at ODD places - Sum of digits at EVEN places) = 0 or divisible by 11**
- Example: 4832718
  - Odd positions: 8+7+3+4 = 22
  - Even positions: 1+2+8 = 11
  - Difference: 22-11 = 11 ✓ (divisible by 11)

### Rule 10: Divisibility by 12
**A number is divisible by 12 if divisible by BOTH 3 AND 4**
- Example: 34632
  - Last 2 digits = 32 (divisible by 4) ✓
  - Sum = 3+4+6+3+2 = 18 (divisible by 3) ✓
  - Therefore divisible by 12 ✓

### Rule 11: Divisibility by 14
**A number is divisible by 14 if divisible by BOTH 2 AND 7**

### Rule 12: Divisibility by 15
**A number is divisible by 15 if divisible by BOTH 3 AND 5**

---

## MODULE 4: FACTORS AND MULTIPLES

### Factors
- When a number (dividend) is exactly divisible by another number (divisor), the divisor is a factor
- **Example:** 5 × 4 = 20
  - 4 divides 20 exactly → 4 is a factor of 20
  - 6 is also a factor (20÷6 gives quotient 4, zero remainder)
  
**Key Points:**
- 1 divides every integer → 1 is a common factor of all integers
- Every number is divisible by 1 and itself
- Every number is a multiple of 1

### Multiples
- A multiple of a number is the product of that number with any natural number
- **Multiples of 2:** 2, 4, 6, 8, 10, 12, ... (even numbers, last digit 0 or even)
- **Multiples of 3:** 3, 6, 9, 12, 15, 21, ... (sum of digits divisible by 3)
- **Multiples of 5:** 5, 10, 15, 20, 25, ... (last digit 0 or 5)

**Finding Multiples - Infinity Trick:**
- Multiples of any number can be infinite
- Just keep multiplying by 1, 2, 3, 4, ... to find "n" number of multiples

---

## MODULE 5: HCF AND LCM

### Highest Common Factor (H.C.F.) / Greatest Common Divisor (G.C.D.)
**The largest number that divides all given numbers exactly**

### Method A: Factorization Method
Express each number as product of prime factors, then take least powers of common factors

**Example:** Find HCF of 72, 108, 2100
- 72 = 2³ × 3²
- 108 = 2² × 3³
- 2100 = 2² × 5² × 3 × 7
- **HCF = 2² × 3¹ = 12** (taking minimum powers)

### Method B: Division Method (Most Efficient!)
1. Divide larger number by smaller
2. Divide previous divisor by remainder
3. Continue until remainder = 0
4. Last divisor is the HCF

**Example:** Find HCF of 513, 1134, 1215

```
1134 ) 1215 ( 1
       1134
       ----
         81 ) 1134 ( 14
              81
              ----
              324
              324
              ----
              000
```
So HCF of 1134 and 1215 = 81

Now find HCF of 81 and 513:
```
81 ) 513 ( 6
     486
     ----
     27 ) 81 ( 3
          81
          ---
          00
```
**∴ Required HCF = 27**

### Least Common Multiple (L.C.M.)
**The smallest number that is exactly divisible by all given numbers**

### Method A: Factorization Method
Take product of highest powers of all factors

**Example:** Find LCM of 72, 108, 2100
- 72 = 2³ × 3²
- 108 = 2² × 3³  
- 2100 = 2² × 5² × 3 × 7
- **LCM = 2³ × 3³ × 5² × 7 = 37,800**

### Method B: Common Division Method (Shortcut!)
Arrange numbers in a row, divide by smallest prime that divides at least 2 numbers, carry forward numbers not divisible, repeat until no two numbers are divisible by same prime

**Example:** Find LCM of 16, 24, 36, 54

```
2 | 16 - 24 - 36 - 54
2 |  8 - 12 - 18 - 27
2 |  4 -  6 -  9 - 27
2 |  2 -  3 -  9 - 27
3 |  1 -  3 -  9 - 27
3 |  1 -  1 -  3 -  9
  |  1 -  1 -  1 -  3
```

**∴ LCM = 2 × 2 × 2 × 2 × 3 × 3 × 3 = 432**

### GOLDEN RULE - Product Relationship
**For any two numbers a and b:**
```
Product of numbers = HCF × LCM
a × b = HCF(a,b) × LCM(a,b)
```

### HCF and LCM of Fractions

**A. HCF of Fractions:**
```
HCF = (HCF of Numerators) / (LCM of Denominators)
```

**B. LCM of Fractions:**
```
LCM = (LCM of Numerators) / (HCF of Denominators)
```

**Example:** Find HCF and LCM of 2/3, 8/9, 16/81, 10/27

**Solution:**
- HCF of numerators (2, 8, 16, 10) = 2
- LCM of numerators (2, 8, 16, 10) = 80
- HCF of denominators (3, 9, 81, 27) = 3
- LCM of denominators (3, 9, 81, 27) = 81

**HCF of fractions = 2/81**
**LCM of fractions = 80/3**

### HCF and LCM of Decimal Fractions

**Step 1:** Make same number of decimal places by adding zeros
**Step 2:** Find HCF or LCM without decimal points
**Step 3:** Mark off same number of decimal places in result

**Example:** Find HCF and LCM of 0.63, 1.05, 2.10

**Solution:**
Convert to same decimal places:
- 0.63 = 63/100
- 1.05 = 105/100
- 2.10 = 210/100

Without decimals: 63, 105, 210

HCF(63, 105, 210):
```
63 = 3² × 7
105 = 3 × 5 × 7
210 = 2 × 3 × 5 × 7
HCF = 3 × 7 = 21
```
**∴ HCF of decimals = 0.21**

LCM(63, 105, 210):
```
LCM = 2 × 3² × 5 × 7 = 630
```
**∴ LCM of decimals = 6.30**

### Comparison of Fractions using LCM
Find LCM of denominators, convert each fraction to equivalent fraction with LCM as denominator, then compare numerators. The fraction with greatest numerator is greatest.

**Example:** Compare 2/3, 8/9, 16/81

LCM of (3, 9, 81) = 81
- 2/3 = 54/81
- 8/9 = 72/81
- 16/81 = 16/81

**Greatest:** 8/9 (numerator 72 is largest)

---

## MODULE 6: UNIT DIGIT AND CYCLICITY

### Finding Unit Digit - The Power Pattern

**GOLDEN RULE:** When any number is raised to power n, the unit digit follows a pattern/cycle

### Cyclicity Table (MEMORIZE THIS!)

| Number | Cycle Length | Pattern | Unit Digits Cycle |
|--------|--------------|---------|-------------------|
| 0 | 1 | 0 | 0 |
| 1 | 1 | 1 | 1 |
| 2 | 4 | 2,4,8,6 | 2¹=2, 2²=4, 2³=8, 2⁴=6 |
| 3 | 4 | 3,9,7,1 | 3¹=3, 3²=9, 3³=7, 3⁴=1 |
| 4 | 2 | 4,6 | 4¹=4, 4²=6 (even=6, odd=4) |
| 5 | 1 | 5 | 5 |
| 6 | 1 | 6 | 6 |
| 7 | 4 | 7,9,3,1 | 7¹=7, 7²=9, 7³=3, 7⁴=1 |
| 8 | 4 | 8,4,2,6 | 8¹=8, 8²=4, 8³=2, 8⁴=6 |
| 9 | 2 | 9,1 | 9¹=9, 9²=1 (odd=9, even=1) |

### How to Find Unit Digit

**Step 1:** Identify unit digit of the base number
**Step 2:** Find the cyclicity (from table above)
**Step 3:** Divide power by cyclicity
- If remainder = 0 → use last digit of cycle
- If remainder = r → use rth digit of cycle

### Method to Remember:
1. Identify unit digit in base: x
2. If x = 0,1,5,6 → Unit digit is always x
3. If x = 2,3,7,8 → Cycle of 4 → Divide power by 4
4. If x = 4,9 → Cycle of 2 → Check if power is odd/even

---

## SOLVED EXAMPLE - UNIT DIGIT (MOST DIFFICULT PATTERN)

**Q. Find the unit digit of (2153)¹⁶⁷ × (8267)¹⁵³**

**Solution:**

**Part 1: Unit digit of (2153)¹⁶⁷**
- Base unit digit = 3
- Cycle of 3: {3, 9, 7, 1} (cycle length = 4)
- Divide power by cycle: 167 ÷ 4 = 41 remainder 3
- Remainder = 3 → Take 3rd position in cycle
- 3rd digit in {3,9,7,1} = **7**

**Part 2: Unit digit of (8267)¹⁵³**
- Base unit digit = 7
- Cycle of 7: {7, 9, 3, 1} (cycle length = 4)
- Divide power by cycle: 153 ÷ 4 = 38 remainder 1
- Remainder = 1 → Take 1st position in cycle
- 1st digit in {7,9,3,1} = **7**

**Part 3: Multiply unit digits**
- Unit digit of (2153)¹⁶⁷ = 7
- Unit digit of (8267)¹⁵³ = 7
- Unit digit of product = 7 × 7 = 49
- **Final Answer: Unit digit = 9**

---

## ADVANCED TRICK - NEGATIVE POWERS & COMPLEX EXPRESSIONS

### For expressions like x^a - y^b:

**Pattern Recognition:**
- When bases end in 4 and 3:
  - 4¹ = 4, 4² = 6, 4³ = 4, 4⁴ = 6 (odd power→4, even power→6)
  - 3¹ = 3, 3² = 9, 3³ = 7, 3⁴ = 1

**Example from lecture:** (164)¹⁶⁹ + (333)³³⁷ - (727)⁷²⁶
- 164 ends in 4: Power 169 is odd → unit digit = 4
- 333 ends in 3: 337 ÷ 4 = remainder 1 → unit digit = 3
- 727 ends in 7: 726 ÷ 4 = remainder 2 → unit digit = 9

Result: 4 + 3 - 9 = 7 - 9 = -2 → 10 - 2 = **8**

---

## SHORTCUTS & TRICKS COLLECTION

### Trick 1: Two-Digit Number Problems
**Pattern:** Product of digits changes positions
- If ab × ba, and given conditions about sum/product
- Use options to eliminate quickly

**From Lecture Q1:** Two-digit number, product of digits is 14, when 45 added digits interchange
- Try options: a.54, b.27, c.36, d.72
- Check: 27 → 2×7=14 ✓, 27+45=72 ✓

### Trick 2: Three-Digit Divisibility by 3
**Pattern:** If (X+Y+Z) not divisible by 3, then (XYZ + YZX + ZXY) is not divisible by 3

**From Lecture Q3:** Let XYZ be 3-digit number where (X+Y+Z) not multiple of 3
- XYZ = 100X + 10Y + Z
- YZX = 100Y + 10Z + X  
- ZXY = 100Z + 10X + Y
- Sum = 111X + 111Y + 111Z = 111(X+Y+Z)
- Since 111 = 37×3, and (X+Y+Z) not divisible by 3 → sum not divisible by 3

### Trick 3: Remainder Pattern (Important!)
**When number leaves remainder R₁ on division by D₁, find remainder when divided by D₂**

**Formula:** If D₁ = k × D₂, then R₂ = R₁ mod D₂

**From Lecture Q17:** Number ÷ 221 leaves remainder 30, find remainder when ÷ 13
- 221 = 17 × 13
- 30 ÷ 13 = 2 remainder **4**

### Trick 4: Digit Position Finding
**For 5³ × 2¹⁰⁰¹, find digit at thousand's place**

**Solution:**
- 5³ × 2¹⁰⁰¹ = 5³ × 2³ × 2⁹⁹⁸
- = 125 × 8 × 2⁹⁹⁸
- = 1000 × 2⁹⁹⁸
- = 1 followed by 3 zeros, then × 2⁹⁹⁸
- Thousand's place will have a digit from 2⁹⁹⁸
- 998 is even → 2ᵉᵛᵉⁿ ends in ...000
- **Answer: 4** (from shifting)

### Trick 5: Sum of Factorials Divisibility
**If p = N + 5, where N is product of three consecutive positive integers**
- Then p is prime OR p is odd

**Reason:** N = k(k+1)(k+2) is always even
- N + 5 = even + odd = odd
- Check by substituting

### Trick 6: Perfect Square Finding
**What's the least number to multiply with 5400 to get perfect square?**
- 5400 = 2³ × 3³ × 5² × ... 
- For perfect square, all powers must be even
- Need one more 2 and one more 3
- **Answer: 2 × 3 = 6**

### Trick 7: HCF with Remainders
**Greatest number that divides a, b, c leaving remainders r₁, r₂, r₃**

**Method:** Find HCF of (a-r₁), (b-r₂), (c-r₃)

**From Material Q19:** 156, 181, 331 divided leaving remainder 6
- (156-6) = 150
- (181-6) = 175
- (331-6) = 325
- HCF(150, 175, 325) = **25**

### Trick 8: Divisibility by 72 (Composite)
**For number to be divisible by 72 = 8 × 9**
- Must be divisible by 8 AND 9
- Check last 3 digits for 8
- Check sum of digits for 9

**From Lecture Q15:** If 785×3678y divisible by 72
- Sum of digits = 7+8+5+x+3+6+7+8+y
- For div by 9: sum must be multiple of 9
- For div by 8: last 3 digits (sum of 8,y must work)
- Find x+y from conditions

### Trick 9: Power Remainder Pattern
**When (7⁷⁷ + 77) ÷ 78**
- 78 = 77 + 1
- 7⁷⁷ = (-1)⁷⁷ (mod 78) = -1
- 7⁷⁷ + 77 = -1 + 77 = 76
- **Remainder = 76**

### Trick 10: Squared Number Remainder
**(n² + n + 2) ÷ 6 always leaves remainder based on n**
- n² + n = n(n+1) always even
- n(n+1) ÷ 6 pattern:
  - If n ≡ 2 (mod 6) → remainder = 2
  - Use this for quick solutions

---

## FORMULA QUICK REFERENCE

### Number of Zeros at End of n!
**Formula:** [n/5] + [n/25] + [n/125] + ...

**Example:** Zeros at end of 100!
- [100/5] + [100/25] + [100/125]
- = 20 + 4 + 0
- = **24 zeros**

### Highest Power of Prime p in n!
**Formula:** [n/p] + [n/p²] + [n/p³] + ...

**Example:** Highest power of 40 that divides 4000!
- 40 = 2³ × 5
- Find min of (power of 2³ and power of 5)
- Since 5 appears less, find [4000/5] + [4000/25] + ...
- Answer based on powers

### Number of Factors Formula
If N = p₁^a × p₂^b × p₃^c
**Total factors = (a+1)(b+1)(c+1)**

**Example:** Factors of 9321
- 9321 = 3 × 29 × 107
- Total factors = (1+1)(1+1)(1+1) = **8 factors**

### Sum of Factors
If N = p₁^a × p₂^b × p₃^c

**Sum = [(p₁^(a+1) - 1)/(p₁-1)] × [(p₂^(b+1) - 1)/(p₂-1)] × [(p₃^(c+1) - 1)/(p₃-1)]**

### Product of All Factors
If N has total k factors:
**Product of all factors = N^(k/2)**

### Number of Ways to Express as Product of Two Factors
- If N is NOT a perfect square: **k/2 ways**
- If N IS a perfect square: **(k+1)/2 ways**

---

## ADDITIONAL PATTERNS FROM LECTURE

### Pattern 1: Digit Position in Large Numbers
**For abc...xyz × 36(78)y type**
- Break into manageable parts
- Use base 10 representation
- Find pattern in powers

### Pattern 2: Remainder on Division by Products
**When n ÷ (a×b) leaves R, find remainder when ÷ a or ÷ b**
- Use: R mod a gives remainder when ÷ a
- Use: R mod b gives remainder when ÷ b

### Pattern 3: LCM with Conditions
**If LCM(a,b) = 500 and HCF = 50, find other number**
- Use: a × b = HCF × LCM
- If one number = 100
- Other = (50 × 500)/100 = **250**

### Pattern 4: Factorial Sum Remainders
**R = (1! + 2! + 3! + ... + 120!) ÷ 15**
- 1! = 1, 2! = 2, 3! = 6, 4! = 24, 5! = 120
- From 5! onwards, all factorials divisible by 15
- Sum = 1+2+6+24 = 33
- 33 ÷ 15 = remainder **3**

---

## EXAM STRATEGY POINTS

### Time-Saving Tips:
1. **Memorize cyclicity table** - saves 30 seconds per question
2. **Use divisibility rules** instead of actual division
3. **Eliminate options** using unit digit before full calculation
4. **HCF/LCM** - use division method for speed
5. **For large powers** - always use cyclicity, never calculate

### Pattern Recognition:
- Product of consecutive integers → divisibility patterns
- Sum/difference of powers → unit digit analysis
- Remainders → modular arithmetic shortcuts
- Factorials → use formulas for zeros/highest powers

### Common Question Types:
1. Find unit digit of expression
2. Divisibility by composite numbers
3. HCF/LCM word problems  
4. Remainder theorems
5. Number of factors/zeros
6. Perfect square/cube multiples

---

## PRACTICE FOCUS AREAS

**HIGH PRIORITY:**
1. Unit digit and cyclicity (appears in 30% questions)
2. Divisibility rules 2-15 (quick elimination)
3. HCF/LCM word problems (2-3 questions guaranteed)
4. Remainder patterns
5. Prime number properties

**MEDIUM PRIORITY:**
1. Number of factors
2. Perfect squares/cubes
3. Co-prime concepts
4. Factorial properties

**MASTER THESE FIRST** - They appear most frequently in TCS NQT!

---

**END OF NUMBER SYSTEM NOTES**

*Keep practicing! Speed comes with pattern recognition.* 🎯
