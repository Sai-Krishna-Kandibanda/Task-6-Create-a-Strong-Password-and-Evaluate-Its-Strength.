# Task-6-Create-a-Strong-Password-and-Evaluate-Its-Strength.

## Objective
This task aimed to create multiple passwords of varying complexity, test their strength using an online password checker, analyse the results, and identify best practices for creating strong passwords.

## Tools Used
- Online password strength checker: https://passwordmeter.com, https://bitwarden.com/password-strength
- Word Document for noting scores and observations
- Screenshot tool (Snipping Tool) for capturing test results

## Passwords Created for Testing
Five passwords were created with varying complexity to analyse their strength:
1. `password123` — common word + numbers; weak.
2. `123456` — short numeric only; very weak.
3. `P@ssword2025!` — mix of upper/lowercase, number, symbol.
4. `Th!sIsAStr0ngP@ssw0rd!` — long, highly complex string.
5. `correcthorsebatterystaple` — long passphrase of unrelated words.

## Password Strength Testing Results
Each password was tested using the online strength checker, with scores and feedback recorded below:

| Password                  | Score                                    | Feedback                                                            |
|---------------------------|------------------------------------------|---------------------------------------------------------------------|
| password123               | **43%**                                  | Common, predictable; lacks complexity.                              |
| 123456                    | **4%**                                   | Very short, numbers only; widely used by attackers.                 |
| P@ssword2025!             | **100%**                                 | Good length; strong mix of characters, numbers, symbols.            |
| Th!sIsAStr0ngP@ssw0rd!    | **100%**                                 | Very long and complex; highly resistant to brute force.             |
| correcthorsebatterystaple | **100%**                                 | Long passphrase; strong but could be improved with numbers/symbols. |

## Best Practices for Strong Passwords
- Use **at least 12 characters** — longer is better.
- Combine **uppercase letters**, **lowercase letters**, **numbers**, and **symbols**.
- Avoid dictionary words, names, or predictable patterns.
- Don’t rely on obvious substitutions (e.g., `P@ssw0rd`).
- Consider using a **passphrase** of unrelated words to balance strength and memorability.
- Use a password manager to create and store unique passwords for each account.

## Common Password Attacks & How Strong Passwords Help
- **Brute Force Attack** – Tests all possible combinations; long, complex passwords make this take too long.
- **Dictionary Attack** – Uses common/stolen word lists; random or uncommon passwords defeat this.
- **Credential Stuffing** – Uses leaked credentials across sites; unique passwords stop reuse attacks.
- **Rainbow Table Attack** – Uses precomputed hashes; strong, complex passwords (and salting) reduce risk.

## Conclusion
Testing showed that password **length**, **variety of characters**, and **unpredictability** significantly improve strength. Short or common passwords are vulnerable to quick cracking. Adopting strong, unique credentials for every account is essential for security.
