
# KMNIST Optimizer Comparison Project

## Introduction

This project compares the performance of three popular optimization algorithms—Adam, RMSprop, and AdamW—on an Artificial Neural Network (ANN) using the Kuzushiji-MNIST (KMNIST) dataset.

## Dataset Description

The KMNIST dataset is a collection of 70,000 grayscale images of cursive Japanese (Kuzushiji) characters. It consists of:
- 60,000 training images
- 10,000 test images
Each image is 28x28 pixels and belongs to one of ten classes representing different Kuzushiji characters.

## Project Structure

- `midterm_project.ipynb`: Notebook containing the code and results.
- `README.md`: This file with instructions on setting up and running the project.
- `requirements.txt`: List of required Python packages.
- `accuracy_comparison.png`: Graphical visualization of the results.

## Setup and Execution

### Clone the Repository

```bash
git clone https://github.com/hoz-efa/Advanced-Deep-Learning-AIGC-5500-0NA-Midterm-Project.git
cd Advanced-Deep-Learning-AIGC-5500-0NA-Midterm-Project
```

### Install Required Packages

Ensure you have Python 3.6 or higher installed. Then, install the required packages using pip:

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

To reproduce the results, run the Jupyter Notebook:

```bash
Colab notebook
```

Open `midterm_project.ipynb` and execute the cells sequentially.

## Results Summary

| Optimizer | Learning Rate | Training Accuracy | Test Accuracy |
|-----------|----------------|-------------------|---------------|
| Adam      | 0.001          | 91.86%            | 91.86%        |
| RMSprop   | 0.001          | 91.68%            | 91.68%        |
| AdamW     | 0.001          | 92.02%            | 92.02%        |

### Best Result
- **Best Test Accuracy:** 92.02%
- **Best Optimizer:** AdamW
- **Parameters:** `learning_rate = 0.001`

## Visual Results

### Training Loss Over Epochs
![Training Loss Over Epochs (1)](https://github.com/hoz-efa/Advanced-Deep-Learning-AIGC-5500-0NA-Midterm-Project/assets/136026095/5236c2ed-20af-487b-8ddc-c677982ec69c)

### Training Accuracy Over Epochs
![Training Accuracy Over Epochs (1)](https://github.com/hoz-efa/Advanced-Deep-Learning-AIGC-5500-0NA-Midterm-Project/assets/136026095/34ee38d6-f5b0-42bb-8995-f18c4d6820af)


## Group Member Contributions

## References

- [Adam Optimization Algorithm](https://arxiv.org/abs/1412.6980)
- [RMSprop: Divide the gradient by a running average of its recent magnitude](https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf)
- [AdamW and Super-Convergence is Now the Best Optimizer](https://arxiv.org/abs/1711.05101)
- KMNIST Dataset: [GitHub Repository](https://github.com/rois-codh/kmnist)
