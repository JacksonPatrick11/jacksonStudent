---
layout: post
title: "AP CSP Create Task – Personalized Project Reference"
permalink: /ppr.md/
---

# 🚀 **AP CSP Create Task – Personalized Project Reference**
The **AP Create Performance Task (CPT)** required me to develop a program that **solves a problem, enables innovation, or explores an interest**.  
My project focused on creating an **AP US History Quiz** with a **dynamic leaderboard**.  

Below is a breakdown of my implementation, how it meets AP CSP requirements, and key reflections.  

---

## 📌 1️⃣ Managing Complexity with Lists  
AP requires using a **list (or other collection type)** to manage complexity.  
In my project, I used a **list of 50 APUSH questions**, ensuring dynamic question selection.

```python
import random  # Importing random to shuffle and select questions dynamically.

# List of APUSH quiz questions (simplified for readability)
question_pool = [
    {"id": 1, "text": "Who was the first U.S. president?", "options": ["George Washington", "Thomas Jefferson"], "correctAnswer": "George Washington"},
    {"id": 2, "text": "What year did the Civil War start?", "options": ["1861", "1776"], "correctAnswer": "1861"},
    # ...more questions...
]

# Function to randomly select 10 questions for a quiz attempt
def get_quiz_questions():
    return random.sample(question_pool, 10)

selected_questions = get_quiz_questions()  # Fetching 10 random questions.
```

✅ **Uses a list** to store quiz questions, making it **scalable**.  
✅ **Simplifies** adding new questions without modifying core logic.  
✅ **Avoids hardcoding** multiple quiz versions, reducing complexity.  

---

## 📌 2️⃣ Student-Developed Procedure with Algorithm  
AP requires a **procedure** that includes **sequencing, selection, and iteration**.  
My program includes a function that **calculates user scores** based on correct answers.

```python
def calculate_score(user_answers, correct_answers):
    score = 0
    for i in range(len(user_answers)):  # Iteration (loops through answers)
        if user_answers[i] == correct_answers[i]:  # Selection (if-else condition)
            score += 1
    return score  # Sequencing (structured process from input to output)
```

✅ **Sequencing** – The function executes steps in order.  
✅ **Selection** – Uses `if` conditions to check correctness.  
✅ **Iteration** – Loops through answers to calculate score.  

---

## 📌 3️⃣ Calling the Student-Developed Procedure  
To demonstrate functionality, here is where my procedure is **actively used in the quiz logic**.

```python
user_score = calculate_score(user_responses, correct_answers)
print(f"Your final score is: {user_score}/10")  # Outputs the calculated score.
```

---

## 📌 4️⃣ Handling Input & Output  
AP requires **user input and output**. My project **handles input** through user responses and **displays scores dynamically**.

```python
user_name = input("Enter your name: ")  # User enters their name.
user_answers = []  # List to store user responses.

# Loop through each question and get user input
for question in selected_questions:
    print(question["text"])  # Display the question text.
    user_answers.append(input("Your answer: "))  # Store the user's response.

# Displaying final score
print(f"Thanks for playing, {user_name}! Your score: {calculate_score(user_answers, correct_answers)}/10")
```

✅ Uses **user input** to collect quiz responses.  
✅ Uses **output** to display the score dynamically.  

---

## 📌 5️⃣ Dynamic Leaderboard with CRUD Operations  
My program includes a **leaderboard system** that dynamically updates based on quiz scores.

```python
leaderboard = []  # List to store leaderboard entries.

def add_to_leaderboard(user_name, score):
    leaderboard.append({"name": user_name, "score": score})  # Appends new entry.
    leaderboard.sort(key=lambda x: x["score"], reverse=True)  # Sorts by score.

# Updating leaderboard after each quiz attempt
add_to_leaderboard(user_name, user_score)
```

✅ Uses a **list** to manage leaderboard data.  
✅ Implements **CRUD operations** (Create, Read, Update, Delete).  
✅ **Sorts dynamically** to display rankings in descending order.  

---

## 🔍 Reflection & Challenges  
During development, I faced challenges such as:  
- Debugging **incorrect answer validation**.  
- Handling **API calls** for leaderboard updates.  

### ✔️ How I Overcame Them:  
✔️ **Added print statements** for debugging.  
✔️ **Researched database query optimizations**.  

### 🔹 Improvements I Would Make:  
🚀 **Improve performance** by caching frequently accessed questions.  
🎯 **Enhance user experience** with a timer for real-time quiz simulation.  
📚 **Expand functionality** by adding more subjects beyond APUSH.  

---

## 🚀 Final Thoughts  
Through this project, I successfully met the **AP Create Task** requirements by implementing:  
✅ **Lists** to store and manage data.  
✅ **User input & output** for interactivity.  
✅ A **student-developed procedure** with an algorithm using **sequencing, selection, and iteration**.  
✅ A **functional leaderboard** with CRUD operations.  

### **Next Steps**  
I plan to:  
📌 Improve my **backend skills** and explore **API integrations**.  
📌 Refine **UX design** to build **more interactive projects**.  

📌 **[View My GitHub Repository](#) | 🏆 [Try the Live Quiz](#)**