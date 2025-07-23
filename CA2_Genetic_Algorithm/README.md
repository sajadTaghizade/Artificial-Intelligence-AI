<div align="center">
  <h1>
    🧬 Artificial Intelligence - Computer Assignment 2 ♟️
  </h1>
  <p>
    This project is the second assignment for the Artificial Intelligence course. It is divided into two main parts: using a <strong>Genetic Algorithm</strong> to approximate the coefficients of a Fourier series, and implementing the <strong>Minimax algorithm</strong> to play the game of Pentago.
  </p>
</div>

<hr>

<table>
  <tr>
    <td valign="top" width="50%">
      <h2>
        Part 1: Genetic Algorithm for Fourier Series
      </h2>
      <p>
        The objective of this part is to use a genetic algorithm to find the optimal coefficients for the first 20 terms of a Fourier series for an unknown function. Given 100 sample data points, the goal is to determine the 41 Fourier coefficients (<em>a</em><sub>0</sub> to <em>a</em><sub>20</sub> and <em>b</em><sub>1</sub> to <em>b</em><sub>20</sub>) that provide the best fit to the data.
      </p>
      <details>
        <summary>
          <strong>Implementation Steps</strong>
        </summary>
        <ul>
          <li>
            <strong>Chromosome Definition</strong>: Define a chromosome structure to represent a potential solution, which consists of the 41 Fourier coefficients.
          </li>
          <li>
            <strong>Initial Population</strong>: Create an initial population of chromosomes with random coefficients to ensure diversity.
          </li>
          <li>
            <strong>Fitness Evaluation</strong>: Implement a fitness function to measure how well a chromosome's resulting Fourier series approximates the target function. At least three error metrics must be discussed, including RMSE.
          </li>
          <li>
            <strong>Selection, Crossover, and Mutation</strong>: Implement selection strategies, a crossover function to combine chromosomes, and a mutation function to introduce variations in the population.
          </li>
          <li>
            <strong>Results Analysis</strong>: The final approximated function should be plotted against the target function. Additionally, the fitness evolution across generations must be graphed and analyzed.
          </li>
        </ul>
      </details>
    </td>
    <td valign="top" width="50%">
      <h2>
        Part 2: Minimax for the Game of Pentago
      </h2>
      <p>
        This part involves implementing the Minimax algorithm to create an AI agent that can play the strategic two-player game, Pentago. The game is played on a 6x6 board divided into four 3x3 sub-blocks. The objective is to be the first to form a continuous line of five of one's own marbles.
      </p>
      <details>
        <summary>
          <strong>Implementation Steps</strong>
        </summary>
        <ul>
          <li>
            <strong>Complete the Minimax Function</strong>: A skeleton code for the game is provided. The primary task is to complete the <code>minimax</code> function within the given code.
          </li>
          <li>
            <strong>Heuristic Function</strong>: A heuristic function is required to evaluate the state of the game board for non-terminal states.
          </li>
          <li>
            <strong>Alpha-Beta Pruning</strong>: To improve performance, Alpha-Beta pruning must be added to the Minimax algorithm.
          </li>
          <li>
            <strong>Results Analysis</strong>: The performance of the algorithm (win rate, execution time, nodes visited) must be analyzed at different search depths, both with and without Alpha-Beta pruning. The final agent should also be tested against a random opponent for 100 games.
          </li>
        </ul>
      </details>
    </td>
  </tr>
</table>
