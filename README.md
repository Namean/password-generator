# password-generator
A group project

# Password Generator Roadmap (Python)

## Project Goal
Build a program that creates strong, random passwords with customizable options.

---

## Phase 1: Basic Setup (30 minutes)

### Task 1.1: Create Your File
- Create a new file called `password_generator.py`
- Open it in your code editor

### Task 1.2: Import Necessary Modules
```python
import random
import string
```
- `random` - helps generate random choices
- `string` - provides letters, digits, and symbols

---

## Phase 2: Simple Password Generator (1 hour)

### Task 2.1: Create Character Sets
- Define what characters can be used:
  - Lowercase letters (a-z)
  - Uppercase letters (A-Z)
  - Numbers (0-9)
  - Symbols (!@#$%^&*)

### Task 2.2: Write a Basic Function
- Create a function called `generate_password()`
- Set a fixed length (e.g., 12 characters)
- Randomly select characters from your character set
- Return the generated password

### Task 2.3: Test Your Function
- Call the function and print the result
- Run it multiple times to see different passwords

---

## Phase 3: Add Customization (1-2 hours)

### Task 3.1: Add Length Parameter
- Modify your function to accept a `length` parameter
- Allow users to specify how long they want the password

### Task 3.2: Add Character Type Options
- Add parameters for:
  - `include_uppercase` (True/False)
  - `include_numbers` (True/False)
  - `include_symbols` (True/False)
- Only include character types when their option is True

### Task 3.3: Add Input Validation
- Check if length is at least 4 characters
- Make sure at least one character type is selected
- Display helpful error messages

---

## Phase 4: User Interface (1 hour)

### Task 4.1: Create a Menu
- Display welcome message
- Show options to the user:
  1. Generate password
  2. Exit program

### Task 4.2: Get User Input
- Ask for password length
- Ask which character types to include
- Handle invalid inputs gracefully

### Task 4.3: Display Results
- Show the generated password clearly
- Ask if they want to generate another password

---

## Phase 5: Advanced Features (Optional - 2-3 hours)

### Task 5.1: Ensure Complexity
- Guarantee at least one character from each selected type
- Example: If symbols are enabled, ensure at least 1 symbol appears

### Task 5.2: Multiple Passwords
- Allow generating multiple passwords at once
- Display them in a numbered list

### Task 5.3: Password Strength Indicator
- Calculate password strength (weak/medium/strong)
- Based on length and character diversity
- Display the strength rating

### Task 5.4: Save to File
- Add option to save passwords to a text file
- Include timestamp with each saved password

---

## Phase 6: Testing & Refinement (30 minutes)

### Task 6.1: Test Edge Cases
- Try length = 0 or negative numbers
- Try with all character types disabled
- Try very long passwords (100+ characters)

### Task 6.2: Add Comments
- Explain what each function does
- Add docstrings to your functions
- Make code readable for others

### Task 6.3: Final Cleanup
- Remove any debug print statements
- Make sure variable names are clear
- Format code consistently

---

## Complete Example Structure

```
password_generator.py
├── Import modules
├── Define character sets
├── generate_password() function
├── validate_input() function
├── calculate_strength() function (optional)
├── display_menu() function
├── get_user_preferences() function
└── main() function (runs the program)
```

---

## Learning Tips

1. **Start Simple**: Complete Phase 1-2 first, then add features
2. **Test Often**: Run your code after each task
3. **Debug Patiently**: Use print() statements to see what's happening
4. **Read Errors**: Python error messages tell you what went wrong
5. **Ask Questions**: Look up functions you don't understand

---

## Estimated Time
- **Beginner**: 4-6 hours total
- **Some Experience**: 2-3 hours total
- **Advanced Features**: +2-3 hours

---

## Next Steps After Completion

1. Add a GUI with Tkinter
2. Create a password strength checker
3. Build a password manager
4. Add encryption for saved passwords
5. Make it a command-line tool with arguments

Good luck building your password generator! 🔒
