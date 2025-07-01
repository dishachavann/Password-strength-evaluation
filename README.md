#  Password Strength Evaluation 

##  Objective
To understand what makes a password strong and evaluate different passwords using online password strength checkers.


##  Task Overview
-  Created multiple passwords with varying complexity.
-  Evaluated them using (https://www.passwordmeter.com/).
-  Analyzed feedback and learned password best practices.


##  Password Strength Results

| Password           | Strength (%)  | Complexity  | Feedback                                              |
|--------------------|---------------|-------------|-------------------------------------------------------|
| `disha`            | 7%            | Very Weak   | Too short, only lowercase letters                     |
| `disha123`         | 39%           | Weak        | Lacks uppercase letters and symbols                   |
| `Disha@10`         | 74%           | Strong      | Includes uppercase, lowercase, numbers, and a symbol  |
| `Dish@_2025$#`     | 100%          | Very Strong | Excellent length, multiple symbols, mixed character types |


##  Learnings & Best Practices

###  What Makes a Password Strong?
- Use at least **12 characters**.
- Mix of:
  - **Uppercase letters (A-Z)**
  - **Lowercase letters (a-z)**
  - **Numbers (0-9)**
  - **Symbols (!@#$%^&*)**
- Avoid:
  - Personal info like names (`disha123` is weak because of this).
  - Common words, simple patterns.

###  Password Creation Tips:
- Example strong password: `Dish@_2025$#`
- Example passphrase: `Sun$Rise&Blue_Sky2025`


##  Common Password Attacks

###  Brute Force Attack:
- Automated guessing of every possible combination.
- Longer, more complex passwords drastically increase the time to crack.

###  Dictionary Attack:
- Attackers try common words or known passwords from databases.


##  How to Improve Security Further
- **Use Multi-Factor Authentication (MFA)**  
  Adds a layer beyond passwords like OTP, fingerprint, or email confirmation.

- **Use Password Managers**  
  Tools like Bitwarden, Dashlane, or LastPass generate and store strong passwords securely.

- **Use Passphrases**  
  Example: `Happy$Dog&RunsFast2025` (Easy to remember, hard to crack).


##  Screenshots
-  Password Test for `disha` – Score: 7% – Very Weak
-  Password Test for `disha123` – Score: 39% – Weak
-  Password Test for `Disha@10` – Score: 74% – Strong
-  Password Test for `Dish@_2025$#` – Score: 100% – Very Strong

*(Screenshots are attached in the repository.)*


##  Conclusion
- Passwords like `disha` or `disha123` are highly insecure.
- Adding complexity (uppercase, symbols, length) improves strength significantly.
- Best practice: use complex passwords with MFA and consider password managers.
