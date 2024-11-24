 Calculator Program

This project implements a simple calculator in *C* that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The program allows the user to input two numbers and choose an operation to perform on them.

Features
- Add two numbers
- Subtract two numbers
- Multiply two numbers
- Divide two numbers (with error handling for division by zero)

How to Use
1. Clone the repository to your local machine using:
   ```bash
   git clone https://github.com/mass1018/My-Lab-10.git


2.Navigate to the Project Folder

Move into the project folder:

cd <repository-folder>

3.Compile the Program

Compile the program using GCC:

gcc -o calculator calculator.c

4.Run the Program

Run the program after compilation:

./calculator


Code Explanation

The program is structured as follows:

Function Declarations:

add(num1, num2): Performs addition.

subtract(num1, num2): Performs subtraction.

multiply(num1, num2): Performs multiplication.

divide(num1, num2): Performs division and handles division by zero.



Main Function:

Accepts user input (two numbers and an operator).

Uses a switch statement to call the appropriate arithmetic function based on the operator.

Outputs the result or an error message if the input is invalid.



Error Handling:

Handles invalid operators.

Prevents division by zero by checking the denominator.




Git commands used to amke a calculator:


1. git init

Purpose: Initializes a Git repository in your project folder.

Command:

git init

Explanation:

Creates a .git folder in your project directory.

Marks the folder as a Git repository to start tracking changes.




---

2. git checkout -b calculator

Purpose: Creates and switches to a new branch named calculator.

Command:

git checkout -b calculator

Explanation:

Branches are used to develop new features (e.g., the calculator program) without affecting the main branch.

calculator is the name of the new branch.




---

3. touch calculator.c

Purpose: Creates a new file named calculator.c.

Command:

touch calculator.c

Explanation:

This creates an empty file in the project directory where you will write your calculator code.




---

4. git add calculator.c

Purpose: Stages the calculator.c file for commit.

Command:

git add calculator.c

Explanation:

Git begins tracking the file and prepares it to be included in the next commit.

If the file is not added, it won't be part of the commit.




---

5. git commit -m "Added calculator program"

Purpose: Saves the current state of the project with a meaningful message.

Command:

git commit -m "Added calculator program"

Explanation:

Commits are snapshots of your repository at a specific point in time.

The -m flag specifies the commit message, which should describe the changes.




---

6. git push origin calculator

Purpose: Pushes the calculator branch and its commits to the remote repository on GitHub.

Command:

git push origin calculator

Explanation:

origin is the name of the remote repository (default for GitHub repositories).

calculator is the branch being pushed to the remote repository.




---

7. git clone <repository-url>

Purpose: Creates a local copy of a remote repository.

Command:

git clone <repository-url>

Explanation:

Used by collaborators to download the repository to their local machines for development.




---

8. git status

Purpose: Displays the status of the repository.

Command:

git status

Explanation:

Shows which files are staged, unstaged, or untracked.

Useful for verifying the current state of your repository.




---

9. git merge calculator

Purpose: Merges the calculator branch into another branch (usually the main branch).

Command:

git merge calculator

Explanation:

Integrates the changes from the calculator branch into the main branch.


Contributors

This project was developed by:

Anoosha Hassan

Isba Mujeeb

Masarrat Fatema
