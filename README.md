Rubik's Cube Solver
This project aims to solve a virtual Rubik's Cube (3x3) using various algorithms implemented in C++. Three models were developed utilizing standard data structures: Breadth-First Search (BFS), Depth-First Search (DFS), and Iterative Deepening Depth-First Search (IDDFS). Additionally, Korf's IDA* Algorithm was incorporated to achieve faster solving times. The solver can successfully solve a Rubik's Cube jumbled 8 times in less than 3 seconds using BFS, DFS, and IDDFS, and less than 10 seconds using Korf's IDA* Algorithm for a Rubik's Cube jumbled 13 times.

Features
Virtual Rubik's Cube solver implemented in C++
Supports a 3x3 Rubik's Cube
Three solving models implemented: BFS, DFS, and IDDFS
Achieves solving time of less than 3 seconds for a jumbled cube (8 times) using BFS, DFS, and IDDFS
Incorporates Korf's IDA* Algorithm for faster solving times
Achieves solving time of less than 10 seconds for a jumbled cube (13 times) using Korf's IDA* Algorithm
Usage
Clone the repository and navigate to the project directory.
shell
Copy code
git clone https://github.com/your-username/rubiks-cube-solver.git
cd rubiks-cube-solver
Compile the C++ source code using a C++ compiler.
shell
Copy code
g++ -o solver main.cpp
Run the compiled executable.
shell
Copy code
./solver
The program will prompt you to input the initial state of the Rubik's Cube. Use the standard notation to represent the colors on each face. For example, 'W' for white, 'R' for red, 'B' for blue, 'G' for green, 'Y' for yellow, and 'O' for orange.

After entering the initial state, the program will output the solution steps to solve the Rubik's Cube.

Credits
This project was created by [Your Name] as a demonstration of various algorithms used to solve a virtual Rubik's Cube. The implementation of BFS, DFS, and IDDFS was inspired by classic graph search algorithms, while Korf's IDA* Algorithm was used to achieve faster solving times.

Disclaimer
This project is intended for educational purposes only. It serves as a demonstration of solving algorithms for a virtual Rubik's Cube. The creators of this project take no responsibility for any misuse or illegal use of the provided code.
