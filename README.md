# Word-Ladder-Game-Solver
# 1. Overview
- This program solves word ladder puzzles.
- You give it a start word and an end word.
- It finds a path where each step changes only one letter and all words are valid.

## 2. How the Program Works (Step-by-Step)

1. **Load Dictionary**
   - The program reads a list of valid words from a dictionary file (e.g., `words.txt`).
   - Stores them in a data structure (like a set or vector) for fast lookup.

2. **Get Input**
   - User enters a **start word** and an **end word**.
   - The program checks they are the same length and exist in the dictionary.

3. **Search for a Ladder**
   - Uses a search algorithm (usually **BFS - Breadth-First Search**).
   - Starts from the start word.
   - Generates all valid words that differ by 1 letter.
   - Keeps track of which words have been visited.

4. **Build the Path**
   - When the end word is found, the program traces back the path.
   - Reconstructs the sequence of words from start to end.

5. **Output**
   - Prints the full word ladder, step by step.
   - If there is no valid path, prints that no ladder exists.

# Demo Video

Here is a short demo with audio explanation of how the Word Ladder Solver works:

<video src="Screen Recording 2025-11-30 at 12.28.46 AM.mp4" controls width="600"></video>
