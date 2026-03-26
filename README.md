# Edge Enhancement using Digital Image Processing

This project implements first-order (**Sobel**) and second-order (**Laplacian**) derivative operators to analyze intensity gradients and perform boundary extraction. Developed as part of a Digital Signal Processing study, it demonstrates the mathematical application of spatial filters for image sharpening and feature detection.

##  Key Features
* **Gradient Computation:** Implementation of Sobel kernels to detect horizontal and vertical edges.
* **Second-Order Analysis:** Utilizing Laplacian operators for high-frequency detail enhancement.
* **Image Superimposition:** An algorithm to overlay detected edges back onto the original signal to produce a "sharpened" output.
* **Python Implementation:** Developed using **OpenCV**, **NumPy**, and **Matplotlib** in a Jupyter environment.

##  Visual Analysis

Each image panel below demonstrates the full transformation pipeline:
1.  **Original Input Signal**
2.  **Boundary Extraction** 
3.  **Filtered & Enhanced Result** (Gradient analysis using Sobel/Laplacian)

### Sobel Enhanced Image
![Edge Enhancement using Sobel Operator](https://github.com/priyankapunjabi15/edge-enhancement-python-opencv/blob/main/sobel_results/Picture1.png)

### Laplacian Enhanced Image
![Edge Enhancement using Laplacian Filter](https://github.com/priyankapunjabi15/edge-enhancement-python-opencv/blob/main/laplacian_results/Picture1.png)

---

##  Project Structure
* `Edge_Enhancement.ipynb`: The main interactive notebook containing the Python implementation and step-by-step mathematical derivations.
* `Technical_Report.pdf`: Comprehensive documentation covering the theory of spatial filtering and result analysis.
* `input_images/`: Raw images used for testing.
* `output_images/`: Generated results showing boundary extraction.

##  Requirements
To run the notebook locally, ensure you have the following installed:
```bash
pip install opencv-python numpy matplotlib
```

##  Documentation
For a deep dive into the mathematical implementation and performance comparison of different kernels, please refer to the ![Technical Report](https://github.com/priyankapunjabi15/edge-enhancement-python-opencv/blob/main/Report.pdf)
