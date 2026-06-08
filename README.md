# 📚 String Library Project

A C++ header-only class that adds useful string operations on top of the standard `std::string`. This was built as a practice project to get comfortable with classes, static methods, and working with strings in C++.

---

## Features

- Convert strings to uppercase or lowercase (all characters or first letter of each word)
- Invert the case of every character in a string
- Count capital letters, small letters, vowels, or a specific character
- Count and print words in a string
- Split a string by a custom delimiter
- Join a list of strings with a delimiter
- Trim spaces from the left, right, or both sides
- Reverse the order of words in a string
- Replace all occurrences of a word or substring
- Remove punctuation from a string
- Print vowels or first letters of each word

---

## Technologies

- C++
- `<string>`, `<vector>`, `<iostream>` from the C++ Standard Library

---

## How It Works

Everything is inside a single file: `clsString.h`. You include it in your project and either use it as an object or call the methods directly without creating one.

```cpp
// Using as an object
clsString s("hello world");
s.UpperAllString();

// Using static methods directly
string result = clsString::UpperAllString("hello world");
```

Each method is available in two ways: as a static function that takes a string as input, and as an instance method that works on the stored value.

---

## Learning Outcomes

Working on this project helped practice:

- Writing and organizing a C++ class with private and public members
- Using static methods alongside regular instance methods
- Working with `std::string` methods like `find`, `substr`, `erase`, and `replace`
- Using `std::vector` to store and return collections of strings
- Default parameter values in functions
- Using enums to represent options
