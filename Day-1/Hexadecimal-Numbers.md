# Day 1 - Hexadecimal Numbers

## 📚 Topic Overview
**Course:** DevOps Engineer with AI: CI/CD Pipelines & Docker Skills  
**Date:** November 23, 2025  
**Source:** HyperSkill - Computational Math

---

## 🎯 What is Hexadecimal (HEX)?

Hexadecimal is a **base-16 number system** used extensively in computer science as a compact way to represent binary data.

### Why HEX?
- Computers work with bits (binary: 0 and 1)
- Grouping 4 bits creates 16 possible values (2^4 = 16)
- More compact than decimal, octal, and binary systems
- Easy conversion to/from binary

---

## 🔢 Hexadecimal Digits

HEX uses:
- Numbers: `0, 1, 2, 3, 4, 5, 6, 7, 8, 9`
- Letters: `A, B, C, D, E, F` (representing decimal 10-15)

### Comparison Table

| Binary | Decimal | HEX |
|--------|---------|-----|
| 0000   | 0       | 0   |
| 0001   | 1       | 1   |
| 0010   | 2       | 2   |
| 0011   | 3       | 3   |
| 0100   | 4       | 4   |
| 0101   | 5       | 5   |
| 0110   | 6       | 6   |
| 0111   | 7       | 7   |
| 1000   | 8       | 8   |
| 1001   | 9       | 9   |
| 1010   | 10      | A   |
| 1011   | 11      | B   |
| 1100   | 12      | C   |
| 1101   | 13      | D   |
| 1110   | 14      | E   |
| 1111   | 15      | F   |

---

## 🔄 Binary ↔ HEX Conversion

### Binary to HEX
1. Split binary number into groups of 4 bits (from right to left)
2. Add leading zeros if needed
3. Convert each 4-bit group to its HEX digit

**Example:**
```
11100110011100012 = 1110 0110 0111 0001
                  = E    6    7    1
                  = E67116
```

### HEX to Binary
- Each HEX digit = 4-bit binary sequence

**Example:**
```
BE16 = 1011 1110
     = 101111102
```

---

## 💡 Real-World Applications

1. **Error Codes:** Operating systems encode errors in hexadecimal
2. **URLs:** Character codes written as hex pairs (e.g., `%40` for `@`)
3. **Color Codes:** RGB colors defined as 3 hex pairs (#RRGGBB)
4. **Unicode:** Character encoding uses hex representation
5. **Memory Addresses:** Computer memory locations shown in hex
6. **Low-level Programming:** Assembly language and debugging

---

## 📌 Key Takeaways

✅ HEX is base-16 with digits 0-9 and A-F  
✅ Each HEX digit represents 4 bits (nibble)  
✅ Easy binary-to-hex conversion by grouping 4 bits  
✅ Widely used in CS: colors, URLs, memory, error codes  
✅ Notation: `0x63`, `63h`, or 6316

---

## 🔗 Resources
- [HyperSkill Course](https://hyperskill.org/learn/step/8788)
- Practice converting between binary, decimal, and hexadecimal

---

**Progress:** Day 1/100 of DevOps Learning Journey 🚀
