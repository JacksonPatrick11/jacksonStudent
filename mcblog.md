---
layout: page
title: 🌟 Multiple Choice Blog and Review 🌟
description: mc blog
hide: false
---


## What I Learned from the Quiz
During the AP CSP practice test, I learned about various topics, such as collaboration, program design, binary numbers, and algorithmic efficiency. These concepts are essential for understanding computer science principles and solving problems effectively.

## Areas to Improve
I realized that I need to work on **Data Compression**, **Developing Algorithms**, and **Algorithmic Efficiency**. These topics were challenging, and I should focus on understanding the underlying principles and practicing more problems. I also understand that reading the questions thoroughly is vital to understanding and answering questions.



## Performance Breakdown
### Topic Breakdown

| Topic                                 | Number of Questions | Average Performance % |
|---------------------------------------|---------------------|-----------------------|
| 1.1: Collaboration                    | 0                   | NA                    |
| 1.2: Program Function and Purpose     | 0                   | NA                    |
| 1.3: Program Design and Development   | 1                   | 100%                  |
| 1.4: Identifying and Correcting Errors| 4                   | 75%                   |
| 2.1: Binary Numbers                   | 4                   | 75%                   |
| 2.2: Data Compression                 | 3                   | 33%                   |
| 2.3: Extracting Information from Data | 7                   | 86%                   |
| 2.4: Using Programs with Data         | 2                   | 50%                   |
| 3.1: Variables and Assignments        | 3                   | 67%                   |
| 3.2: Data Abstraction                 | 0                   | NA                    |
| 3.3: Mathematical Expressions         | 1                   | 0%                    |
| 3.4: Strings                          | 0                   | NA                    |
| 3.5: Boolean Expressions              | 3                   | 100%                  |
| 3.6: Conditionals                     | 2                   | 50%                   |
| 3.7: Nested Conditionals              | 0                   | NA                    |
| 3.8: Iteration                        | 2                   | 100%                  |
| 3.9: Developing Algorithms            | 4                   | 25%                   |
| 3.10: Lists                           | 1                   | 0%                    |
| 3.11: Binary Search                   | 0                   | NA                    |
| 3.12: Calling Procedures              | 5                   | 60%                   |
| 3.13: Developing Procedures           | 2                   | 50%                   |
| 3.14: Libraries                       | 0                   | NA                    |
| 3.15: Random Values                   | 2                   | 50%                   |
| 3.16: Simulations                     | 2                   | 100%                  |
| 3.17: Algorithmic Efficiency          | 2                   | 0%                    |
| 3.18: Undecidable Problems            | 1                   | 0%                    |
| 4.1: The Internet                     | 3                   | 67%                   |
| 4.2: Fault Tolerance                  | 1                   | 100%                  |
| 4.3: Parallel and Distributed Computing| 0                  | NA                    |
| 5.1: Beneficial and Harmful Effects   | 3                   | 33%                   |
| 5.2: Digital Divide                   | 1                   | 100%                  |
| 5.3: Computing Bias                   | 0                   | NA                    |
| 5.4: Crowdsourcing                    | 2                   | 100%                  |
| 5.5: Legal and Ethical Concerns       | 2                   | 100%                  |
| 5.6: Safe Computing                   | 3                   | 33%                   |

**Summary of Summaries:** 
- **Key Learnings:** Enhanced understanding of various computer science topics.
- **Areas for Improvement:** Focus on Data Compression, Developing Algorithms, and Algorithmic Efficiency.
- **Pop Quiz Prep:** Ready to review and reinforce knowledge of correct answers.

 🌟💻🚀

[MC Review](https://apclassroom.collegeboard.org/103/assessments/results/61960596/performance)



### mc question review 

## Question 1: Swap Values of `first` and `second`

### Problem
The code below is intended to swap the values of `first` and `second` using a temporary variable `temp`:

1. `temp ← first`
2. `first ← second`
3. **MISSING CODE**

What should replace the missing code?

### Options:
- **A**: `second ← first`
- **B**: `second ← temp`
- **C**: `temp ← first`
- **D**: `temp ← second`

---

### Correct Answer: **B**

### Explanation:
1. `temp ← first` saves the value of `first`.
2. `first ← second` moves the value of `second` into `first`.
3. `second ← temp` completes the swap by assigning the original value of `first` (stored in `temp`) to `second`.

**Why B?**  
It correctly swaps the values of `first` and `second`.

---
## Question 6: Internet Engineering Task Force (IETF)

### Problem
Which of the following best describes the role of the Internet Engineering Task Force (IETF)?

### Options:
- **A**: Developing standards and protocols for Internet communication
- **B**: Preventing copyrighted materials from being illegally distributed online
- **C**: Preventing malicious software from being distributed online
- **D**: Verifying the ownership of encrypted keys used in secured messages

---

### Correct Answer: **A**

### Explanation:
The **IETF** focuses on developing and promoting **standards and protocols** to ensure seamless communication across the Internet. It does not enforce laws, prevent malware, or verify encrypted key ownership.

**Why A?**  
It correctly describes the IETF’s primary role in Internet standardization.

**Why C is incorrect:**  
The IETF does not handle malware prevention or security enforcement directly.

---
## Question 14: Comparing Loop Algorithms

### Problem
Consider the two programs below:

**Program A:**
1. `i ← 1`
2. `REPEAT UNTIL i > 10`  
   - `DISPLAY(i)`  
   - `i ← i + 1`

**Program B:**
1. `i ← 1`
2. `REPEAT UNTIL i > 10`  
   - `i ← i + 1`  
   - `DISPLAY(i)`

### Question:
Which of the following best compares the values displayed by Program A and Program B?

### Options:
- **A**: Program A and Program B display identical values.
- **B**: Program A and Program B display the same values in different orders.
- **C**: Program A and Program B display the same number of values, but the values differ.
- **D**: Program A and Program B display a different number of values.

---

### Correct Answer: **D**

### Explanation:
- **Program A**: Displays the value of `i` **before** incrementing it, starting with `1` and ending at `10`.  
  Output: `1, 2, 3, ..., 10`.

- **Program B**: Increments the value of `i` **before** displaying it, starting with `2` and ending at `11`.  
  Output: `2, 3, 4, ..., 11`.

Since the programs display **a different number of values** (Program A: 10 values, Program B: 9 values), the correct answer is **D**.

**Why B is incorrect:**  
The programs do not display the same values or even the same number of values, making this answer invalid.

---
## Question 22: Procedure to Determine the Weather

### Problem
A student is creating a procedure to determine if the weather for a particular month was "very hot." The procedure takes a list of daily high temperatures and returns:
- **True**: If at least 50% of the days have temperatures of 90 degrees or higher.
- **False**: Otherwise.

The program includes a missing code segment in the return statement:

**Code:**
1. `PROCEDURE IsHot(temperatureList)`
2. `{`
3. `    total ← 0`
4. `    counter ← 0`
5. `    FOR EACH temperature IN temperatureList`
6. `    {`
7. `        IF (temperature ≥ 90)`
8. `        {`
9. `            counter ← counter + 1`
10. `        }`
11. `        total ← total + 1`
12. `    }`
13. `    RETURN (MISSING CODE)`
14. `}`


### Question:
Which of the following replaces the **MISSING CODE** to make the program work as intended?

### Options:
- **A**: `counter < 0.5 * total`
- **B**: `counter > 0.5 * total`
- **C**: `total < 0.5 * counter`
- **D**: `total > 0.5 * counter`

---

### Correct Answer: **B**

### Explanation:
1. **`counter`** represents the number of days where the temperature was 90 degrees or higher.
2. **`total`** represents the total number of days in the list.
3. To determine if the weather is "very hot," the program should check if **`counter > 50% of total`** (i.e., `counter > 0.5 * total`).

**Why B?**  
This correctly checks if the majority of days were very hot.

**Why C is incorrect:**  
The expression `total < 0.5 * counter` is illogical because `total` (total number of days) will always be greater than or equal to `counter` (a subset of those days).

---
## Question 25: Shortening Strings Using Byte Pair Encoding

### Problem
**Byte pair encoding** is a data compression technique that replaces pairs of characters that appear multiple times in a string with a unique character. For example:
- String: `"THIS_IS_THE_BEST_WISH"`
- Encoding:
  - Replace `TH` with `%` → `%IS_IS_%E_BEST_WISH`
  - Replace `IS` with `#` → `%#_#_%E_BEST_W#H`

The algorithm saves a mapping of replaced pairs to their unique characters. The task is to determine which string **cannot** be shortened using this technique.

---

### Options:
- **A**: `"BANANA"`
- **B**: `"LEVEL_UP"`
- **C**: `"MEET_ME_LATER"`
- **D**: `"NEITHER_HERE_NOR_THERE"`

---

### Correct Answer: **D**

### Explanation:
- **A**: `"BANANA"`  
  - Replace `AN` with `*` → `B*ANA`  
  - Replace `NA` with `#` → `B*#A`  
  This string can be shortened.

- **B**: `"LEVEL_UP"`  
  - Replace `EL` with `*` → `LEV*_UP`  
  This string can be shortened.

- **C**: `"MEET_ME_LATER"`  
  - Replace `ME` with `*` → `*ET_*_LATER`  
  This string can be shortened.

- **D**: `"NEITHER_HERE_NOR_THERE"`  
  - This string has no recurring character pairs that can be replaced. Therefore, it **cannot** be shortened using byte pair encoding.

**Why C is incorrect:**  
The string `"MEET_ME_LATER"` can be shortened by replacing `ME` and `ET` as shown above.

---
## Question 30: Video-Streaming Service by Genre

### Problem
A video-streaming service analyzes its database to compare the number of viewers of science fiction videos with the number of viewers of other genres. The program uses the procedure `Analysis(category)`, which:
- Returns the number of unique users who viewed videos of a given category in the past year.
- Takes **1 hour per call**, regardless of the category size.

---

### Options:
- **A**: 1 hour
- **B**: 2 hours
- **C**: 4 hours
- **D**: 5 hours

---

### Correct Answer: **D**

### Explanation:
1. The program calls `Analysis("science fiction")` once (**1 hour**).
2. The program iterates through 4 genres (`comedy`, `drama`, `mystery`, `romance`), calling `Analysis(genre)` for each genre (**4 hours** total).
3. **Total time:** `1 hour + 4 hours = 5 hours`.

**Why C is incorrect:**  
C assumes only 4 calls to `Analysis`, but there are 5 in total (1 for science fiction + 4 for the genres).

---
## Question 32: Comparing Smartphone and Reading Data in a Graph

### Problem
A scatter plot shows the relationship between:
- **X-axis**: Number of hours spent using a smartphone per day.
- **Y-axis**: Number of hours spent reading per day.
Each point is labeled with:
- **×**: Participant interested in a book review app.
- **o**: Participant not interested in the app.

The task is to identify which hypothesis is most consistent with the data.

---

### Options:
- **A**: Participants who read more were generally more likely to say they are interested in the application.
- **B**: Participants who read more were generally less likely to say they are interested in the application.
- **C**: Participants who use a smartphone more were generally more likely to say they read more.
- **D**: Participants who use a smartphone more were generally less likely to say they read more.

---

### Correct Answer: **A**

### Explanation:
- Participants with higher reading hours (higher Y-axis values) are more frequently represented with **×**, indicating interest in the app.
- No significant correlation exists between smartphone use (X-axis) and interest or reading habits, eliminating options **C** and **D**.

**Why D is incorrect:**  
The graph does not show any meaningful relationship between smartphone usage and reading hours.

---
## Question 37: Comparing Code Segments to Compute Average from List

### Problem
Two code segments compute and display the average of the numbers in a list `numList`. Both segments perform similar tasks but may differ in how they compute the average.

---

### Options:
- **A**: Code segment I displays the correct average, but code segment II does not.
- **B**: Code segment II displays the correct average, but code segment I does not.
- **C**: Both code segments display the correct average, but code segment I requires more arithmetic operations than code segment II.
- **D**: Both code segments display the correct average, but code segment II requires more arithmetic operations than code segment I.

---

### Correct Answer: **C**

### Explanation:
- Both programs correctly compute and display the average.
- Code segment I performs the division within the loop, requiring multiple division operations (one for each iteration).
- Code segment II performs the division after the loop, requiring only one division operation.

**Why A is incorrect:**  
Code segment II also computes the correct average.

---
## Question 64: Cloud Computing and the Internet

### Problem
Which of the following statements describe how cloud computing has affected Internet communication?  
**Select two answers.**

---

### Options:
- **A**: Cloud computing has eliminated the need to provide redundancy in Internet routing.
- **B**: Cloud computing has helped enhance collaboration.
- **C**: Cloud computing has introduced new data-security concerns.
- **D**: Cloud computing has reduced concerns about intellectual property rights.

---

### Correct Answer: **B and C**

### Explanation:
- **B**: Cloud computing facilitates collaboration by enabling multiple users to work on shared resources in real-time from different locations.
- **C**: Cloud computing raises data-security concerns due to the need to store sensitive information on third-party servers.

**Why A is incorrect:**  
Redundant routing is still necessary for fault tolerance in cloud systems.

---
## Question 66: Test Cases for Procedure `Smallest`

### Problem
The procedure `Smallest(numbers)` is intended to return the smallest value in the list `numbers`. However, the procedure does not work as intended. The task is to identify the test cases where `Smallest(numbers)` **does not** return the correct result.

---

### Options:
- **A**: `numbers ← [10, 20, 30, 40]`
- **B**: `numbers ← [20, 10, 30, 40]`
- **C**: `numbers ← [30, 40, 20, 10]`
- **D**: `numbers ← [40, 30, 20, 10]`

---

### Correct Answer: **C and D**

### Explanation:
- In the procedure, `RETURN(number)` immediately exits the loop when a smaller number is found. This behavior prevents the procedure from iterating through the entire list to find the actual smallest value.
- For **C** (`[30, 40, 20, 10]`) and **D** (`[40, 30, 20, 10]`), the procedure does not correctly find the smallest value because it stops at the first smaller value encountered.

**Why A and B are correct:**  
In these cases, the procedure correctly identifies the smallest value during the loop.

---


## REVVIT (Polls)

### Summary of Work
For Sprint 3, I focused on creating a functional and interactive webpage for car-related polls as part of the REVVIT project. This involved designing, implementing, and testing a frontend that allows users to vote in polls and view real-time updates on the leading choices.

---

### Accomplishments

1. **Frontend Design and Implementation**
   - Created a responsive webpage using **HTML**, **CSS**, and **JavaScript**.
   - Designed a clean and user-friendly interface with visually appealing styling to enhance the user experience.
   - Built interactive elements such as radio buttons for voting and dynamically updating result sections.

2. **Interactive Voting Logic**
   - Implemented the `handleVote` function to:
     - Validate user input (ensure a selection is made).
     - Send votes to the backend using the `fetch` API.
     - Dynamically update the page to show the current leading choice based on server responses.

3. **Styling and Responsiveness**
   - Applied modern design principles, including:
     - Dark theme with color contrasts for accessibility.
     - Responsive layout to ensure usability on various devices.
     - Hover effects for interactive elements like buttons and labels.

---

### Key Takeaways and Learning
- **Frontend Development Skills:**
  - Improved proficiency in writing structured HTML and CSS for responsive designs.
  - Enhanced understanding of how JavaScript interacts with the DOM to create dynamic features.

- **Problem-Solving with JavaScript:**
  - Gained experience in handling user input validation and managing asynchronous operations with `fetch`.

- **Preparing for Backend Integration:**
  - Learned how frontend logic communicates with backend endpoints for real-time updates.
  - Understood the importance of data validation and error handling for smooth user experiences.

---


---

### Outcome
This sprint allowed me to successfully build an engaging frontend for REVVIT polls, setting the foundation for a complete end-to-end voting system.

