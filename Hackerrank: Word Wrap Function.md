# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

## 🎯 Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---


## 🧪 Program
```
import textwrap
def wrap_string(long_string, width):
    wrapped_text = textwrap.fill(long_string, width)
    return wrapped_text
long_string = input("Enter a long string: ")
width = int(input("Enter the desired width for wrapping: "))

wrapped_string = wrap_string(long_string, width)

print("\nWrapped String:")
print(wrapped_string)
```

## Sample Output
![image](https://github.com/user-attachments/assets/d909ecfb-6c80-49d7-8643-f79bdb9b5abe)

## Result

Thus the program has been executed successfully.

