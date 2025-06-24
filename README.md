# pest-detection-in-plants


### 🧠 **Project Title: Pest Identification using CNN-based Image Classification**

### ✅ **Objective:**

To design and implement a convolutional neural network (CNN) model capable of accurately identifying and classifying different types of agricultural pests from images, helping in early detection and pest control.

---

### ⚙️ **Tools & Technologies Used:**

* **Python** – For developing and training the model.
* **Google Colab** – For leveraging GPU acceleration and easy experimentation.
* **TensorFlow & Keras** – For building, training, and evaluating the CNN model.
* **OpenCV** – For preprocessing images (resizing, normalization, etc.).

---

### 📦 **Dataset:**

* Sourced from **Kaggle** – A labeled dataset containing thousands of pest images across multiple classes (e.g., aphids, beetles, caterpillars, etc.).
* Data split into **training, validation, and testing** sets to ensure model generalization.

---

### 🧪 **Workflow & Implementation:**

1. **Data Preprocessing**

   * Images resized to a uniform dimension (e.g., 128×128).
   * Applied normalization, augmentation (rotation, zoom, flip), and labeling.

2. **Model Design**

   * Built a custom **CNN architecture** with:

     * Convolutional layers for feature extraction.
     * Max-pooling layers to reduce spatial dimensions.
     * Dropout for regularization.
     * Fully connected layers for classification.

3. **Training**

   * Compiled with categorical cross-entropy loss and Adam optimizer.
   * Trained over multiple epochs with early stopping and model checkpointing.

4. **Evaluation**

   * Achieved improved classification accuracy and reduced validation loss.
   * Evaluated with confusion matrix, precision, recall, and F1-score.

5. **Result Visualization**

   * Plotted training vs. validation accuracy/loss.
   * Visualized predictions with actual vs. predicted labels.

---

### 🎯 **Result:**

* The model achieved **high classification accuracy** on unseen test data.
* Successfully differentiated among multiple pest species, enabling more accurate pest control decisions in agriculture.

---

### 📈 **Applications:**

* Smart farming and automated pest monitoring systems.
* Integration into mobile/web applications for real-time pest diagnosis.
* Enhancing agricultural productivity by reducing crop damage.


