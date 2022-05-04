## U-GAT-IT &mdash; Official PyTorch Implementation
### : Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation

### Here is a step-by-step guide to reproduce the results obtained for the final report.

<ol>
<li>0.) Install CUDA.</li>
<li>1.) Pull the code to a source folder. Download the dataset as well and place into the dataset directory.</li>
<li>2.) Install Anaconda.</li>
<li>3.) Create and activate the environment with the source folder active.</li>
<li>4.) Install the respective packages outlined in Tools & Technologies (i.e. torch, cv2, scipy, numpy)</li>
<li>5.) Run the code using python main.py --dataset selfie2anime --light True</li>
<li>6.) Wait and let the models save to the results directory.</li>
<li>7.) Run the code using python main.py --dataset selfie2anime --light True --phase test</li>
<li>8.) Wait and let the tests save to the results directory.</li>
<li>9.) View the results directory under tests to see the resulting images.</li>
</ol>