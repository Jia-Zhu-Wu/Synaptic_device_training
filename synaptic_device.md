# Quantizaion synaptic device simulator 

This quantization‑based CNN model was developed by Jia‑Zhe Wu. It uses a straightforward quantization scheme to emulate the behavior of optical and electrical synaptic devices entirely in software.

Because the papers that inspired this work did not release source code, I combined several of their ideas and implemented a complete neural‑network model, documenting every detail as thoroughly as possible. To help users who prefer not to read or write code, I also built a graphical user interface (GUI).

The current version employs simple linear quantization: weights are mapped to the range [‑1, 1], and only the fully connected layers are quantized. (In real spiking‑neural‑network hardware, precise synaptic devices suitable for CNN‑based SNNs are still lacking.)

## installation steps
1. Clone the repository to your computer.

## Software version and hardware equipment 
The following software version which have been test
1. python 3.13
2. pythorch Preview(Nightly), CUDA 12.8
3. GPU RTX5080 

## Reference 
1. "Biological UV Photoreceptors-Inspired Sn-Doped Polycrystalline 𝜷-Ga2O3 Optoelectronic Synaptic Phototransistor for Neuromorphic Computing", 
Youngbin Yoon, Youngki Kim, Wan Sik Hwang, and Myunghun Shin*
2. "Adaptive Weight Quantization Method for Nonlinear Synaptic Devices", Dongseok Kwon, Suhwan Lim, Jong-Ho Bae, Byung-Gook Park, Sung-Tae Lee, Hyeongsu Kim, Chul-Heung Kim, Member, IEEE, and Jong-Ho Lee
3. "An electro-photo-sensitive synaptic transistor for edge neuromorphic visual systems",Nian Duan,a Yi Li, aHsiao-Cheng Chiang, Jia Chen Wen-Qian Pan, Ya-Xiong Zhou, Yu-Chieh Chien, Yu-Hui He, Kan-Hao Xue, Gang Liu, Ting-Chang Chang, bandXiang-Shui Miao