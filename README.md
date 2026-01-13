<h1> Commputer Vision & Imaging Technologies Labs</h1>

<h2>Description</h2>
This repo contains all laboratory work completed for the <b>Imaging Technologies</b> course.  
The labs focus on <b>digital image processing, signal processing, and basic deep learning</b> through hands-on image manipulations and analysis.  
The work covers both <b>spatial-domain and frequency-domain techniques</b>, as well as an introduction to <b>Convolutional Neural Networks (CNNs)</b> using real image datasets.  
All experiments were conducted using provided image samples as part of the course requirements.

<br />
<br />
<br />

  

<h2>Images</h2>

<p align="center">
Laplacian Sharpening: <br/>
<img src="https://i.imgur.com/l3SQHK4.png" height="80%" width="80%" alt="Original Image"/>
<br />
<br />

Intensity transformation result: <br/>
<img src="https://i.imgur.com/CEYG0Iy.png" height="80%" width="80%" alt="Intensity Transformation"/>
<br />
<br />

Gamma Transformation: <br/>
<img src="https://i.imgur.com/7n2UCUr.png" height="80%" width="80%" alt="Spatial Filtering"/>
<br />
<br />

Frequency-domain filtering result: <br/>
<img src="https://i.imgur.com/oVYibuP.png" height="80%" width="80%" alt="Frequency Domain Filtering"/>
<br />
<br />
</p>

<b>Course Outcomes & Skills:</b>  
This course focused on the theoretical foundations and practical implementation of digital imaging and image processing. Key skills and knowledge gained include:
- Understanding of <b>imaging systems</b>, sensors, and digital cameras  
- Application of <b>sampling, digitization, and image quality evaluation</b>  
- Use of <b>intensity transformations</b> for contrast enhancement (log, power-law, piecewise, sigmoid)  
- Hands-on experience with <b>spatial filtering</b>, kernels, Gaussian filters, and image derivatives  
- Implementation of <b>frequency-domain processing</b> using Fourier Transform and FFT  
- Design and comparison of <b>low-pass filters</b> (Ideal, Gaussian, Butterworth)  
- Application of <b>smoothing, sharpening, and edge detection</b> techniques  
- Introduction to <b>Convolutional Neural Networks (CNNs)</b> using the MNIST dataset  

<h2>Laboratory Work</h2>

<b>Lab 1 – Introduction to Imaging</b>  
- Imaging fundamentals  
- Sensors and digital cameras  
- Image acquisition and inspection  

<br />

<b>Lab 2 – Intensity Transformations</b>  
- Logarithmic (log) transformation  
- Power-law (gamma) transformation  
- Piecewise intensity transformation  
- Sigmoid (S-curve) transformation  
- Contrast enhancement analysis  

<br />

<b>Lab 3 – Histogram & Spatial Filtering</b>  
- Cumulative Distribution Function (CDF)  
- Kernel-based filtering  
- Gaussian filtering  
- Spatial filters  
- Image derivatives  

<br />

<b>Lab 4 – Frequency Domain Filtering</b>  
- Fourier Transform (FT) and FFT  
- Frequency spectrum analysis  
- Effect of changing filter equations and parameters  
- Implemented filters:  
  - <b>Ideal Low-Pass Filter</b>: cutoff ≤ cutoff_radius  
  - <b>Gaussian Low-Pass Filter</b>: exp(-D<sub>uv</sub><sup>2</sup> / (2·cutoff_radius<sup>2</sup>))  
  - <b>Butterworth Low-Pass Smoothing Filter</b>: 1 / (1 + (D<sub>uv</sub> / cutoff_radius))<sup>2n</sup>  

<br />

<b>Lab 5 – Spatial Filtering & CNNs</b>  
- Image smoothing and weighted filters  
- Image sharpening  
- Vector color edge detection  
- CNN implementation using the <b>MNIST dataset</b>
