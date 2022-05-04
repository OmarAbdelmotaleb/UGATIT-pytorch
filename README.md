## U-GAT-IT &mdash; Official PyTorch Implementation
### : Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation

### Here is a step-by-step guide to reproduce the results obtained for the final report.

0.) Install CUDA.
1.) Pull the code to a source folder. Download the dataset as well and place into the dataset directory.
2.) Install Anaconda.
3.) Create and activate the environment with the source folder active.
4.) Install the respective packages outlined in Tools & Technologies (i.e. torch, cv2, scipy, numpy)
5.) Run the code using python main.py --dataset selfie2anime --light True
6.) Wait and let the models save to the results directory.
7.) Run the code using python main.py --dataset selfie2anime --light True --phase test
8.) Wait and let the tests save to the results directory.
9.) View the results directory under tests to see the resulting images.