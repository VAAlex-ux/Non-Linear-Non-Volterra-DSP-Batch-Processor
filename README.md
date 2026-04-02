# Non Linear Non Volterra DSP Batch Processor
Non-Linear DSP Web Batch Processor ("AudioForge SonicScope MutantWave DSP Engine")
Developed a high-speed audio processing engine utilizing Non-Volterra functional series for non-linear system modeling. Designed a cross-platform pipeline where core DSP algorithms were implemented in MATLAB/GNU Octave and deployed as a scalable Node.js batch-processing frontend service.

**Optimization and Time Complexity Overview**

This is a fast processor that can operate on as little as < 500 MB while being memory efficient and cheap 
on a CPU. Time Complexity is between $O(1)$ $\le$ $O(n)$ $\le$ $O(n^c)$ where by comparison to Volterra batch processors
operating on exponential time complexity $O(n^k)$. For this Non-Volterra processor the upper limit $O(n^c)$ is
such that $c << k$. This achieves faster speed all while requiring less CPU cycles in addition to being cheap in memory.

**Tech Stack**

JavaScript, Node.js, HTML, Python, GNU Octave, MATLAB

**Prototype Project Link**

https://audioforge-sonicscope-mutantwave-dsp.onrender.com/

© [2026] [Velikov, Aleksandar (Alexander)]. All rights reserved. This project and the underlying technologies are protected by international copyright laws and multiple patents and/or pending patent applications. Unauthorized copying, modification, or distribution of this software/hardware/logic, in whole or in part, is strictly prohibited.
