# my notebook
## Table of Contents
- [Day 1](#day-1)
  - [Notes](#notes)
  - [Practice](#practice)
- [Code Definitions](#code-definitions) 
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

## Flutter Notes

### What is Flutter?
- Definition:
- Why is it useful?
A framework made by Google for building apps that work on web, Android, and iOS - with one codebase.
  Uses the Dart programming language.

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |                                                  |                                           |
| MaterialApp      |                                                  |                                           |
| Scaffold         |                                                  |                                           |
| StatelessWidget  |                                                  |                                           |
| StatefulWidget   |                                                  |                                           |
| Navigator        |                                                  |                                           |
| AppBar           |                                                  |                                           |
| Column           |                                                  |                                           |
| Row              |                                                  |                                           |
| Container        |                                                  |                                           |
| Text             |                                                  |                                           |
| Image.network    |                                                  |                                           |

| Padding    |                    |                     |

| Center      |                    |                     |

---

### Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?




## Code Definitions

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
|   Variable    | A named container used to store a value that may change. | `var x = 5;` | Age | height |
|      | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
|   Data Type   | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |If you're small and you get an xl shirt its not gonna fit, not efficient  |  |
|   String   | A sequence of characters used to represent words or text. | `"Hello World"` |In social media, you see the words on the search engions, comments, descriptions, etc.  |  |
|   Integer   | Whole number values. | `int age = 16;` |Counting your steaks in apps like "duolingo  |  |
|   Double   | Number values with decimals. | `double age = 16.2;` | walking and running in games use decimals in that transition to make it smooth |  |
|   Boolean   | A value that can be true or false. | `bool isLoggedIn = false;` | "Are you a robot" tests at the beginning of websites/apps. |If you won or lost in an app.  |
|   List   | A collection of values in a specific order. | `List<String> names = [];` | If you make a playlist of certain songs, those certain songs will be easier to find faster. |  |
|   Null   | A special value that means “nothing.” | `String? name = null;` | Search bar is an example of this. |  |
|   Function   | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` | When you're about to search up something you've already searched before and it fills in what you wre about to say. |  |
|   Parameter   | The information passed into a function to change how it works. | `greet(String name)` |  |  |
|      | The result a function gives back. | `return total;` |  |  |
|      | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|      | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|      | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|      | A variable that belongs to a class/object. | `String name;` |  |  |
|      | A function that belongs to a class. | `void bark() {}` |  |  |
|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |




















## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
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

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.


Layout in Flutter:

Row - Horizontal Layout

Column - Vertical Layout

Container - wraps content with padding, margin, or color

Center - centers its child

Padding - adds space around a widget

Image.network - displays images from a URL

Text - displays text


Term: Widget(Basic building block of a flutter app. Everything is a widget.) Example from App: Text, Image, Container, Column

Term: MaterialApp(The root of the app. Sets up routes and themes.) Example from app: Found in main.dart

Term: Scaffold(Provides basic visual layout - like a header, body, floating button) Example from App: Each screen uses it

Term: Named routes(Predefined paths to navigate between screens.) Example from App: '/',,'/page2','/page3', etc.

Term: Navigator(Manages screen transitions) Example from App: Navigator .pushNamed(context,  ' /pages2');

Term: StatefulWidget(A widget that can change over time) Example from App: Used in MyHomePage()

Term: StatelessWidget(A widget that doesn't change) Example from App: Most of the screen files

Term: AppBar(Top navigation bar) Example from App: Title of each page appears here

Term: main()(The function that runs the app) Example from App: Found in main.dart
