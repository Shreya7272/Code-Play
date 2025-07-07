# Code-Play
Code Play is a beginner-friendly web application designed to make coding fun and interactive. The platform allows users—especially students—to learn the basics of programming through simple challenges, visual outputs, and gamified interactions.
CodePlay* is a web-based platform designed for beginners and students to learn programming in a fun and interactive way.  
It supports 4 languages: *C, C++, Java, and Python*.

Main features include:
- 📖 *Learn Module* – Topic-wise theory and examples.
- 🧑‍💻 *Practice Module* – Online code editor with live output.
- 🧠 *Puzzle Section* – Algorithm puzzles with visual animations.
- 🎮 *Play Module* – Drag-and-drop logic builder.
- 🏆 *Gamified Progress* – Earn badges and track learning.

---

## 🛠 Technologies Used

| Component        | Technology Used               | Why We Used It                                   |
|------------------|-------------------------------|--------------------------------------------------|
| Code Editor      | Monaco / CodeMirror           | VS Code-like experience, lightweight, browser-based |
| Frontend         | HTML, CSS, JavaScript         | Simple, responsive, interactive UI               |
| Backend          | Node.js + Express.js          | Fast, uses same JS as frontend, easy API creation |
| Code Execution   | Docker                        | Secure, isolated execution, supports many languages |
| Database         | MongoDB                       | JSON-like, flexible structure, works with Node.js |
| Visual Effects   | CSS Animations, SVG, Canvas   | Smooth visuals, interactive puzzle experience     |

---

## 🔍 Key Modules & Algorithms

### 📖 Learn Module
- Shows topic-wise theory (Loops, Arrays, OOP, etc.)
- Data stored in a *JSON file* for easy access
- Languages: C, C++, Java, Python

### 🧑‍💻 Practice Module
- Uses *Monaco Editor* to write code
- Code is executed through *Docker containers*
- Languages supported: C, C++, Java, Python

### 🎮 Play Module
- Drag-and-drop logic blocks to simulate coding flow
- Helps beginners learn without writing syntax

### 🧩 Puzzle Section (Algorithms Used)

| Puzzle Name         | Algorithm Used       | Purpose                                   |
|---------------------|----------------------|-------------------------------------------|
| Rain Water Trapping | Two-pointer technique| Teaches array traversal and logic          |
| Bubble Sort         | Bubble Sort          | Simple sorting, easy to animate           |
| Graph Coloring      | Backtracking         | Constraint-based problem solving          |
| Coin Change         | Dynamic Programming  | Optimization and subproblem reuse         |
| Tower of Hanoi      | Recursion            | Visual understanding of recursion calls   |

---

## 📈 Project Result

- All modules are working as expected.
- Code runs securely using Docker.
- Users can learn, code, and play with programming concepts.
- User progress (badges, scores) is saved in MongoDB.
- Interface is responsive and easy to use.
- Fully tested and ready for educational use.

---

## 🧪 How to Run the Project

### ▶️ Backend Server Setup

1. Open *Node.js Command Prompt*
2. Navigate to the backend folder:
   ```bash
   cd d:
   cd finalproj
   cd code-compiler-backend

. Start the server:

node server.js


4. Output:

Server listening on port 8000



📷 Screenshot:



> Make sure Docker is installed and running on your system.




---

🗂 Folder Structure

/codeplay
  ├── /frontend
  │   ├── index.html
  │   ├── styles.css
  │   └── script.js
  ├── /backend
  │   ├── server.js
  │   └── executeCode.js
  ├── /puzzles
  │   └── *.js (puzzle logic files)
  ├── /data
  │   └── topics.json
  └── /screenshots
      └── server-running.png


---

🔮 Future Scope

Add more languages (JavaScript, Go)

Add certificate after puzzle completion

AI feedback on code performance

Launch mobile app version.
