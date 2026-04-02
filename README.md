# Non Linear Non Volterra DSP Batch Processor
Non-Linear DSP Web Batch Processor ("AudioForge SonicScope MutantWave DSP Engine")
Developed a high-speed audio processing engine utilizing Non-Volterra functional series for non-linear system modeling. Designed a cross-platform pipeline where core DSP algorithms were implemented in MATLAB/GNU Octave and deployed as a scalable Node.js batch-processing frontend service.

**Memory Efficiency**
Optimized for low-resource environments, maintaining a footprint of < 500 MB while remaining CPU-efficient.

**Optimization and Time Complexity Overview**
Achieved a significant reduction in time complexity compared to traditional Volterra batch processors. While standard models operate at exponential complexity $O(n^k)$ this implementation maintains an upper bound of $O(n^c)$ where $c << k$. Maintains an algorithmic complexity of $O(n^c)$ significantly outperforming the $O(n^k)$ growth typical of standard Volterra expansions. 

**Performance**
This reduction in complexity allows for real time batch processing with significantly lower CPU cycle requirements.

**Tech Stack**
JavaScript, Node.js, HTML, Python, GNU Octave, MATLAB

**Live Prototype**
https://audioforge-sonicscope-mutantwave-dsp.onrender.com/

© [2026] [Velikov, Aleksandar (Alexander)]. All rights reserved. This project and the underlying technologies are protected by international copyright laws and multiple patents and/or pending patent applications. Unauthorized copying, modification, or distribution of this software/hardware/logic, in whole or in part, is strictly prohibited.
