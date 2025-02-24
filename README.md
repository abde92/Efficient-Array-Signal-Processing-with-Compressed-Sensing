# Efficient-Array-Signal-Processing-with-Compressed-Sensing
Scripts for the technical blog [Efficient Array Signal Processing with Compressed Sensing](https://www.cesimulations.com/blog/signal-processing-with-compressed-sensing/).

## Technical Blog Summary
This technical artical delves into the concept of compressed sensing and its applications in array signal processing, demonstrating its effectiveness through MATLAB implementations.
Compressed sensing offers significant advantages over traditional Direction-of-Arrival (DOA) estimation techniques such as Multiple Signal Classification (MUSIC) and Estimation of Signal Parameters via Rotational Invariance Technique (ESPRIT) algorithms particularly in its ability to accurately recover signals from a limited number of measurements. This approach not only enhances computational efficiency but also improves performance in scenarios with sparse data, making it a powerful tool in modern signal processing. [Read more](https://www.cesimulations.com/blog/signal-processing-with-compressed-sensing/).

## Scripts' Description 
 - <code style="color : Aqua">spasity.mlx</code> showcases the concept of data sparsity. A double-tone signal is sparse in frequency domain which makes it a good candidate for compressed sensing. 
   
 - <code style="color : Aqua">cs_omp.mlx</code> demonstrates how Orthogonal Matching Prsuit(OMP) finding an approximation of a signal using a dictionary.
   
   
 - <code style="color : Aqua">oa_cs.mlx</code> demonstrates building and reconstructing sparse arrays and how compressed sensing can be and efficient useful to estimate direction of arrival using these arrays.

## Prerequisities
- MATLAB
- Phased Array System Toolbox
- Signal Processing Toolbox
- Wavelet Toolbox

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=abde92/Efficient-Array-Signal-Processing-with-Compressed-Sensing)
