PSF-Optimized Meta-Optics for Segmentation-Inspired Kernels
This repository contains a Colab notebook for designing RGB meta-optics that replicate small convolutional kernels derived from the Carvana segmentation dataset. The notebook demonstrates optimization for a subset of 8 example kernels out of a total of 56 available 3×3 filters.
Summary
- Optimizes metasurfaces to generate 3×3 RGB kernels from segmentation-oriented features.
- Uses a differentiable phase proxy and wave-optics propagation to simulate the resulting PSFs at the focal plane.
- Separates each kernel into positive and negative optical components for physical realizability.
- Designs are targeted at 450, 532, and 635 nm to align with RGB laser diodes.
- Loss function minimizes the error between target PSFs and simulated responses using TensorFlow-based optimization.
Included
- TF_for_PSF_Engineering_Carvana_Segmentation.ipynb: Google Colab notebook for simulating and optimizing meta-optics using a sample of 8 RGB kernels.
Requirements
- Google Colab
- TensorFlow
- NumPy, SciPy, Matplotlib
License
Released under the MIT License.
