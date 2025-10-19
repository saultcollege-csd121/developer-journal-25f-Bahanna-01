# Developer Journal – Lab 1: Introduction to Java

## Entry 1 – Installation and Setup
**Date:** September 9, 2025

**What I learned:**
Today I installed IntelliJ IDEA as my Java development environment and configured the JDK. I also created the GitHub repository named CSD121-labs as instructed in Lab 1, and added my instructor as a collaborator.

**Questions I had:**
I wasn’t sure how to add my instructor as a collaborator on GitHub or whether I should include files in the repository right after creating it.

**Problems I faced:**
I had trouble locating the “Collaborators” option in the repository settings.

**How I solved it:**
I followed the lab instructions and found the option under “Settings > Collaborators and Teams.” I also confirmed that no files should be added to the repository at this stage.

**Ideas or next steps:**
I plan to write my first Java program and begin developing an interactive quiz as part of my practice.

## Entry 2 – Reviewing Previous Labs
**Date:** September 13, 2025 

**What I learned:**
I spent time reviewing previous programming labs from other courses to refresh my memory on Java basics. I revisited concepts like class structure, arrays, the main method, and conditional logic. This helped me feel more confident before starting the quiz project.

**Questions I had:**
I wasn’t sure how to organize questions and options efficiently, whether to use separate arrays or a more object-oriented structure.

**Problems I faced:**
Some of my old examples were written in other languages (Python), so I had to adapt the logic to Java.

**How I solved it:**
I compared the examples with Java syntax and used study resources to understand how to apply the same concepts. I also asked ChatGPT Studying for help with array structure.

**Ideas or next steps:**
I decided to start the quiz using separate arrays to make the structure easier to visualize. Later, I want to try using a Question class to make the code more organized.

## Entry 3 – Building the Java Quiz
**Date:** September 15, 2025

**What I learned:**
I built an interactive quiz in Java with questions about movies and series. I used three separate arrays: one for the questions, one for the answer options, and one for the correct answers. I learned how to use loops to go through each question and compare the user’s input with the correct answer.I also reviewed the Lab 1 instructions and created a checklist to make sure I completed every required step.

**Questions I had:**
I wasn’t sure whether it would be better to use a class to group each question with its options and answer, or keep everything separate. I also had questions about how to save the results to a .txt file

**Problems I faced:**
I struggled with aligning the array indices and understanding how FileWriter works to write data to a file.

**How I solved it:**
I asked ChatGPT Studying for help and learned that using separate arrays is a good way to visualize the structure. I received examples and explanations that helped me apply the logic correctly. I also learned how to use FileWriter to save quiz results.

**Debugging Test:**
I ran a debug session in IntelliJ IDEA to test variable values during runtime. I used breakpoints to inspect the Scanner input and confirmed that the name variable was correctly storing the user’s input ("Barbora"). This helped me understand how the program flows and how to monitor values step by step.

**Ideas or next steps:**
I want to test a more object-oriented version using a Question class, and maybe add a scoring system with personalized feedback for each answer.


## Link_ChatGPT

https://chatgpt.com/share/68c86d71-dc90-8009-a04a-06073a4e15f9

https://chatgpt.com/share/68c871e4-f5d8-8009-a2d7-4fa347ff053c


## References
https://getemoji.com/



# Developer Journal – Lab 3: Implementing Classes

**What I built**
I created a fully functional Tic Tac Toe game in Java using three classes: `Board`, `Console`, and `Main`. The game includes a menu, rules display, player name input, and flexible move entry (space or comma). It checks for win and draw conditions and displays the board after each move.

**What I learned**
- How to structure a Java project using packages (`lab3.game`, `lab3.ui`)
- How to use arrays to represent a game board and check for win conditions
- How to use loops and conditionals to manage game flow
- How to split user input using regular expressions (`split("[,\\s]+")`)
- How to write beginner-friendly comments and JavaDoc-style documentation

**Problems I overcame**
- Input validation: I initially only accepted moves like `1 1`, but realized players might type `1,1`. I updated the code to accept both formats.
- Win detection: I had to carefully check rows, columns, and diagonals to ensure the game ends correctly.
- Commenting: I wanted my comments to reflect my learning process, so I rewrote them in a beginner-friendly style.
