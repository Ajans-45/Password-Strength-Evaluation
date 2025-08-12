# Task 6: Password Strength Evaluation - Detailed Report

## Objective
The objective of this task was to create multiple passwords with varying complexity, test them against an online password strength checker, and analyze the results to understand what makes a password strong.

## Tool Used
- **Password Meter** – https://passwordmeter.com/

---

## 1. Password: `ADmin3355@$`
**Score:** 100%  
**Complexity:** Very Strong

### Additions:
| Criteria                     | Count | Bonus |
|------------------------------|-------|-------|
| Number of Characters         | 11    | +44   |
| Uppercase Letters            | 2     | +18   |
| Lowercase Letters            | 3     | +16   |
| Numbers                      | 4     | +16   |
| Symbols                      | 2     | +12   |
| Middle Numbers or Symbols    | 5     | +10   |
| Requirements (5 met)         | -     | +10   |

### Deductions:
| Criteria                              | Count | Penalty |
|---------------------------------------|-------|---------|
| Repeat Characters (Case Insensitive)  | 4     | -2      |
| Consecutive Uppercase Letters         | 1     | -2      |
| Consecutive Lowercase Letters         | 2     | -4      |
| Consecutive Numbers                   | 3     | -6      |

**Analysis:**  
This password uses uppercase, lowercase, numbers, and symbols, meeting all complexity requirements. The length (11 characters) and variation make it resistant to brute-force and dictionary attacks.

---

## 2. Password: `admin123`
**Score:** 39%  
**Complexity:** Weak

### Additions:
| Criteria                  | Count | Bonus |
|---------------------------|-------|-------|
| Number of Characters      | 8     | +32   |
| Lowercase Letters         | 5     | +6    |
| Numbers                   | 3     | +12   |
| Middle Numbers or Symbols | 2     | +4    |

### Deductions:
| Criteria                      | Count | Penalty |
|--------------------------------|-------|---------|
| Consecutive Lowercase Letters | 4     | -8      |
| Consecutive Numbers           | 2     | -4      |

**Analysis:**  
This password lacks uppercase letters and symbols, making it vulnerable to dictionary attacks. It follows a common pattern (word + number), which is easily guessable.

---

## 3. Password: `12345678`
**Score:** 4%  
**Complexity:** Very Weak

### Additions:
| Criteria                  | Count | Bonus |
|---------------------------|-------|-------|
| Number of Characters      | 8     | +32   |
| Middle Numbers or Symbols | 6     | +12   |

### Deductions:
| Criteria                      | Count | Penalty |
|--------------------------------|-------|---------|
| Numbers Only                  | 8     | -8      |
| Consecutive Numbers           | 7     | -14     |
| Sequential Numbers (3+)       | 6     | -18     |

**Analysis:**  
This password consists only of sequential numbers, making it extremely easy to crack with a brute-force or dictionary attack. It is also one of the most commonly used passwords worldwide.

---

## Best Practices Learned:
1. Use at least **12 characters**.
2. Include a **mix of uppercase, lowercase, numbers, and symbols**.
3. Avoid common words, names, and predictable patterns.
4. Do not use sequential or repeated characters.
5. Use unique passwords for different accounts.
6. Consider a password manager for secure storage.

---

## Common Password Attacks:
- **Brute Force Attack**: Tries every possible combination until the correct one is found.
- **Dictionary Attack**: Uses a list of common words, patterns, and leaked passwords.
- **Credential Stuffing**: Uses stolen username-password pairs from data breaches.
- **Phishing Attacks**: Tricks users into revealing their passwords.

---

## Conclusion:
Password complexity significantly improves security. A strong password like `ADmin3355@$` is far more resistant to common attack methods than simple passwords like `admin123` or `12345678`. Adopting strong password practices is essential to safeguarding online accounts.

