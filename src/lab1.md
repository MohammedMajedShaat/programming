# Lab 1: Introduction, Algorithms & Flowcharts 🚀

> 🤲 **قبل ما تبدأ الدراسة..**  
> سمّ بسم الله وادعُ لنفسك:  
> *"اللهم لا سهل إلا ما جعلته سهلاً، وأنت تجعل الحزن إذا شئت سهلاً.. اللهم إني أسالك فهم النبيين وحفظ المرسلين."*  
>   
> **ولو حسيت الدنيا تشابكت ونسيت:**  
> *"يا جامع الناس ليوم لا ريب فيه اجمع عليّ ضالتي.. صلي على النبي ﷺ وخذ نفس عميق!"*

---

> 🤍 **Encouragement Message**  
> *Remember, you are not just studying to pass an exam... You are building real skills and engineering experience for your future. The exhaustion is temporary, but the knowledge and success stay with you. Take a deep breath, put your trust in Allah, and strive for excellence!* 💪✨

---

## 🎯 Lab Objectives

By the end of this lab, you will be able to:
1. Understand the 5 core stages of the **Programming Life Cycle**[cite: 61].
2. Define what an **Algorithm** is and understand why developers use it before coding[cite: 61].
3. Identify standard **Flowchart** symbols and their designated logical functions[cite: 61, 62].
4. Convert real-world problems into clear, logical steps (Algorithms & Flowcharts)[cite: 63, 64, 65].

---

## 📚 1. Programming Life Cycle

The software development process follows 5 essential stages[cite: 61]:
1. **Thinking:** Analyzing the problem statement and understanding requirements[cite: 61].
2. **Planning:** Defining inputs, outputs, and logical boundaries[cite: 61].
3. **Designing:** Drafting step-by-step algorithms and visual flowcharts[cite: 61].
4. **Coding:** Translating the algorithm into Java or another programming language[cite: 61].
5. **Testing:** Running test cases to discover and fix logical or syntax errors[cite: 61].

---

## 🧠 2. Algorithms & Flowcharts

* **Algorithm:** A detailed, step-by-step procedure used to solve a specific problem or perform a computation[cite: 61].
* **Why Algorithms?**
  1. Documents solution ideas clearly[cite: 61].
  2. Helps developers detect logical errors early before writing code[cite: 61].
  3. Allows comparing performance between different solutions[cite: 61].

* **Flowchart:** A visual representation of an algorithm using standard shapes and arrows[cite: 61, 62].

| Shape | Name | Function / Description |
| :---: | :---: | :--- |
| **Oval** | **Start / End** | Marks the beginning or termination of the flowchart[cite: 62]. |
| **Parallelogram** | **Input / Output** | Represents reading inputs or printing outputs[cite: 62]. |
| **Rectangle** | **Process / Instruction** | Represents computational operations or variable assignments[cite: 62]. |
| **Diamond** | **Decision** | Represents a conditional check (True/False or Yes/No branching)[cite: 62]. |

---

## 📖 3. Lab Examples (From Course Manual)

### Example 1: Print Numbers 1 to 20
* **Algorithm:**
  * **Step 1:** Initialize $X = 0$[cite: 63].
  * **Step 2:** Increment $X$ by 1 ($X = X + 1$)[cite: 63].
  * **Step 3:** Print $X$[cite: 63].
  * **Step 4:** If $X < 20$, go back to **Step 2**[cite: 63].

### Example 2: Convert Temperature from Fahrenheit ($^\circ\text{F}$) to Celsius ($^\circ\text{C}$)
* **Algorithm:**
  * **Step 1:** Read temperature in Fahrenheit ($F$)[cite: 64].
  * **Step 2:** Compute $C = \frac{5}{9} \times (F - 32)$[cite: 64].
  * **Step 3:** Print $C$[cite: 64].

### Example 3: Determine Student Pass / Fail Status
* **Algorithm:**
  * **Step 1:** Read grades of 4 courses: $M1, M2, M3, M4$[cite: 65].
  * **Step 2:** Compute average: $Grade = \frac{M1 + M2 + M3 + M4}{4}$[cite: 65].
  * **Step 3:** If $Grade < 60$, print `"FAIL"`, else print `"PASS"`[cite: 65].

---

## 🛠️ 4. Solved Lab Tasks

### Task 1: Temperature Average
**Problem:** Write an algorithm to print the average temperature of $T1, T2, T3$[cite: 66].

* **Solution Algorithm:**
  * **Step 1:** Input temperatures $T1, T2, T3$[cite: 66].
  * **Step 2:** Calculate $Average = \frac{T1 + T2 + T3}{3.0}$[cite: 66].
  * **Step 3:** Print $Average$[cite: 66].

---

### Task 2: Temperature Classifier (Cold vs. Hot)
**Problem:** Write an algorithm to print the average temperature of $T1, T2, T3$. Print `"cold"` if average is less than 17, and print `"hot"` if it is greater than or equal to 17[cite: 66].

* **Solution Algorithm:**
  * **Step 1:** Input temperatures $T1, T2, T3$[cite: 66].
  * **Step 2:** Calculate $Average = \frac{T1 + T2 + T3}{3.0}$[cite: 66].
  * **Step 3:** Print $Average$[cite: 66].
  * **Step 4:** If $Average < 17$ then:
    * Print `"cold"`[cite: 66].
    * Else:
    * Print `"hot"`[cite: 66].

---

### Task 3: Evaluate Expression $F(x, y) = 2x + 3y$
**Problem:** Write an algorithm to calculate the value of the function $F(x, y) = 2x + 3y$[cite: 66].

* **Solution Algorithm:**
  * **Step 1:** Read values for $x$ and $y$[cite: 66].
  * **Step 2:** Calculate $F = (2 \times x) + (3 \times y)$[cite: 66].
  * **Step 3:** Print $F$[cite: 66].

---

## 💡 5. Extra Practice Questions with Solutions

### Question 1: Find Largest of Two Numbers
**Problem:** Write an algorithm to read two numbers $A$ and $B$, and print the larger one.

* **Solution:**
  * **Step 1:** Read numbers $A$ and $B$.
  * **Step 2:** If $A > B$, then print $A$.
  * **Step 3:** Else if $B > A$, then print $B$.
  * **Step 4:** Else, print `"Both numbers are equal"`.

---

### Question 2: Calculate Area & Perimeter of a Rectangle
**Problem:** Write an algorithm that takes length ($L$) and width ($W$) of a rectangle, then outputs its area and perimeter.

* **Solution:**
  * **Step 1:** Read $L$ and $W$.
  * **Step 2:** Calculate $Area = L \times W$.
  * **Step 3:** Calculate $Perimeter = 2 \times (L + W)$.
  * **Step 4:** Print $Area$ and $Perimeter$.

---

## ✨ 6. What We Learned From This Lab

> 💡 **Key Takeaways:**
> * **Never jump straight to coding:** Thinking and planning on paper saves hours of debugging later[cite: 61].
> * **Logic First:** Algorithms provide a clear roadmap regardless of which programming language you end up using[cite: 61].
> * **Visual Clarity:** Flowcharts make complex decision paths easy to understand for team members and reviewers[cite: 61, 62].
