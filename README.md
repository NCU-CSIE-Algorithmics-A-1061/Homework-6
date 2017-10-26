# Homework 6

1. Exercises 16.1‐3<br>
Not just any greedy approach to the activity‐selection problem produces a maximum‐size set of mutually compatible activities. Give an example to show that the approach of selecting the activity of least duration from among those that are compatible with previously selected activities does not work. Do the same for the approaches of always selecting the compatible activity that overlaps the fewest other remaining activities and always selecting the compatible remaining activity with the earliest start time.

2. Exercises 16.1‐4<br>
Suppose that we have a set of activities to schedule among a large number of lecture halls, where any activity can take place in any lecture hall. We wish to schedule all the activities using as few lecture halls as possible. Give an efficient greedy algorithm to determine which activity should use which lecture hall.
(This problem is also known as the interval‐graph coloring problem. We can create an interval graph whose vertices are the given activities and whose edges connect incompatible activities. The smallest number of colors required to color every vertex so that no two adjacent vertices have the same color corresponds to finding the fewest lecture halls needed to schedule all of the given activities.)

3. Exercises 16.1‐5<br>
Consider a modification to the activity-selection problem in which each activity a<sub>i</sub> has, in addition to a start and finish time, a value v<sub>i</sub>. The objective is no longer to maximum the number of activities scheduled, but instead to maximize the total value of the activities scheduled. That is, we wish to choose a set A of compatible activities such that ![sum(vk) where ak in A](http://latex.codecogs.com/gif.latex?%5CSigma_%7Ba_k%5Cin%7BA%7D%7Dv_k) is maximized. Give a polynomial-time algorithm for this problem.

4. Exercises 16.2‐6<br>
Show how to solve the fractional knapsack problem in O(n) time.

5. Exercises 16.3-7<br>
Generalize Huffman's algorithm to ternary codewords (i.e., codewords using the symbols 0, 1, and 2), and prove that it yields optimal ternary codes.

6. Find the Huffman codes of the data below by drawing the tree like the figure 16.5(unit06-演算法.pdf p21~p24). You should write down each step of the Huffman's algorithm.
    - a:22 b:2 c:5 d:3 e:5 f:8 g:7 h:11

7. There are n people whose individual weight is an integer.
    - Design an algorithm to decide whether they can be divided into two groups with equal weight.
    - Suppose that n is even, design an algorithm to find out whether they can be divided into two groups with equal weight and each group has exactly n/2 people.
