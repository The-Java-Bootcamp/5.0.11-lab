# Lab: 5.0.11

**Objective:**

- Understand the concept and importance of Regular Expressions in Java development.
- Learn how to implement Regular Expressions using Java's `java.util.regex` package.
- Explore practical applications of Regular Expressions in real-world Java projects.
- Identify common pitfalls and best practices when working with Regular Expressions.
- Gain hands-on experience with a complete Java example that demonstrates Regular Expressions.

**Prerequisites:**

- Basic understanding of Java programming.
- Familiarity with String manipulation in Java.

**What You'll Achieve:**

By the end of this lab, you will have:

- Develop a solid understanding of Regular Expressions in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in pattern matching and text processing.

**Assignment Details**

1. Open the provided `RegexExplorer.java` file in your preferred Java development environment.
2. In the `main` method, you'll find several String variables with sample text.
3. Implement the following Regular Expression tasks:
   - Create a pattern to match all email addresses in the given text.
   - Use a regex to validate if a given string is a valid Java identifier.
   - Implement a pattern to find all words that start with a vowel.
   - Create a regex to match and extract all dates in the format DD-MM-YYYY.
   - Use a regular expression to replace all multiple whitespace characters with a single space.
4. For each task, print the results of your regex operations.
5. Test your implementation with the provided sample text and additional inputs of your own.

**Example Output**

```
Email addresses found: [john@example.com, alice@email.co.uk]
Is 'validVariable' a valid Java identifier? true
Is '123invalid' a valid Java identifier? false
Words starting with a vowel: [apple, orange, is, an, excellent, example]
Dates found: [12-03-2023, 25-12-2022]
Text after whitespace normalization: This is a sample text with some extra spaces.
```

**Starter Code**

The `RegexExplorer.java` file contains the following starter code:

```java
package academy.javapro.lab;

import java.util.regex.*;

public class RegexExplorer {
    public static void main(String[] args) {
        String emailText = "Contact us at john@example.com or support@company.org for assistance.";
        String identifierText = "validVariable";
        String vowelText = "The quick brown fox jumps over the lazy dog";
        String dateText = "Important dates: 12-03-2023 and 25-12-2022";
        String whitespaceText = "This   is   a   sample    text    with   some    extra   spaces.";

        // TODO: Implement regex tasks here
    }
}

```

**Hints**

- Use the `Pattern` and `Matcher` classes from the `java.util.regex` package for complex regex operations.
- For simple pattern matching, you can use the `String.matches()` method.
- Remember to escape special characters in your regex patterns.
- Use regex quantifiers like `*`, `+`, and `?` to specify repetitions.
- Character classes like `\d` for digits, `\w` for word characters, and `\s` for whitespace can be very helpful.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required regex operations in the `RegexExplorer.java` file
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.