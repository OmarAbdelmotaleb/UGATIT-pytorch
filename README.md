## U-GAT-IT &mdash; Official PyTorch Implementation
### : Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation

### Here is a step-by-step guide to reproduce the results obtained for the final report.

<ol>
<li>Install CUDA.</li>
<li>Pull the code to a source folder. Download the dataset as well and place into the dataset directory.</li>
<li>Install Anaconda.</li>
<li>Create and activate the environment with the source folder active.</li>
<li>Install the respective packages outlined in Tools & Technologies (i.e. torch, cv2, scipy, numpy)</li>
<li>Run the code using python main.py --dataset selfie2anime --light True</li>
<li>Wait and let the models save to the results directory.</li>
<li>Run the code using python main.py --dataset selfie2anime --light True --phase test</li>
<li>Wait and let the tests save to the results directory.</li>
<li>View the results directory under tests to see the resulting images.</li>
</ol>