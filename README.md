# Lab Project: Image Registration using SIFT and Planar Transformations

## Overview

This lab project focuses on image registration techniques, specifically utilizing Scale-Invariant Feature Transform (SIFT) and planar transformations for rigid image registration. 
The primary objectives include extracting invariant features, describing them, matching them, and ultimately using them to compute a homography. 
This project provides insights into the strengths and weaknesses of local feature-based approaches.

## Prerequisites

Please refer to David G. Lowe's paper:

- David G. Lowe, "Distinctive image features from scale-invariant keypoints," International Journal of Computer Vision, 60, 2 (2004), pp. 91-110. [Download Paper](https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf)

## Team Collaborators

Author(s):  **Muhammad Zain Amin**, [Mohammad Imran Hossain](https://github.com/imran-maia)

## Project Tasks

1. **Testing Lowe's Implementation:**
   - Evaluate Lowe's implementation on a set of images featuring skin lesions.
   - Document observations and any potential issues encountered during the testing phase.

2. **Image Registration:**
   - Utilize Lowe's implementation to detect and match features in image pairs depicting the same skin lesion.
   - Implement different motion models by estimating homography matrices for image registration.

3. **Enhancing Registration Accuracy:**
   - Implement data normalization techniques to improve the accuracy of homography estimation.
   - Document the impact of normalization on the overall registration performance.

## Getting Started

1. **Clone the Repository:**
   - Clone this GitHub repository to your local machine.

   ```bash
   git clone https://github.com/your-username/your-repository.git

2. **Dependencies:**

   Ensure you have the following Python libraries and modules installed before running the project:

  - [`numpy`](https://numpy.org/)
  - [`matplotlib`](https://matplotlib.org/)
  - [`opencv`](https://opencv.org/)
  - [`pandas`](https://pandas.pydata.org/)
  - [`scipy`](https://www.scipy.org/)
  - [`scikit-image`](https://scikit-image.org/)
  - [`PIL`](https://pillow.readthedocs.io/)
  - [`google.colab`](https://colab.research.google.com/)

  You can install these dependencies using the following command:

  ```bash
  pip install numpy matplotlib opencv-python pandas scipy scikit-image pillow
