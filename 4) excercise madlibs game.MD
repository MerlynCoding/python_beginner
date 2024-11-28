## 9. **Madlibs Game**
The Madlibs game is a fun word game where users fill in blanks with random words to create a humorous story.

### **Code:**
```python
# Madlibs game
# A word game where you create a story by filling in blanks with random words

adjective1 = input("Enter an adjective (description): ")
noun1 = input("Enter a noun (person, place, or thing): ")
adjective2 = input("Enter another adjective: ")
verb1 = input("Enter a verb ending with 'ing': ")
adjective3 = input("Enter one more adjective: ")

print(f"Today I went to a {adjective1} zoo.")
print(f"In an exhibit, I saw a {noun1}.")
print(f"The {noun1} was {adjective2} and {verb1}.")
print(f"I was {adjective3}!")
```

### **Example Interaction:**
```
Enter an adjective (description): wild
Enter a noun (person, place, or thing): elephant
Enter another adjective: huge
Enter a verb ending with 'ing': dancing
Enter one more adjective: amazed

Output:
Today I went to a wild zoo.
In an exhibit, I saw an elephant.
The elephant was huge and dancing.
I was amazed!
```

### **Purpose:**
- Demonstrates how to use the `input()` function for interactive programs.
- Encourages creativity and provides a simple yet effective introduction to string manipulation with f-strings.
