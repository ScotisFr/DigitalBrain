Pseudocode is an informal, high-level description of a program's logic. It acts as a bridge between the problem statement and the actual code, helping you outline the steps to solve a coding task before implementation.
# General Principles

- **Clarity:** 
  Write pseudocode that is easy to read and understand. Avoid jargon or unnecessary complexity.
- **Simplicity:** 
  Focus on the core logic and omit irrelevant details. Simplify wherever possible.
- **Consistency:** 
  Use consistent naming conventions for variables and functions
- **Descriptive names:** 
  Choose names for variables, functions, and steps that make their purpose self-explanatory (e.g., `calculate_total` instead of `calcTot`).
- **Consistent indentation:** 
  Use consistent indentation to indicate blocks of code and hierarchy,visually representing the flow and making it easier to follow the logic.
- **Language agnostic**: 
  Good pseudocode should be understandable regardless of informatics language.

# Best Practices

- **Start with the problem statement**:
  Restate the problem in your own words before writing pseudocode. This ensures clarity.
- **Avoid code syntax:** 
  Focus on the logic, not specific syntax (e.g., write `loop through the list` instead of `for i in range(len(list))`).
- **Use natural language:** 
  Write in plain human language that describes actions (e.g., `Add 1 to the counter` instead of `counter++`).
- **Use bullet points or numbered steps:**
  Structuring pseudocode as a list improves readability.
- **Refine and review:** 
  Simplify and clarify until the pseudocode is easily understandable.
- **Think as a reader, not the writer:**
  Imagine someone else reading your pseudocode. Is it clear and understandable?
- **Test with real problems:** 
  Write pseudocode for real problems to practice and improve.

# Structure

1) **Start with a high-level outline**
	a) Define the main steps of your algorithm or process.
	b) Break down complex problems into smaller, manageable parts. 
	_(Example: Instead of "Solve the problem," write "Sort the list" → "Search for an item.")_
2) **Comments for explanation**
	a) Use inline comments or notes to clarify decisions or logic that might not be immediately obvious.
3) **Break down tasks**
	a) Divide complex tasks into smaller, reusable components (e.g., use functions or procedures for repetitive tasks).
4) **Include edge cases and error handling**
	a) Consider edge cases: mention how edge cases are handled (e.g., empty input, null values, invalid values, or extreme conditions).
	b) Error handling: describe how errors are managed (e.g., "If input is invalid, prompt user again").
5) **Document assumptions and dependencies**
	a) Assumptions: clearly state any assumptions you make about the input or the environment.
	b) Dependencies: note any dependencies or preconditions needed for the pseudocode to work.

# Common Constructs

**Variables**
Clearly state what variables are and their purpose. (e.g., `counter` to track iterations).

**Conditionals**
Use simple and clear conditional statements:
(Example: "If the item is found, print success. Else, continue searching.")

**Loops**
Clearly define the loop type and its purpose.

**Functions/procedures**
Define the purpose and parameters of functions. (Example: "Function find_max takes a list as input and returns the largest number.")