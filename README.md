# **Iris Flower Classification via Custom Neural Networks**

A data science workspace dedicated to loading the classic Iris floral dataset, preparing raw data for analysis, and building a custom **Deep Learning neural network** from scratch. The project evaluates how different learning speeds affect model accuracy and tests the network's ability to categorise unseen data.

## 📂 Project Structure
*   `tony_u4_l5_iris.ipynb` - The full Jupyter Notebook containing data loading, visual charts, custom neural network math, and performance evaluations.
  
* **[AI Image Classification Training](https://github.com/anthonymroso-star/ai_iris/tony_u4_l5_iris.ipynb)** - Custom AI model, Deep Learning neural network developed in Python.

## Core Workflow Steps

### 1. Data Exploration & Visualisation
*   **Library Integration:** Imports core data tools like **NumPy** and **Pandas** alongside visualization libraries like Matplotlib and Seaborn.
*   **Visual Analysis:** Loads the standard Iris dataset and generates color-coded distribution graphs to reveal distinct patterns and boundaries between flower categories.

### 2. Data Preparation
*   **Label Formatting:** Automatically transforms text-based category names into organized numerical values.
*   **Data Splitting:** Segregates the flower data into three distinct buckets—**Training (70%)**, **Validation (15%)**, and **Testing (15%)**—ensuring strict separation between teaching and testing phases.

### 3. Custom Neural Network Construction
*   **Scratch-Built Architecture:** Implements a multi-layer brain-inspired network directly using **NumPy matrix operations** rather than pre-made shortcuts.
*   **Forward Tracking:** Flows flower measurements through a 10-neuron hidden layer to calculate target class probabilities.
*   **Error Assessment & Correction:** Uses cross-entropy loss tracking to measure prediction errors, shifting parameters backward step-by-step via custom gradient adjustments to improve accuracy.

### 4. Training, Testing & Analysis
*   **Speed Tuning:** Trains the network across multiple learning speeds to discover the ideal balance between processing pace and system stability.
*   **Live Prediction Inference:** Passes entirely new, isolated flower measurements into the finalized system to instantly categorize the species type.
*   **Performance Diagnostics:** Evaluates the risks of perfect scores (100% accuracy), analyzing potential real-world challenges like memorization bias (overfitting) versus genuine learning.

