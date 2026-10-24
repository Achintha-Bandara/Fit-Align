# EN3160 Assignment 2 - Fitting and Alignment

This repository contains the implementation and results for Assignment 2 of **EN3160 - Image Processing and Machine Vision**.

### Assignment Topics

1. **Blob Detection Using Laplacian of Gaussians**
   - Scale-space representation and Laplacian of Gaussian (LoG) filtering
   - Scale-space extrema detection
   - Blob detection in a sunflower field image
   - Circle visualization and analysis
   - Investigation of scale parameters and detected circle sizes

2. **Line Fitting Using RANSAC**
   - Generation and analysis of noisy point sets
   - Implementation of the Random Sample Consensus (RANSAC) algorithm
   - Line estimation using sampled points
   - Normal-distance error calculation
   - Consensus set identification and inlier selection
   - Best-fit line estimation using total least squares

3. **Circle Fitting Using RANSAC**
   - Circle estimation from three sampled points
   - Radial error calculation and inlier selection
   - RANSAC-based circle detection
   - Best-fit circle estimation using nonlinear optimization
   - Visualization of sampled points, inliers, and estimated models
   - Comparison of line-first and circle-first fitting strategies

4. **Image Compositing Using Homography**
   - Selection of planar surfaces in architectural images
   - Correspondence selection using four point pairs
   - Homography estimation between two images
   - Perspective warping of flag images
   - Image blending and visualization of the composited results

5. **PCB Image Alignment and Difference Analysis**
   - SIFT feature detection and descriptor extraction
   - Feature matching using `cv2.BFMatcher()`
   - Homography estimation using RANSAC
   - Visualization of feature matches
   - Perspective warping of PCB images to align with a reference template
   - Pixel-wise difference computation and visualization
   - Analysis of differences caused by component variations, alignment errors, and imaging conditions
