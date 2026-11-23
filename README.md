# whack_a_mole
# Whack-a-Mole Game – PF Project (C Version)

## Section A: Project Introduction

Whack-a-Mole is a simple and interactive arcade game developed in C language as a Programming Fundamentals (PF) project. The main objective of the game is to hit the mole whenever it appears in one of the holes and score as many points as possible before the timer runs out. The game includes six holes arranged in two rows, a scoring system, a countdown timer, and a high-score system. When the time reaches zero, the game displays the final score and high score. Players can also restart the game by pressing the R key.

## Section B: Features & Test Cases (Execution Scenarios)

### Case 1: Starting and Playing the Game

- **Description:** This test case checks whether the game starts successfully and displays the playing screen with six holes, a mole, the current score, and the countdown timer.
- **Inputs:** Run the game and wait for the mole to appear. Click on the mole to score points.
- **Expected Output:** The game displays the mole, score, and remaining time. The score increases when the player successfully hits the mole.
- **Screenshot:**

![Case 1](screenshots/gameplay.webp)

### Case 2: Game Over Screen

- **Description:** This test case checks whether the game ends automatically when the countdown timer reaches zero.
- **Inputs:** Play the game until the timer runs out.
- **Expected Output:** The game displays the GAME OVER screen along with the final score, high score, and an option to restart the game by pressing R.
- **Screenshot:**

![Case 2](screenshots/gameover.webp)

### Case 3: High Score System

- **Description:** This test case checks whether the game tracks and displays the highest score achieved.
- **Inputs:** Play multiple rounds and achieve different scores.
- **Expected Output:** The game displays the current score and the highest score achieved during the game session.
- **Screenshot:**

![Case 3](screenshots/highscore.webp)

### Case 4: Restarting the Game

- **Description:** This test case checks whether the player can restart the game after the game-over screen appears.
- **Inputs:** Press the R key on the keyboard after the game ends.
- **Expected Output:** The game starts a new round with the score reset to zero and the timer restarted.

## Section C: Instructions to Clone and Execute

### Step 1: Clone the Repository

Open the terminal and execute the following command:

```bash
git clone https://github.com/alizasyed89/whack_a_mole
```

Navigate to the project folder:

```bash
cd whack_a_mole
```

### Step 2: Compile the Code

Compile the C source code using GCC:

```bash
gcc main.c -o game.exe -lraylib -lopengl32 -lgdi32 -lwinmm
```

**Note:** Raylib and GCC (MinGW) must be installed and configured before compiling. If your source file has a different name, replace `main.c` with its actual filename.

### Step 3: Run the Program

For Windows (Command Prompt or VS Code Terminal), execute:

```bash
game.exe
```

Alternatively, run the existing executable by double-clicking `game.exe`.

## Section D: Submission Checklist

Before submitting the repository link on the university portal, ensure that:

- [ ] The GitHub repository is set to Public.
- [ ] The C source code is uploaded.
- [ ] The executable file is included if required.
- [ ] The README.md file contains the project introduction.
- [ ] All execution cases are explained.
- [ ] Screenshots are uploaded inside the `screenshots` folder.
- [ ] Screenshot paths in README.md are correct.
- [ ] The program compiles and runs successfully.
- [ ] Clone and execution instructions are provided.

---

**Project:** Whack-a-Mole Game  
**Language:** C  
**Project Type:** Programming Fundamentals (PF)  
**Version:** C Version
