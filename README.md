# **Java Boilerplate Code Generator - Version 0.0.2**

Welcome to  **Java Boilerplate Code Generator** , the go-to extension for generating ready-to-use Java snippets efficiently. With  **Version 0.0.2** , we’ve added powerful input handling features, new code templates, and refined existing snippets to enhance your Java development workflow.

---

## 🔥 **What’s New in Version 0.0.2** 🔥

### 🆕 **New Features & Improvements**

1. **Advanced Input Handling** :

* Snippets to easily handle **array inputs** and  **2D matrix inputs** .
* New snippets for printing arrays and 2D jagged arrays.

1. **Improved Loop Snippets** :

* Standard `for`, `foreach`, and `while` loops now come with default ranges and placeholders for quick modifications.

1. **Enhanced Class Templates** :

* `Public`, `Private`, and `Protected` class templates are streamlined for consistency.
* Integrated **Scanner** for user input in the **main method** boilerplate.

1. **Updated Printing Templates** :

* Added simple print and println statements for quicker outputs.

---

## 🚀 **How to Use the Extension**

1. **Install the Extension** :
   Download and install the extension from the [VS Code Marketplace](https://chatgpt.com/c/675d7ae7-5cd4-8002-a915-0979abfb7828#).
2. **Trigger a Snippet** :

* Start typing the prefix (e.g., `puc`, `for`, `arrin`) and press **Enter** or  **Tab** .
* The corresponding code snippet will expand in your editor.

1. **Modify Placeholders** :

* Use the highlighted fields to customize the code according to your needs.

---

## 🛠️ **Full List of Snippets**

| **Snippet Prefix** | **Purpose**           | **Generated Code**                                  |
| ------------------------ | --------------------------- | --------------------------------------------------------- |
| `puc`                  | Public Class Boilerplate    | Generates a public class with Scanner for input.          |
| `prc`                  | Private Class Boilerplate   | Generates a private class template.                       |
| `proc`                 | Protected Class Boilerplate | Generates a protected class template.                     |
| `start`                | Main Method Boilerplate     | Generates the main method with Scanner for input.         |
| `print`                | Print Statement             | `System.out.print("Enter your text here");`             |
| `println`              | Print Line Statement        | `System.out.println("Enter your text here");`           |
| `for`                  | For Loop                    | Generates a standard for loop with a default range of 10. |
| `foreach`              | For-Each Loop               | Generates a for-each loop for iterating over an array.    |
| `while`                | While Loop                  | Generates a while loop with a default range of 10.        |
| `arrin`                | Array Input                 | Generates input handling for a single-dimensional array.  |
| `printarr`             | Printing Array              | Generates code to print all elements of an array.         |
| `arr2din`              | 2D Matrix Input             | Generates input handling for a two-dimensional matrix.    |
| `print2d`              | Print 2D Jagged Array       | Generates code to print a 2D jagged array.                |

---

## 📚 **Snippet Details**

Here are some examples of how the new and updated snippets work:

### 🔹 **1. Public Class Boilerplate** (`puc`)

Generates a public class template with Scanner for user input:

```java
import java.util.Scanner;
public class program {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        // TODO: your code here
    }
}
```

### 🔹 **2. For Loop** (`for`)

Generates a standard for loop:

```java
int range = 10; //Range by default is set to 10
for (int i = 0; i < range; i++) {
    // TODO: your code here
}
```

### 🔹 **3. Advanced Input Handling - Array Inputs** (`arrin`)

Generates code for taking single-dimensional array input:

```java
int n = size;
int[] arr = new int[n];
System.out.println("Enter " + n + " integers:");
for (int i = 0; i < n; i++) {
    arr[i] = input.nextInt();
}
```

### 🔹 **4. Advanced Input Handling - Matrix Inputs** (`arr2din`)

Generates code for taking a two-dimensional matrix as input:

```java
int rows = rows;
int cols = cols;
int[][] matrix = new int[rows][cols];
System.out.println("Enter the matrix elements:");
for (int i = 0; i < rows; i++) {
    for (int j = 0; j < cols; j++) {
        matrix[i][j] = input.nextInt();
    }
}
```

### 🔹 **5. Printing Array** (`printarr`)

Generates a for-each loop for printing array elements:

```java
for (int value : arr) {
    System.out.print(value + " ");
}
```

---

## 🎯 **Planned Features for Future Versions**

1. **Customizable Snippets** :

* Allow users to configure placeholders dynamically.

1. **File Handling Templates** :

* Add snippets for reading/writing files using `BufferedReader` and `PrintWriter`.

1. **Enhanced Loops** :

* Include `do-while` loops and nested loops.

1. **Real-Time IntelliSense Integration** :

* Snippets that adapt to the context of your code.

---

## 🏆 **Why Use Java Boilerplate Code Generator?**

* **Time-Saving** : Reduces repetitive coding tasks.
* **Error-Free** : Generates syntax-perfect code templates.
* **Beginner-Friendly** : Makes Java coding easier for students and newcomers.
* **Versatile** : Covers input handling, loops, and common boilerplate code.

---

## ❤️ **Contribute to This Project**

We welcome your contributions! To add more snippets:

1. Fork the repository.
2. Add or update code in the `snippets.json` file.
3. Submit a pull request with your changes.

---

## 📈 **Metrics & Impact**

* **150+ Installs** (and growing!)
* **Positive Feedback** : Students and developers report improved productivity.
* **Community-Driven** : Contributions from developers around the globe.

---

## 🤝 **Contact**

Have suggestions or feedback? Let’s connect!

* **Creator** : Vedant Sareen
* **Email** : [securecybernetics@gmail.com](mailto:securecybernetics@gmail.com)
* **GitHub** : [CYBERSAREEN](https://github.com/CYBERSAREEN)

---

## 📜 **License**

This extension is licensed under the  **MIT License** . Feel free to use, modify, and distribute it while giving proper credit.

---
