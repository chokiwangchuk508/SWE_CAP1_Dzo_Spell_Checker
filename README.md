Readability
Problem: Code gets unreadable when working with big dictionaries or nested structures.
Solution: Code should be documented, HELPER-functions used and complex operations divided into smaller steps that do not make the code incomprehensible.
Iteration with Modification
Problem: Modifying a dictionary during iteration can lead to runtime errors or unexpected behavior.
Solution: Make a list of keys to be modified after the end of iteration or use dictionary comprehensions for transformations.
Uniqueness of Keys
Problem: Ensuring keys are unique to avoid accidentally overwriting data.
Solution: Before adding a key, implement checks, or use another data structure, such as lists, if one needs to allow duplicates.
