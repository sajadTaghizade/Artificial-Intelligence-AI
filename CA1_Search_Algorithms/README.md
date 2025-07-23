<div align="center">
  <h1>
    🤖 Artificial Intelligence - Computer Assignment 1 🤖
    <br>
    The Chaos Warehouse Problem
  </h1>
  <p>
    This project is the first assignment for the Artificial Intelligence course. The main goal is to solve a simulated problem by using various <strong>informed and uninformed search algorithms</strong>. The project emphasizes the implementation, comparison, and analysis of these different search strategies.
  </p>
</div>

<hr>

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>
        📖 Project Description
      </h3>
      <p>
        In this problem, you'll help the character <strong>Mike Wazowski</strong> move boxes of scream capsules to their designated destinations within a warehouse. The warehouse map includes walls, empty spaces, boxes (<strong>B_i_</strong>), their destinations (<strong>G_i_</strong>), and up to two pairs of portals (<strong>P_i_</strong>).
      </p>
      <p>
        Mike can push only one box at a time. Passing through a portal instantly transports him to the corresponding portal in the same direction. The objective is to find the optimal sequence of moves to get all the boxes to their correct destinations.
      </p>
      <br>
      <h3>
        🛠️ Provided Tools
      </h3>
      <ul>
        <li>
          <strong><code>game.py</code></strong>: A Python file containing a game simulation class. Its use is optional but provides helpful functions for managing game state and player movement.
        </li>
        <li>
          <strong><code>gui.py</code></strong>: A file for graphical visualization of the game, which requires the <strong>raylib</strong> library to be installed.
        </li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>
        🤖 Required Algorithms
      </h3>
      <h4>Uninformed Search</h4>
      <ul>
        <li>DFS (Depth-First Search)</li>
        <li>BFS (Breadth-First Search)</li>
        <li>IDS (Iterative Deepening Search)</li>
      </ul>
      <h4>Informed Search</h4>
      <ul>
        <li>A* (A-Star) with at least one appropriate heuristic function.</li>
        <li>Weighted A* with at least one weight value (w).</li>
      </ul>
    </td>
  </tr>
</table>

<hr>

### 📥 Input and Output Format

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>Input</h4>
      The input is a text map representing the initial state of the warehouse. The characters are defined as follows:
      <ul>
        <li><strong>H</strong>: Mike's position</li>
        <li><strong>B_i_</strong>: Box number i</li>
        <li><strong>G_i_</strong>: Destination for box number i</li>
        <li><strong>W</strong>: Wall</li>
        <li><strong>P_i_</strong>: Portal number i</li>
        <li><strong>.</strong>: Empty space</li>
        <li>Two elements can share a location, separated by a <strong>/</strong> (e.g., <code>G1/H</code>).</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h4>Output</h4>
      <p>
        The output should be a string of moves (<strong>U, D, L, R</strong>) and the number of states visited. For <strong>BFS and A*</strong> algorithms, the solution must be optimal (the shortest path). If no solution is found, the output should be <code>No solution</code>.
      </p>
    </td>
  </tr>
</table>

<hr>

<details>
  <summary>
    <h3>💡 Key Implementation Points & Report Guidelines</h3>
  </summary>
  <ul>
    <li>
      <strong>State Definition</strong>: Implement an efficient definition for a "state" that is more optimized than a simple representation of the entire map at each moment.
    </li>
    <li>
      <strong>Heuristics</strong>: For the A* algorithm, design and analyze at least two suitable heuristic functions. These can be improved versions of the Manhattan distance and should be analyzed for <strong>admissibility and consistency</strong>.
    </li>
    <li>
      <strong>Report</strong>: Submit a comprehensive report that includes an analysis of the algorithms, a comparison of the heuristics, and tables showing results like execution time and the number of states visited.
    </li>
  </ul>
</details>
