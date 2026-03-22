# Non Linear Non Volterra DSP Batch Processor
A new instant audio web batch processor based on Non - Linear Non - Volterra DSP theory. 

**Optimization and Time Complexity Overview**

This is a fast processor that can operate on as little as < 500 MB while being memory efficient and cheap 
on a CPU. Time Complexity is between $O(1)$ $\le$ $O(n)$ $\le$ $O(n^c)$ where by comparison to Volterra batch processors
operating on exponential time complexity $O(n^k)$. For this Non-Volterra processor the upper limit $O(n^c)$ is
such that $c << k$. This achieves faster speed all while requiring less CPU cycles in addition to being cheap in memory. Based on multiple 
pending or issued patents.

**Tech Stack**

Javascript, Node.js, HTML, Python, Octave, MATLAB
