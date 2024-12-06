## Overview
This project as per the instructions, implements an in memory key value data base with transaction support, and it allows for the user to put in operations like , get(), put(), begin_transaction(), commit(), and rollback() in order to mimic transaction behavior seen in relational databases.
---
## How to Run the Code
### Prerequisites
- Have Python 3.7 or later installed.
- Have a IDE (e.g., PyCharm, VSCode) or terminal for running the script.

### Instructions
1. Clone or download the repository to your local machine.
2. Open a terminal or command prompt and go to the directory containing the script.
3. Run the program using the command:
   ```bash
   python main.py
   ```
4. Look at the output of the test cases in the terminal to verify functionality.

---

## How This Could Become An Offical Assingment

1. **Clarify Nested Transaction Behavior:**
   - I would first state in more defined termed whether the nested transactions should be supported or explicitly prohibited.
   - If those transcations were supported, I would include examples and requirements for merging nested transactions into the main state. I would make sure that those requirements were extremely detailed as well to avoid confusion. 

2. **Include Performance Metrics:**
   - I would then add a requirement to measure performance, somthing like the time complexity for operations (`put`, `get`, `commit`, `rollback`).

3. **Expand Test Cases:**
   - I would also Provide additional edge cases, examples would be something like handling large datasets, non-string keys, or non-integer values in order to verify resilience of the database.

4. **Alternative Methods:**
   - Alternativley, implementing this assignment in other languages (Java or C++) and then comparing results or behaviors.
   - I could also include an optional extension for concurrency support in order to mirror real-world scenarios more closely.

5. **Grading Suggestions:**
   - I would simply automate the grading process by including test scripts that validate the functionality against a set of predefined inputs and outputs.
   - If that was too complicated I would have the graders have a list of defined characteristics and outputs for the program so when they go on Github and test it they can just grade it solely off the output and whatnot. 

---
