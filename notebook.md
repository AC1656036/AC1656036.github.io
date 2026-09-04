# My Notebook



## Navigation
[Home](index.md)


## Table of Contents

- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

  - [Headings](#headings)

  - [Text Formatting](#text-formatting)

  - [Code Examples](#code-examples)


  ## Vocab

<details>
  <summary>Java</summary>
    A programming language. Java and JavaScript are completely different languages. 
  
    
</details>

<details>
  <summary>Procedural languages</summary>
    Procedural Languages focus on procedures (functions) that operate on data in a linear top-down sequence. 
  
    
</details>

<details>
  <summary>Object oriented programming</summary>
    Object-oriented programming is a way of writing code where you group related data and actions into reusable "objects," kind of like organizing tools into labeled boxes. 
  
    
</details>


<details>
  <summary>Java class</summary>
    In Java, a class is like a blueprint that defines the structure and behavior (data and actions) of objects you can create from it.
  
    
</details>

<details>
  <summary>Java method</summary>
    A method in Java is a block of code inside a class that performs a specific task when it's called. 
  
    
</details>

<details>
  <summary>Console</summary>
    The area of a computer that notes from a program can be printed to. Kind of like a notebook. 
  
    
</details>
  
<details>
  <summary>Algorithm</summary>
    Step-by-step instructions. 
  
    Example: The steps to making cookies and a method we use for long math problems are both examples of algorithms.
</details>

<details>
  <summary>Sequencing</summary>
    The order things happen in.

    Example: Brushing your teeth might consist of these steps: Put toothpaste on the toothbrush. Use the toothbrush to clean your teeth.
</details>

<details>
  <summary>Selection</summary>
    The parts of an algorithm where decisions are made.

    Example: If you already have your shoes on, then you are ready. If not, put them on.
</details>

<details>
  <summary>Iteration</summary>
    The parts of an algorithm which repeat.

    Example: If you need to buy 10 apples, instead of buying them one at a time, you would buy multiple at once.
</details>

<details>
  <summary>Internal Link</summary>
    A link that takes a user to a different page in the same site.

    Example: The following link will take users to the hobbies page within the site. <a href=“hobbies.html”>Take me to my Hobbies page</a>
</details>

<details>
  <summary>External documentation</summary>
    External documentation is the information about your code that's kept outside the actual source files, like user guides, API references, or manuals, to help others understand how to use or work with your program.

    Example: // this is a java comment
</details>

<details>
  <summary>Variables</summary>
    A variable is like a box that holds the information you want.

    Example: var = information; name = arthur; fave_food = pizza;
</details>

<details>
  <summary>String</summary>
    A string is a set of words or numbers that are surrounded by quotation marks. "Here is 1 string."

    Example: "I am a string."
</details>

<details>
  <summary>Int</summary>
    Int is short for integer, which is a data type that means a number value.

    Example: 12
</details>

<details>
  <summary>Double</summary>
    A double variable type is a decimal value.
  
    Example: 4.56
</details>

<details>
  <summary>Char</summary>
    A data type of just one character.
  
    Example: "A"
</details>

<details>
  <summary>Boolean</summary>
    A data type that represents the value of True or False. In Python it must be capitalized: True. In JavaScript and Java it's all lowercase: true.
  
    Example: "Rain = true, clearSky = false"
</details>

<details>
  <summary>camelCase</summary>
    CamelCase is a way of writing compound words or phrases where each word starts with a capital letter and there are no spaces
  
    Example: "myVariable" or "codeVarOne"
</details>

<details>
  <summary>Concatenation</summary>
    Adding strings together to create longer strings. "Hello my name" + "is" + "Dominique"
  
    Example: print("This is " + "an example of " + "concatenation.") #Output: This is an example of concatenation.
</details>

<details>
  <summary>Type conversion</summary>
    Type conversion is the process of changing a value from one data type to another, like turning an `int` into a `double` or a `String` into an `int`.
  
   
</details>











 

## Code Examples
 
  ### Print Statements
  ```java
  public class Hello {
      public static void main(String[] args) {
          System.out.println("Hello World!");
      }
  }
  ```
  **System** accesses a Java class that's built into the language
  
  **out** is short for "output".
  
  **println** is short for "print line".





 





















## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.


