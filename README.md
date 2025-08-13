# Task 6: Password Strength Analysis Report

## Objective
The objective of this task was to understand the principles of creating a strong password by testing passwords of varying complexity against an online strength-checking tool and researching best practices.

## Tools Used
* Online Password Strength Checker

## Process
1.  A series of six sample passwords were created to represent different levels of strength and common user habits, from weak to very strong passphrases.
2.  Each sample password was tested using an online strength checker to evaluate its score and complexity rating.
3.  The results were documented, and research was conducted on common password attacks and modern authentication best practices.
4.  The findings were consolidated into this comprehensive report.

---

## Password Strength Evaluation

The following table summarizes the results of the password strength tests.

| Password Type                  | Sample Password                    | Score / Complexity                            | Analysis                                                                                                 |
| :----------------------------- | :--------------------------------- | :-------------------------------------------- | :------------------------------------------------------------------------------------------------------- |
| **Weak (Common Word)** | `password123`                      | **43% (Good)**                | Deceptively rated "Good" but is extremely weak as it appears at the top of every password-cracking list.       |
| **Weak (Personal Info)** | `vikrant2025`                      | **55% (Good)**                    | Weak because it uses easily guessable personal information that could be found through social media.         |
| **Medium (Simple Substitution)**| `P@ssw0rd!`                        | **82% (Very Strong)**         | While rated "Very Strong" by the tool, this is a flawed technique as automated attacks can easily guess common substitutions. |
| **Medium (Short & Complex)** | `R#b8^k!Z`                         | **96% (Very Strong)**           | Strong complexity but its short length makes it more vulnerable to modern brute-force attacks over time.  |
| **Strong (Long & Complex)** | `cyb3r$ec-L@b$-Rul3z!`             | **100% (Very Strong)**          | An excellent password. It is long, random, and uses a mix of all four character types.                   |
| **Strong (Passphrase)** | `Correct-Horse-Battery-Staple-99!` | **100% (Very Strong)**         | An excellent password. Its significant length makes it extremely resistant to brute-force attacks.        |

---

## Analysis & Key Learnings

This exercise provided several key insights into password security.

### How Password Complexity Affects Security
Password complexity, which includes a mix of **uppercase letters, lowercase letters, numbers, and symbols**, makes a password exponentially harder to guess. However, the most critical factor is **length**. A long password or passphrase, even a simpler one, is generally stronger than a short, complex one because it dramatically increases the number of possible combinations an attacker would have to try in a brute-force attack.

### Common Password Attacks
* **Brute-Force Attack:** This is an automated attack where software tries every possible combination of characters until the correct password is found. Longer and more complex passwords make this attack mathematically impractical.
* **Dictionary Attack:** This is a more targeted attack where the software tries a pre-compiled list of common words, phrases, names, and previously leaked passwords. This is why using common words like `password123` is so dangerous.

### Best Practices for Password Creation
1.  **Length is Key:** Aim for a password that is at least 16 characters long.
2.  **Use Passphrases:** A passphrase (a memorable sequence of 4-5 random words) is often stronger and easier to remember than a complex, short password.
3.  **Use a Mix of Character Types:** Always include uppercase, lowercase, numbers, and symbols.
4.  **Avoid Personal Information:** Never use your name, birthday, pet's name, or other easily guessable information.
5.  **Uniqueness:** Never reuse passwords across different websites or services.

### The Role of MFA and Password Managers
* **Multi-Factor Authentication (MFA):** This is the single best way to secure an account. It requires a second form of verification (like a code from your phone) in addition to your password. Even if an attacker steals your password, they cannot log in without your second factor.
* **Password Managers:** These tools generate and securely store long, complex, and unique passwords for all your accounts. You only need to remember one master password. This helps you follow best practices without having to memorize dozens of difficult passwords.

## Conclusion
A strong password is a critical first line of defense, but it is not enough on its own. The best security is achieved by combining a long, complex, and unique password (ideally a passphrase managed by a password manager) with the mandatory use of Multi-Factor Authentication.
