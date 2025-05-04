# ⚙️ Session 3: Optimizers in Practice

Welcome to **Session 3** of the *Applied Machine Learning Optimization* course!  
This session focuses on understanding and experimenting with modern optimizers and learning rate schedules such as **Adam, RMSProp, AdamW**, and **Step/Cosine/1Cycle** schedulers.

---

## 📘 Core Learning Goals

By the end of this session, you should be able to:

- Understand the internal mechanics of Adam, RMSProp, and AdamW
- Tune learning rates effectively using schedulers
- Visualize optimizer performance on different loss surfaces
- Select appropriate optimizers and learning rate policies for real-world problems

---

## 🎯 Interactive Learning Resources

Explore the following interactive tools to deepen your understanding through hands-on experimentation:

### 🔁 [Optimizer Playground – by Louis Dinh](https://louisdinh.com/optimizer-playground/)
Visual comparison of optimizers (SGD, Momentum, RMSProp, Adam) on multiple 2D loss surfaces.  
**Try adjusting** learning rates and momentum values to see how convergence behavior changes.

---

### 📉 [Fast.ai: The 1cycle Policy and Learning Rate Finder](https://sgugger.github.io/the-1cycle-policy.html)
A deep dive into the **1Cycle** learning rate scheduler with visual plots.  
**Explore how** dynamically changing learning rates can outperform static schedules.

---

### 🧪 [Victor Zhou – Optimizer Visualizer](https://victorzhou.com/optimizer-visualizer/)
Simple, clean interactive demo of different optimizers over contour plots.  
**Useful for visually comparing** convergence paths and understanding how adaptive optimizers work.

---

### 💻 [Google Colab – Optimizer Comparison Notebook](https://colab.research.google.com/github/toelt-llc/ADL-Book-2nd-Ed/blob/master/docs/Optimizers/Optimizers_comparison.ipynb)
Run this interactive Colab to test **Adam, RMSProp, and AdamW** on real datasets using Keras.  
**Modify parameters** to see how training behavior changes.

---

## 📚 Supplementary Reading

### 📄 [Sebastian Ruder’s Guide: Optimizing Gradient Descent](https://www.ruder.io/optimizing-gradient-descent/)
A comprehensive visual guide to modern optimizers, including AdamW and practical tuning tips.

---

## 🧠 Bonus Insight

> *"Choosing the right optimizer and scheduler can be the difference between fast convergence and frustrating plateaus. Visualization helps make these invisible dynamics visible."*

---

## 🛠️ In-Class Activity

**Simulate a binary classification task** using synthetic data (e.g., using `make_classification` in scikit-learn or manually constructed tensors).  
Apply multiple optimizers (e.g., SGD, RMSProp, Adam, AdamW) to train the model.  
**Compare and visualize** how each optimizer affects convergence and accuracy.

---

