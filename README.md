# **Java Boilerplate Code Generator - Version 0.0.3**

Welcome to  **Java Boilerplate Code Generator** , the must-have extension for Java developers looking to save time and reduce boilerplate code writing. With  **Version 0.0.3** , we've introduced new input templates, refined existing features, and added tools for seamless coding.

---

## 🔥 **What’s New in Version 0.0.3** 🔥

### 🆕 **New Features & Enhancements**

1. **Advanced Input Snippets** :

* Support for **integer** and **string inputs** with ease using `takeint` and `takestr` snippets.
* Added support for **array output** with `arrout`.

1. **Expanded Printing Templates** :

* Print statements (`print` and `println`) have been optimized for common scenarios.

1. **Refined Loop Templates** :

* Included placeholders for dynamic ranges and values for all loop types (`for`, `foreach`, `while`).

1. **Matrix Handling** :

* Enhanced matrix input handling with `arr2din` for both structured and jagged arrays.

---

## 🚀 **How to Use the Extension**

1. **Install the Extension** :

* Download and install from the [VS Code Marketplace](https://example.com/).

1. **Trigger a Snippet** :

* Start typing the prefix (e.g., `puc`, `for`, `takeint`) and press **Enter** or **Tab** to expand the snippet.

1. **Modify Placeholders** :

* Placeholders are highlighted for quick customization of variables and logic.

---

## 🛠️ **Full List of Snippets**

| **Snippet Prefix** | **Purpose**           | **Generated Code**                          |
| ------------------------ | --------------------------- | ------------------------------------------------- |
| `puc`                  | Public Class Boilerplate    | Generates a public class with Scanner for input.  |
| `prc`                  | Private Class Boilerplate   | Generates a private class template.               |
| `proc`                 | Protected Class Boilerplate | Generates a protected class template.             |
| `start`                | Main Method Boilerplate     | Generates the main method with Scanner for input. |
| `takeint`              | Integer Input               | Reads an integer input using Scanner.             |
| `takestr`              | String Input                | Reads a string input using Scanner.               |
| `print`                | Print Statement             | Generates a single-line print statement.          |
| `println`              | Print Line Statement        | Generates a print line statement.                 |
| `for`                  | For Loop                    | Generates a standard for loop.                    |
| `foreach`              | For-Each Loop               | Generates a for-each loop.                        |
| `while`                | While Loop                  | Generates a while loop.                           |
| `arrin`                | Array Input                 | Handles input for a single-dimensional array.     |
| `arrout`               | Array Output                | Prints a single-dimensional array.                |
| `arr2din`              | 2D Matrix Input             | Handles input for a 2D matrix.                    |
| `arr2dout`             | 2D Matric output            | Handles Output for 2D array                       |

---

## 📚 **Snippet Examples**

### 🔹 **Public Class Boilerplate** (`puc`)

```java
import java.util.Scanner;
public class program {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        // TODO: your code here
    }
}
```

### 🔹 **Integer Input** (`takeint`)

```java
int num = input.nextInt();
```

### 🔹 **Array Output** (`arrout`)

```java
for (int value : arr) {
    System.out.print(value + " ");
}
```

### 🔹 **2D Matrix Input** (`arr2din`)

```java
int rows = size;
int cols = size;
int[][] matrix = new int[rows][cols];
System.out.println("Enter matrix elements:");
for (int i = 0; i < rows; i++) {
    for (int j = 0; j < cols; j++) {
        matrix[i][j] = input.nextInt();
    }
}
```

---

## 🎯 **Planned Features for Future Versions**

1. **Dynamic Customization** :

* Allow users to configure placeholders and templates.

1. **Streamlined File I/O** :

* Add snippets for file reading and writing.

1. **Functional Programming** :

* Lambda expression and stream templates for modern Java workflows.

---

## 🏆 **Why Choose Java Boilerplate Code Generator?**

* **Efficiency** : Speeds up coding by reducing repetitive tasks.
* **Accuracy** : Minimizes syntax errors with pre-written, tested templates.
* **Flexibility** : Offers diverse boilerplate code for different use cases.
* **Beginner-Friendly** : Ideal for students and newcomers to Java.

---

## ❤️ **Contribute to the Project**

Want to improve this extension? Follow these steps:

1. Fork the repository on GitHub.
2. Add or update snippets in the `snippets.json` file.
3. Submit a pull request with your changes.

---

## 📈 **Community Impact**

* **150+ Installs** : Trusted by Java developers globally.
* **Student Favorite** : Simplifies Java learning with easy-to-use templates.
* **Collaborative Growth** : Feedback and contributions from the developer community.

---

## 👌Features

1. **Beginner-Friendly Snippets**

   * Provides ready-to-use boilerplate code for public, private, and protected classes.
   * Simplifies Java programming with essential structures and best practices.
2. **Main Method Templates**

   * Prepares main method boilerplates with `Scanner` input handling for quicker development.
3. **Input Handling Snippets**

   * **Take Integer Input (`takeint`)** : Quickly insert code for accepting integer input using `Scanner`.
   * **Take String Input (`takestr`)** : Easily add a snippet for reading strings.
4. **Output Snippets**

   * **Print Statement (`print`)** : Generate single-line output code.
   * **Print Line Statement (`println`)** : Add a `println` statement for output with a newline.
5. **Loop Snippets**

   * **For Loop (`for`)** : Insert a standard `for` loop template with a customizable range.
   * **For-Each Loop (`foreach`)** : Generate code for iterating over arrays or collections.
   * **While Loop (`while`)** : Add a basic `while` loop with default range variables.
6. **Array Input and Output Handling**

   * **Array Input (`arrin`)** : Quickly generate code to accept integer arrays as input.
   * **Array Output (`arrout`)** : Insert a snippet for printing array elements in a single line.
7. **2D Matrix Input and Output**

   * **Matrix Input (`arr2din`)** : Template for accepting elements of a 2D matrix.
   * **Matrix Output (`arr2dout`)** : Snippet to display a jagged 2D array in matrix format.

---

This feature-rich extension helps Java developers—especially beginners—write clean, efficient, and reusable code faster by reducing boilerplate and improving productivity.

## 🤝 **Contact**

Feel free to reach out for suggestions or queries:

* **Creator** : Vedant Sareen
* **Email** : [securecybernetics@gmail.com](mailto:securecybernetics@gmail.com)
* **GitHub** : [CYBERSAREEN](https://github.com/CYBERSAREEN)

---

## 📜 **License**

Licensed under the  **MIT License** . Use, modify, and distribute this extension while giving proper credit.

---
