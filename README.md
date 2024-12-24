# [WACV 2024] Towards High-fidelity Head Blending with Chroma Keying for Industrial Applications

**Towards High-fidelity Head Blending with Chroma Keying for Industrial Applications**
Hah Min Lew*, Sahng-Min Yoo*, Hyunwoo Kang*, and <bold>Gyeong-Moon Park<\bold> 

[[Paper]](https://arxiv.org/abs/2411.00652) [Project Page](https://hahminlew.github.io/changer/)

## Abstract
We introduce an industrial Head Blending pipeline for the task of seamlessly integrating an actor's head onto a target body in digital content creation. The key challenge stems from discrepancies in head shape and hair structure, which lead to unnatural boundaries and blending artifacts. Existing methods treat foreground and background as a single task, resulting in suboptimal blending quality. To address this problem, we propose CHANGER, a novel pipeline that decouples background integration from foreground blending. By utilizing chroma keying for artifact-free background generation and introducing Head shape and long Hair augmentation ($H^2$ augmentation) to simulate a wide range of head shapes and hair styles, CHANGER improves generalization on innumerable various real-world cases. Furthermore, our Foreground Predictive Attention Transformer (FPAT) module enhances foreground blending by predicting and focusing on key head and body regions. Quantitative and qualitative evaluations on benchmark datasets demonstrate that our CHANGER outperforms state-of-the-art methods, delivering high-fidelity, industrial-grade results.
