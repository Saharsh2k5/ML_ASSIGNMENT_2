# Overview
This assignment covers various optimization techniques for regression, image, and audio reconstruction using Gradient Descent, Random Fourier Features (RFF), and Matrix Factorization.

# Tasks Completed
## Task 1: Gradient Descent Optimization 
Used torch.autograd to compute the true gradient for linear regression.
Implemented stochastic gradient estimation and verified its accuracy.
Compared full-batch, mini-batch, and stochastic gradient descent, analyzing convergence time.
Visualized loss vs. epochs and contour plots for optimization.
Implemented Gradient Descent with Momentum and compared convergence with vanilla GD.
## Task 2: Image and Audio Reconstruction with RFF (3 Marks)
Used Random Fourier Features (RFF) and Linear Regression for:
Image Reconstruction: Learned mapping from (X, Y) → (R, G, B), computed RMSE & PSNR.
Audio Reconstruction: Learned mapping from time (t) → amplitude (A), computed RMSE & SNR.
## Task 3: Super-Resolution with RFF (4 Marks)
Performed image super-resolution (upscaling 2×) using RFF.
Compared original and reconstructed images qualitatively.
Computed RMSE & PSNR for a quantitative evaluation.
## Task 4: Image Reconstruction using Matrix Factorization (4 Marks)
Implemented Matrix Factorization for image reconstruction.
Reconstructed an image with 900 missing pixels (30×30).
Compared performance of Matrix Factorization vs. RFF using RMSE & PSNR.
## Task 5: Image Compression using Matrix Factorization (3 Marks)
Compressed a 50×50 image patch using low-rank factorization.
Tested different rank values (r = 5, 10, 25, 50).
Evaluated compression quality using RMSE & PSNR.
## Results and Observations
Gradient Descent with Momentum converges faster than vanilla GD.
RFF-based reconstruction effectively reconstructs images and audio.
Matrix Factorization performs well for missing pixel reconstruction but RFF can be more robust.
Super-resolution with RFF improves image quality with quantitative validation.
Low-rank factorization enables effective image compression while preserving important details.
## Note
It is done in group of four
