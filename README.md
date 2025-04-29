# comp424---solved
**TO GET THIS SOLUTION VISIT:** [COMP424 – Solved](https://www.ankitcodinghub.com/product/comp424-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110755&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP424 -  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Homework 1

General instructions.

• Unless otherwise mentioned, the only sources you should need to answer these questions are your course notes, the textbook, and the links provided. Any other source used should be acknowledged with proper referencing style in your submitted solution.

• For each problem, you can solve manually, or write a program to help you. You can use a programming language of your choice. You can modify code from other sources if you provide adequate citation; this cannot be code from other students in the class.

• Submit a single pdf of your responses through myCourses. You can scan-in hand-written pages. If necessary, learn how to combine many pdf files into one.

• In addition, submit any code developed to answer questions as a separate file through myCourses.

Question 1: Six-Puzzle [30]

Write code in a language of your choice to solve this problem. Hand in the source code with your submission, making clear that the file(s) is/are for Question 1.

Consider a variant of the eight-puzzle, which we saw in class, where we reduce the size of the puzzle to 3×2, in order to keep the number of states manageable. Now, consider the following initial and goal states:

Initial state: Goal state:

1 4 2 1 2

5 3 5 4 3

a) Show the solution path (i.e., the sequence of puzzle states from the initial to the goal state) found by each of the following algorithms, assuming transitions have unit cost. You must ensure that puzzle states that have been explored are not added to the search queue. Given multiple states to explore that are otherwise equivalent in priority, the algorithm should prefer the state that involves moving a lower-numbered piece. i. Breadth first search ii. Uniform cost search

iii. Depth first search

iv. Iterative deepening

b) Suppose now that transitions have differing costs. In particular, the cost of a transition is equal to the number of the piece that is moved (e.g., moving the “4” costs 4). If we employ the Manhattan distance heuristic for the original unit cost version of the eight-puzzle presented in class (Lecture 4, slide 11, ℎ2), would this heuristic still be an admissible heuristic for A* search in the new variant? Justify your answer.

c) Design an admissible heuristic that dominates the heuristic from part b, under the same transition cost scheme as part b.

Question 2: Search algorithms [30]

(Adapted from Russell &amp; Norvig)

a) Describe a state space in which iterative deepening search performs much worse than depth-first search (for example, 𝑂(𝑛2) vs 𝑂(𝑛)).

Prove each of the following statements, or give a counterexample:

b) Breadth-first search is a special case of uniform-cost search.

c) Uniform-cost search is a special case of A* search.

d) Best-first search is optimal in the case where we have a perfect heuristic (i.e., ℎ(𝑛) = ℎ∗(𝑛), the true cost to the closest goal state).

e) Suppose there is a unique optimal solution. Then, A* search with a perfect heuristic will never expand nodes that are not in the path of the optimal solution.

Question 3: Travelling Salesman Problem [40]

Write code in a language of your choice to solve this problem. Hand in the source code with your submission, making clear that the file is/are for Question 3. If you think it will be easier, you are welcome to use external code and libraries with citation, as long as they do not come from current or past students in COMP 424, but please implement your own greedy local search method.

Consider the travelling salesman problem, as described in class. For parts a) – c), write code to generate 100 random TSP instances involving 7 cities, where cities lie at points in the 2D plane ([0.0,1.0], [0.0,1.0]), sampled uniformly at random. Your code should be correct but will not be marked for style. Use Euclidean distance as your distance measure between cities.

a) Solve each TSP exactly by brute-force search over all possible tours. Record and save these costs. In your report, simply state where in your code this is implemented, and state the mean, min, max, and standard deviation of the optimal tour lengths across the 100 instances.

c) Implement and apply hill climbing/greedy local search using the 2-change neighbourhood function described in class on the 100 instances, using the randomly sampled start state from part b). What is the mean, min, max, and standard deviation of the tour lengths found? Also report the number of instances for which the algorithm found the optimal solution.

(If you have extra time, you can find libraries to help you plot and visualize the solutions found by your algorithms, but this is not necessary for the submission.)
