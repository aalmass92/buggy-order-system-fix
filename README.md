# Buggy Order System Fix

## Project Overview
This project is a learning exercise focused on debugging Python code while practicing project management using GitHub and Trello. The goal was to identify, document, and fix bugs in an order management system.

## Learning Experience

### GitHub Integration
Throughout this project, I learned how to:
- Create a GitHub issue from the command line using GitHub CLI
- Track bugs using GitHub Issues
- Link commits to issues using keywords like "Closes #X"
- Use version control to document the debugging process


### Trello Project Management
This project integrated Trello for task management, helping to:
- Organize bugs and fixes into actionable tasks
- Track progress from identification to resolution
- Coordinate between issue tracking and development workflow

### Debugging Process
I identified and fixed three types of errors in the order management system:

#### 1. **Syntax Errors**
- **Issue:** [#1](../../issues/1) - Missing colon in `add_item` function definition
- **Location:** Line 16
- **Fix:** Added colon (`:`) at the end of the function definition
- **Learning:** Syntax errors prevent code from running entirely and are caught by the Python parser

- **Issue:** [#2](../../issues/2) - Missing closing parenthesis in `print_summary` method
- **Location:** Line 28
- **Fix:** Added closing parenthesis to the print statement
- **Learning:** Multiple syntax errors 

#### 2. **Runtime Errors**
- **Issue:** [#3](../../issues/3) - Typo in variable name (`itemz` vs `items`)
- **Location:** Line 26
- **Fix:** Changed `self.itemz` to `self.items`
- **Learning:** Runtime errors occur during execution when the code tries to access non-existent attributes or perform invalid operations

#### 3. **Logic Errors**
- **Issue:** [#4](../../issues/4) - Incorrect calculation in `calculate_total` method
- **Location:** Line 11
- **Fix:** Changed addition (`+`) to multiplication (`*`) for quantity × price calculation
- **Learning:** Logic errors are the hardest to catch because the code runs without crashing but produces incorrect results

## Key Takeaways

1. **Issue Tracking:** Using GitHub Issues helped me document each bug  with clear descriptions, reproduction steps, and expected vs actual behavior
2. **Version Control:** Committing fixes individually made it easy to track what was changed and why
3. **Project Management:** Integrating Trello with GitHub created a comprehensive workflow for managing the debugging process
4. **Error Classification:** Understanding the difference between syntax, runtime, and logic errors
## How to Run

```bash
python "Buggy Code.py"
```

## Issues
All bugs have been documented in the [Issues](../../issues) section of this repository.

View [Closed Issues](../../issues?q=is%3Aissue+is%3Aclosed) to see all resolved bugs.





