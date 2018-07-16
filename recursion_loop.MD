---
tittle: use stack and loop instead of recursion
key words: stack, loop and recursion
---
## This file defines describe how to transfer recursion into loop
---
 When you are writing code, there may be a situation that all stack, loop and recursion can be used to solve your problem. But, what's difference among these three algorithm? Are all these algorithm same or a certain algorithm is more proper in some certain situation?
 #### Recursion
 Recursion occurs when a thing is defined in terms of itself or of its type. When you use recursion algorithm, there should be a batch of stack memory to mentain recursion algorithm. Also stack memory is faster than heap memory, but stack memory is very limited in a computer. For windows operation system computer, there are only 1M bit stack memory. That means your recursion will lead to memory leack if your recursion goes to deep when it tries to solve a complex porblem. Then there may be incorrect result calculated.
 #### Loop 