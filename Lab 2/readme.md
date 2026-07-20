\# Deep Learning Lab – Experiment 2



\## Title

Comparative Study of Activation Functions and Optimization Algorithms in Deep Learning



\## Aim

To analyze the impact of different activation functions and optimization algorithms on the performance of Artificial Neural Networks (ANNs) and to learn best practices for managing deep learning experiments using Google Colab and GitHub.



\---



\## Objectives



\- Understand the role of activation functions in neural networks.

\- Visualize and compare Sigmoid, Tanh, and ReLU activation functions.

\- Evaluate the performance of different activation functions in an ANN.

\- Compare the performance of optimization algorithms such as SGD, Momentum, RMSProp, and Adam.

\- Learn experiment management using Google Colab and GitHub.

\- Maintain reproducible deep learning experiments using version control.



\---



\## Software Requirements



\- Python 3.x

\- TensorFlow 2.x

\- Google Colab

\- GitHub

\- NumPy

\- Matplotlib



\---



\## Experiment Overview



\### Part A – Visualization of Activation Functions

\- Implemented and plotted:

&#x20; - Sigmoid

&#x20; - Tanh

&#x20; - ReLU

\- Compared their output range, gradient behavior, computational efficiency, and applications.



\### Part B – Performance Comparison of Activation Functions

Built identical ANN architectures using:

\- Sigmoid

\- Tanh

\- ReLU



Compared:

\- Training Accuracy

\- Validation Accuracy

\- Training Loss

\- Validation Loss

\- Convergence Speed



\### Part C – Comparison of Optimization Algorithms

Trained the ANN using:

\- Stochastic Gradient Descent (SGD)

\- Momentum

\- RMSProp

\- Adam



Compared:

\- Training Loss

\- Validation Loss

\- Training Accuracy

\- Validation Accuracy

\- Convergence Speed



Generated graphs for:

\- Loss vs Epoch

\- Accuracy vs Epoch



\### Part D – Deep Learning Experiment Management

\- Created the experiment in Google Colab.

\- Mounted Google Drive.

\- Saved the trained ANN model.

\- Uploaded the notebook to GitHub.

\- Managed version history using Git.



\---



\## Results



\### Activation Functions

\- ReLU achieved the highest accuracy and fastest convergence.

\- Tanh performed better than Sigmoid.

\- Sigmoid showed slower convergence due to the vanishing gradient problem.



\### Optimization Algorithms

\- Adam converged the fastest and produced the best validation accuracy.

\- RMSProp achieved competitive performance.

\- Momentum improved over standard SGD.

\- SGD required more epochs to converge.



\---



\## Conclusion



The experiment demonstrated that both activation functions and optimization algorithms significantly influence the learning capability and convergence speed of Artificial Neural Networks. ReLU combined with the Adam optimizer provided the best overall performance, making it the preferred choice for most deep learning applications.



\---



\## Repository Structure



```

Lab 2/

│── DL\_LAB\_2.ipynb

│── README.md

```



\---



\## Student Details



\- \*\*Name:\*\* Jack Solomon

\- \*\*Roll No:\*\* 24BAD113

\- \*\*Course:\*\* 24ADI006 – Deep Learning

\- \*\*Experiment No:\*\* 2

