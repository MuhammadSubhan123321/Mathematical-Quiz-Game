**Mathematics Quiz Game (C++)**

📌 Overview

**This is a console-based Mathematics Quiz Game written in C++.**

**The game challenges users to answer multiple-choice questions across three difficulty levels:**

1- Easier

2- Medium

3- Hard

**All questions and answers are loaded from external text files:**

1- level1.txt

2- level2.txt

3- level3.txt

✨ **Features**

👤 -User Registration with name input.

🎯 -Three Difficulty Levels with separate question sets.

✅ -Input Validation for menu options and answers.

🏆 -Score Tracking with percentage calculation.

💬 -Instant Feedback on correct/wrong answers.

🔄 -Retry Options to replay levels or return to the menu.

📖 -Clear Instructions before starting.

🧭- Dynamic Level Navigation with error checking.

⚙️ **How It Works**

-The user inputs their name.

-The Main Menu lets the user start or exit the game.

-After starting, the user chooses a difficulty level or returns to the main menu.

-The game loads the appropriate quiz file (level1.txt, level2.txt, or level3.txt).

-Each question is displayed with multiple-choice options (A, B, C, D).

-The system validates the answer and provides instant feedback.

-At the end of a level, the percentage score is shown.

-The user can retry the level or go back to the menu.

-The game continues until the user chooses to exit.

▶️ **Usage Instructions**

-Compile the program:

g++ main.cpp -o quizgame


-Ensure that quiz files (level1.txt, level2.txt, level3.txt) are in the same directory.

**Run the executable:**

./quizgame


**Follow the on-screen instructions to play.**

⌨️ Input Format

**Main Menu:**

0 → Exit

1 → Start

**Level Selection:**

1 → Easier

2 → Medium

3 → Hard

4 → Return to Menu

Answers: Enter A, B, C, or D (case-insensitive).

🏅 **Scoring**

Each correct answer = 1 point.

Final Score = Points × 10 (Percentage).

**Feedback messages indicate whether the user:**

✅ Passed

❌ Failed

🌟 Excelled

📦 Dependencies

**Standard C++ Libraries:**

<iostream>

<fstream>

<string>

External quiz files: level1.txt, level2.txt, level3.txt.

📌 **Notes**

**Quiz files must be formatted properly:**

-Questions should end with ?

-Options separated by /

-Program uses loops and goto statements for navigation.

-Case-insensitive handling ensures smooth input for answers and menu selections.

Enter your name : Muhammad Subhan
------------------------------------------------------------------
Welcome to Mathematics quiz game Muhammad Subhan
------------------------------------------------------------------
---------------------- Mathematics Quiz Game----------------------
Press '0' for exiting game.
Press '1' for starting game.
_____________________________
1
_____________________________
Enter Level '1' for Easier Level
Enter Level '2' for Medium Level
Enter Level '3' for Harder Level
OR
If you want to go back to main screen, Press '4' 
_________________________________
1
_________________________________
You must follow these rules before entering this quiz
Rule no.1:- You must not cheat during your Quiz
Rule no.2:- You must select correct answer
Are you ready for the Quiz
 YES  OR  NO 
 __________________
YES
___________________
Question 1? 
A) ...
B) ...
C) ...
D) ...
User input: D
__________________
Great!Correct Answer.
...
Score calculation and final feedback.

