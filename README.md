# LeetCode Linked List Visualizer

An interactive, stream-ready visualizer for learning linked-list pointer movement through two classic duplicate-removal problems.

## Try it live

[Open the interactive visualizer](https://gliesecc212.github.io/leetcode-visualizer/)

## Included problems

- **LeetCode 83 — Remove Duplicates from Sorted List**: keep one copy of each value.
- **LeetCode 82 — Remove Duplicates from Sorted List II**: remove every value that appears more than once.

## What it shows

- A linked list rendered as connected nodes
- Live `current`, `prev`, and `dummy` pointer positions
- Step-by-step navigation, back, reset, and auto-play
- Removed nodes clearly highlighted
- Java code with the current line synchronized to each pointer action
- A short explanation and stream talk track for every step

## How to use

1. Open `index.html` in a browser.
2. Choose problem **82** or **83**.
3. Enter sorted integers, such as `1, 1, 2, 3, 3`.
4. Ask viewers to predict what happens next, then use **Next step** to reveal the pointer operation.

## Teaching idea

Use problem 83 first to establish the simple rule: skip only the extra duplicate node. Then move to problem 82 to show why the requirement “remove all duplicates” needs a `dummy` node and a `prev` pointer.

## Complexity

Both solutions use **O(n)** time and **O(1)** extra space.
