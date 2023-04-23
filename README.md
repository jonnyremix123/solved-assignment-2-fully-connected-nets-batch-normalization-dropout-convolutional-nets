Download Link: https://assignmentchef.com/product/solved-assignment-2-fully-connected-nets-batch-normalization-dropout-convolutional-nets
<br>
in this assignment you will practice writing backpropagation code, and training Neural Networks and Convolutional Neural Networks. The goals of this assignment are as follows:

<ul>

 <li>understand <strong>Neural Networks</strong> and how they are arranged in layered architectures</li>

 <li>understand and be able to implement (vectorized) <strong>backpropagation</strong></li>

 <li>implement various <strong>update rules</strong> used to optimize Neural Networks</li>

 <li>implement <strong>Batch Normalization</strong> and <strong>Layer Normalization</strong> for training deep networks</li>

 <li>implement <strong>Dropout</strong> to regularize networks</li>

 <li>understand the architecture of <strong>Convolutional Neural Networks</strong> and get practice with training these models on data</li>

 <li>gain experience with a major deep learning framework, such as <strong>TensorFlow</strong> or <strong>PyTorch</strong>.</li>

</ul>

<h2 id="setup">Setup</h2>

Get the code as a zip file <a href="https://cs231n.github.io/assignments/2019/spring1819_assignment2.zip">here</a>.

You can follow the setup instructions <a href="https://cs231n.github.io/setup-instructions">here</a>.

If you performed the google cloud setup already for assignment1, you can skip this step and use the virtual machine you created previously. (However, if you’re using your virtual machine from assignment1, you might need to perform additional installation steps for the 5th notebook depending on whether you’re using Pytorch or Tensorflow. See below for details.)

<h3 id="some-notes">Some Notes</h3>

<strong>NOTE 1:</strong> This year, the <code class="highlighter-rouge">assignment2</code> code has been tested to be compatible with python version <code class="highlighter-rouge">3.7</code> (it may work with other versions of <code class="highlighter-rouge">3.x</code>, but we won’t be officially supporting them). You will need to make sure that during your virtual environment setup that the correct version of <code class="highlighter-rouge">python</code> is used. You can confirm your python version by (1) activating your virtualenv and (2) running <code class="highlighter-rouge">which python</code>.

<strong>NOTE 2:</strong> As noted in the setup instructions, we recommend you to develop on Google Cloud, and we have limited support for local machine configurations. In particular, for students who wish to develop with Windows machines, we recommend installing a Linux subsystem (preferably Ubuntu) via the <a href="https://docs.microsoft.com/en-us/windows/wsl/install-win10">Windows App Store</a> to streamline the AFS submission process.

<strong>NOTE 3:</strong> The submission process this year has <strong>2 steps</strong>, requiring you to 1. run a submission script and 2. download/upload an auto-generated pdf (details below.) We suggest <strong><em>making a test submission early on</em></strong> to make sure you are able to successfully submit your assignment on time (a maximum of 10 successful submissions can be made.)

<h3 id="q1-fully-connected-neural-network-20-points">Q1: Fully-connected Neural Network (20 points)</h3>

The IPython notebook <code class="highlighter-rouge">FullyConnectedNets.ipynb</code> will introduce you to our modular layer design, and then use those layers to implement fully-connected networks of arbitrary depth. To optimize these models you will implement several popular update rules.

<h3 id="q2-batch-normalization-30-points">Q2: Batch Normalization (30 points)</h3>

In the IPython notebook <code class="highlighter-rouge">BatchNormalization.ipynb</code> you will implement batch normalization, and use it to train deep fully-connected networks.

<h3 id="q3-dropout-10-points">Q3: Dropout (10 points)</h3>

The IPython notebook <code class="highlighter-rouge">Dropout.ipynb</code> will help you implement Dropout and explore its effects on model generalization.

<h3 id="q4-convolutional-networks-30-points">Q4: Convolutional Networks (30 points)</h3>

In the IPython Notebook <code class="highlighter-rouge">ConvolutionalNetworks.ipynb</code> you will implement several new layers that are commonly used in convolutional networks.

<h3 id="q5-pytorch--tensorflow-on-cifar-10-10-points">Q5: PyTorch / TensorFlow on CIFAR-10 (10 points)</h3>

For this last part, you will be working in either TensorFlow or PyTorch, two popular and powerful deep learning frameworks. <strong>You only need to complete ONE of these two notebooks.</strong> You do NOT need to do both, and we will <em>not</em> be awarding extra credit to those who do.

Open up either <code class="highlighter-rouge">PyTorch.ipynb</code> or <code class="highlighter-rouge">TensorFlow.ipynb</code>. There, you will learn how the framework works, culminating in training a convolutional network of your own design on CIFAR-10 to get the best performance you can.

<strong>NOTE 1</strong>: The PyTorch notebook requires PyTorch version 1.0, which comes pre-installed on the Google cloud instances.

<strong>NOTE 2</strong>: The TensorFlow notebook requires Tensorflow version 2.0. If you want to work on the Tensorflow notebook with your VM from assignment1, please follow the instructions on <a href="https://piazza.com/class/js3o5prh5w378a?cid=384">Piazza</a> to install TensorFlow. New virtual machines that are set up following the <a href="https://cs231n.github.io/setup-instructions">instructions</a> will come with the correct version of Tensorflow.