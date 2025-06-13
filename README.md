# Binary-Tree-Bottom-Up-Level-Order-Traversal



**Optimal Solution:** BFS + Reverse  
**Time Complexity:** O(n)  
**Space Complexity:** O(n)  

### Approach
1. Perform standard level-order traversal (BFS)
2. Reverse the result list
3. Handle edge cases (empty tree, single node)

### Key Features
- Uses `collections.deque` for efficient pops
- Tracks level size explicitly
- Clean separation of traversal and reversal steps

Usage Example
#   3
#  / \
# 9  20
#   /  \
#  15   7
→ [[15,7], [9,20], [3]]
Contribute? Open a PR with optimizations or additional test cases!

text

This version:
1. Uses clean GitHub-flavored markdown
2. Highlights the algorithmic approach first
3. Shows complexity analysis upfront
4. Includes executable code block
5. Ends with contribution prompt
6. Maintains technical precision while being scannable
