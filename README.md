# Password Strength Checker

This Python script evaluates the strength of a password based on certain criteria. It checks for the presence of lowercase letters, uppercase letters, digits, and special characters, and determines the strength accordingly.

## Usage

1. **Clone Repository**: 
    ```bash
    git clone https://github.com/your-username/password-strength-checker.git
    ```

2. **Navigate to Directory**:
    ```bash
    cd password-strength-checker
    ```

3. **Run Script**:
    ```bash
    python password_strength_checker.py
    ```

4. **Enter Password**:
    Enter the password when prompted and press Enter.

## Criteria for Strength Evaluation

- **Strong Password**: 
  - Contains lowercase and uppercase letters, digits, special characters.
  - Length is at least 8 characters.

- **Moderate Password**: 
  - Contains either lowercase or uppercase letters, along with special characters.
  - Length is at least 6 characters.

- **Weak Password**: 
  - Does not meet the criteria for strong or moderate passwords.

## Example

```python
Enter the password : MyP@ssw0rd
Strength of password : Strong
