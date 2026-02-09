IPS — Image Processing Studio
IPS (Image Processing Studio) is a GUI‑based Python application developed for the Image Processing and Fundamentals of Computer Vision course at Bahonar University.

The software is designed as an educational and practical tool to demonstrate core concepts of digital image processing using OpenCV, NumPy, and Fourier analysis.

🎯 Project Objectives
The main goals of IPS are:

To provide a hands‑on learning environment for image processing concepts
To visualize spatial and frequency domain operations
To help students understand how OpenCV functions are actually used
To bridge the gap between theory and implementation
A key educational feature of IPS is the real‑time OpenCV (CV2) code viewer, which displays the exact code executed for each image processing operation.

✨ Key Features
📂 Image Management
Open images in common formats (JPG, PNG, BMP)
Save processed images to disk
Reset image to its original state at any time
🖼️ Image Visualization
Real‑time image preview
Color and intensity visualization
Image histogram display
Grayscale histogram
Color channel histograms
Histogram updates dynamically after each operation
🧮 Image Operations (Spatial Domain)
Basic image manipulation tools implemented using OpenCV:

Image inversion
Rotation
Flipping
Intensity transformations
Pixel‑level operations
These operations help demonstrate spatial domain processing fundamentals.

🔊 Noise Addition
IPS allows controlled noise modeling for experimentation and analysis:

Salt & Pepper Noise
Gaussian Noise
Noise parameters can be adjusted to observe their effect on image quality and frequency content.

🧹 Denoising Filters
Noise reduction filters commonly taught in image processing courses:

Mean Filter
Median Filter
Gaussian Filter
Bilateral Filter
These filters allow direct comparison between different denoising techniques.

🎛️ Frequency Domain Processing (Fourier Analysis)
IPS includes a full Fourier Transform workflow:

Fast Fourier Transform (FFT)
Inverse FFT
Frequency domain visualization
Frequency Filters:
Low‑Pass Filter
High‑Pass Filter
Gaussian Filter
Notch Pass Filter
Notch Reject Filter
These filters demonstrate how frequency manipulation affects spatial image characteristics.

📊 Fourier Visualization Panels
IPS provides detailed frequency‑domain visualizations:

Magnitude Spectrum (log scale)
Power Spectrum
Phase Spectrum
Radial Average of Magnitude Spectrum
These visual tools help users understand the distribution of frequency components in images.

🧠 Real‑Time OpenCV Code Viewer (Educational Feature)
One of the most important features of IPS:

Displays the exact OpenCV (cv2) code executed for:
Filters
Noise addition
Denoising
Image operations
Updates dynamically as operations are applied
Shows only the relevant CV2 functions, not the entire application code
This feature is designed specifically for learning and teaching purposes.

🧱 Software Architecture
Developed in Python
Uses:
OpenCV (cv2)
NumPy
Matplotlib (for plots)
GUI framework (PyQt / Tkinter based)
Core Design Concepts:
Separation between:
Original image
Working image
Modular filter and operation handlers
Centralized code‑generation logic for CV2 viewer
🧪 Typical Workflow
Load an image
Inspect histogram and visualization
Add noise to the image
Apply denoising filters
Perform Fourier analysis
Apply frequency filters
View real‑time OpenCV code
Save final result
🎓 Academic Context
This project was developed as part of the Image Processing and Fundamentals of Computer Vision course at Bahonar University.

It is intended for:

Undergraduate students
Computer vision beginners
Digital image processing laboratories
📚 Topics Covered
Spatial domain processing
Frequency domain processing
Noise modeling
Image filtering
Fourier Transform
Histogram analysis
OpenCV practical usage
📄 License
This project is released under the MIT License and is free to use for educational purposes.

🤝 Contributions
Contributions, improvements, and suggestions are welcome.

Feel free to open issues or submit pull requests.

📌 Final Note
IPS is not just an image processing tool —

it is a learning platform designed to help students see, apply, and understand the fundamentals of computer vision through real code and real results.
