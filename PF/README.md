# EKF-UKF-ParticleFilter-Practice

This repository presents practical implementations of three prominent state estimation techniques: Extended Kalman Filter(EKF), Unscented Kalman Filter(UKF), and Particle Filter(PF). These algorithms are applied to nonlinear systems to estimate their states accurately.([GitHub][1])

## Overview

State estimation is crucial in control systems, robotics, and signal processing. This project demonstrates how EKF, UKF, and PF can be used to estimate the state of nonlinear systems, providing insights into their performance and applicability.

## Repository Structure

* **EKF-UKF.ipynb**: A Jupyter Notebook implementing both the Extended Kalman Filter and Unscented Kalman Filter. It includes simulations and visualizations to illustrate the estimation process.
* **PF**: A directory containing the implementation of the Particle Filter algorithm, along with an example demonstrating its application.
* **pendulum\_noisy\_data.xlsx**: An Excel file containing noisy measurement data for a pendulum system, used for testing and validating the filters.

## Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.x
* Jupyter Notebook
* NumPy
* Matplotlib
* Pandas([GitHub][2])

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ErfanJoodi/EKF-UKF-ParticleFilter-Practice.git
   ```


2\. Navigate to the project directory:

```bash
cd EKF-UKF-ParticleFilter-Practice
```


3\. Install the required Python packages:

```bash
pip install -r requirements.txt
```



## Usage

### Extended Kalman Filter (EKF) & Unscented Kalman Filter (UKF)

Open the `EKF-UKF.ipynb` notebook in Jupyter Notebook to explore the implementations of EKF and UKF. The notebook provides step-by-step explanations, simulations, and visualizations to facilitate understanding.

### Particle Filter (PF)

Navigate to the `PF` directory to access the Particle Filter implementation. The provided example demonstrates how the PF can be applied to estimate the state of a nonlinear system using noisy measurements.

## Data

The `pendulum_noisy_data.xlsx` file contains simulated noisy measurements of a pendulum system. This data is used to test and compare the performance of the different filters implemented in this project.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to fork the repository and submit a pull request.