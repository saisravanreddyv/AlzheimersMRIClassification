Alzheimer's MRI Classification Using Deep Learning

--About This Project--

This project uses deep learning to classify brain MRI scans into four stages of Alzheimer's disease progression. We implemented and compared four different convolutional neural network architectures to find the most effective approach for automated diagnosis.
Alzheimer's disease is a progressive brain disorder that affects memory and cognitive abilities. Early detection is crucial for better patient outcomes, but analyzing MRI scans manually is time-consuming and prone to error. Our goal was to build a reliable automated system that can assist medical professionals in identifying different stages of the disease.

--Classification Categories--

Non-Demented - No signs of dementia
Very Mild Demented - Early stage with subtle changes
Mild Demented - Noticeable cognitive decline
Moderate Demented - Significant impairment

--Models Implemented--
We tested four popular CNN architectures:

->Model Test Accuracy:
 
 GoogLeNet-->99.21%
 
 ResNet-18-->90.16%
 
 DenseNet-->84.38%
 
 VGG-16-->78.36%
 
-- GoogLeNet performed best thanks to its Inception blocks that capture features at multiple scales, making it ideal for detecting subtle differences in medical images.

--Key Features--

Custom implementations of ResNet-18, DenseNet, VGG-16, and GoogLeNet

Image preprocessing with normalization and augmentation

Weighted sampling to handle class imbalance

Comprehensive evaluation metrics (accuracy, precision, recall, F1-score)

Visualization of predictions and confusion matrices

--Results--

The models excel at identifying moderate dementia cases but face challenges with early-stage classification where visual differences are subtle. GoogLeNet achieved near-perfect classification across all stages, demonstrating the potential of deep learning in medical imaging.
