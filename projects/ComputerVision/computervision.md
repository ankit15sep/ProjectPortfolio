# Computer Vision Projects

This page covers some of my computer vision projects. The code for these projects is in a private repo which is available upon request.

## A) Compression and Filtering<br>
Compression is the way to reduce the size of an image by reducing information in the image by only selecting the frequencies which have a
higher contribution for a given image, based on a threshold value. Only the amplitudes (magnitude) greater than the threshold will be
retained in the complex plane.
With higher compression, the threshold is higher. This means only a handful of frequencies will be picked and a lot of information may be
lost. The image will loose most of the details. The dog images below show that.

<p align="center">
  <img src="../../assets/ComputerVision/01_Compression_and_Filtering/dog.jpg" width="200"/><br>
  <em>Figure A1: Input image Dog</em>
</p>

<p align="center">
  <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-4-a-1.jpg" width="200"/> <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-4-a-1-freq.jpg" width="200"/><br>
  <em>Figure A2: Compressed image and FFT (lower threshold)</em>
</p>
<p align="center">
  <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-4-a-3.jpg" width="200"/> <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-4-a-3-freq.jpg" width="200"/><br>
  <em>Figure A3: Compressed image and FFT (higher threshold)</em>
</p>

Filtering is the way to filter out the frequency content of an image (Low pass or high pass) irrespective of the magnitude.
When filtering with a low pass, the high frequency content is filtered out which leads to ringing . Ringing is basically ripples appearing in
the image once high frequency noise is filtered out, which contain more information about the edges in an image. As seen in the cat example,
the more high frequency content we removed, the ringing becomes more and more prominent.

<p align="center">
  <img src="../../assets/ComputerVision/01_Compression_and_Filtering/cat.jpg" alt="System Diagram" width="200"/><br>
  <em>Figure A4: Input image Cat</em>
</p>

<p align="center">
  <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-5-a-1.jpg" width="200"/> <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-5-a-1-freq.jpg" width="200"/><br>
  <em>Figure A5: Filtered image and low pass filter</em>
</p>

<p align="center">
  <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-5-a-3.jpg" width="200"/> <img src="../../assets/ComputerVision/01_Compression_and_Filtering/ps2-5-a-3-freq.jpg" width="200"/><br>
  <em>Figure A6: Filtered image  and low pass filter</em>
</p>

## B) Lucas Kanade

Tracking image shift - More details coming soon 

<p align="center">
  <img src="../../assets/ComputerVision/02_LK/Shift0.png" width="200"/> <img src="../../assets/ComputerVision/02_LK/ShiftR2.png" width="200"/><br>
  <em>Figure B1:Input image 0 shift and right shift 2 units</em>
</p>
<p align="center">
  <img src="../../assets/ComputerVision/02_LK/ps4-1-a-1.jpg" width="200"/><br>
  <em>Figure B2: Lucas Kanade optical flow
</p>

## C) Gaussian and Laplacian Pyramid

More content coming soon

<p align="center">
  <img src="../../assets/ComputerVision/03_Gaussian_and_LaplacianPyramid/ps4-2-a-1.jpg" width="200"/><br>
  <em>Figure C1: Gaussian Pyramid
</p>

<p align="center">
  <img src="../../assets/ComputerVision/03_Gaussian_and_LaplacianPyramid/ps4-2-b-1.jpg" width="200"/><br>
  <em>Figure C2: Laplacian Pyramid
</p>

## D) Object detection and Tracking - Particle filters

More content coming soon

<p align="center">
  <img src="../../assets/ComputerVision/04_ObjectDetection/ps5-6-a-1.png" width="200"/> <img src="../../assets/ComputerVision/04_ObjectDetection/ps5-6-a-2.png" width="200"/> <img src="../../assets/ComputerVision/04_ObjectDetection/ps5-6-a-3.png" width="200"/><br>
  <em>Figure D1: Object detection and Tracking using particle filters
</p>

## E) Face Detection

More content coming soon

<p align="center">
  <img src="../../assets/ComputerVision/04_FaceDetection/ps6-1-a-1.png" width="200"/> <img src="../../assets/ComputerVision/04_FaceDetection/ps6-1-b-1.png" width="200"/> <br>
  <em>Figure E1: Average face and Eigen faces
</p>

## F) CNN Digit classification and Detection

Digit classification and detection - (https://drive.google.com/file/d/13VlsIiL7V8To27km389ZbwALut2mUxDG/view?usp=drive_link)


