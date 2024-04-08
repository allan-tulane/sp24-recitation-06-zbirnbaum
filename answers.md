# CMPS 2200 Recitation 06
## Answers

**Name: Zoe Birnbaum**


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
  W(n) = 1 + W(n-1) + W(n-2) -> O(2^n)
  

- **3)**
  S(n) = 1 + S(n-1) -> O(n)

- **4)**
  The pattern that emerges with `counts` is that counts[1] is the largest number, followed by counts[0] == counts[2], followed by counts[i>2] respectively until the last two numbers, which are == 1. Generally speaking, the numbers decrease as we move down the list until we reach 1. 

- **6)**
  The maximum number of times fib_top_down(i) will be called is n.
  W(n) = O(n)
  S(n) = O(n)

- **8)**
  The maximum number of times Fi will be read is twice. 
  W(n) = O(n)
  S(n) = O(n)
