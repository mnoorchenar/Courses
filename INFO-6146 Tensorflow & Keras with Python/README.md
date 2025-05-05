| Week | Title                                                        | Key Topics Covered |
|------|--------------------------------------------------------------|--------------------|
| 1    | 🔍 Deep Learning Fundamentals I                              | Overview of AI, ML, and DL; ML challenges; learning algorithms (supervised, unsupervised, reinforcement); feature engineering limitations; tensors and data representation; optimization (gradient descent); overfitting and regularization |
| 2    | 🔍 Deep Learning Fundamentals II                             | History and key milestones of deep learning; advantages over traditional ML; fundamentals of deep architectures (neurons, layers, activation functions, MLP); introduction to ANNs, CNNs, and RNNs |
| 3    | 🧠 Deep Learning vs. Traditional Machine Learning            | Key differences between traditional ML and DL; decision factors (data size, complexity, compute); advantages of DL (end-to-end learning, scalability, complex data handling); real-world applications (vision, NLP, speech, finance, healthcare, autonomous systems) |
| 4    | ⚙️ Framework Setup and TensorFlow Playground Demo           | Overview of Keras and TensorFlow; interactive demo of ANNs using TensorFlow Playground: learning rate, activation, regularization, architecture depth; installing and configuring TensorFlow and Keras |
| 5    | ⚙️ Deep Learning Environment and Keras API                   | Basics of tensors, operations, and computation graphs; using tf.data and TFDS for efficient data pipelines; Sequential vs. Functional API; compiling, training, evaluating models; setting up training strategies on CPU, GPU, TPU; visualizing with TensorBoard; model serialization; deployment options |
| 6    | 📊 Data Loading, EDA & Preprocessing                         | Extracting data from open sources (Kaggle, UCI, APIs); dataset loading (Keras, TFDS, scikit-learn); exploratory data analysis (NumPy, Pandas, Matplotlib); data transformation, scaling, encoding, and augmentation |
| 7    | 📊 Modeling Pipelines & Transfer Learning                    | Handling imbalanced data; train-test split and cross-validation; building Keras modeling pipelines; hyperparameter tuning with GridSearchCV; supervised models for tabular and image data; transfer learning with pretrained CNNs |
| 8    | 🔧 Supervised Learning with Keras                            | Classification and regression with MLPs using Sequential API; activation functions (ReLU, softmax, sigmoid); loss functions (MSE, cross-entropy); evaluation metrics (accuracy, MSE, RMSE); CNN image classification pipeline; model tuning and visualization with TensorBoard; Sequential vs. Functional API |
| 9    | 🧩 Unsupervised Learning with Autoencoders                   | Clustering, dimensionality reduction, and anomaly detection; difference from supervised learning; vanilla, deep, convolutional, and regularized autoencoders; training for denoising and reconstruction; anomaly detection using AEs and VAEs (ECG dataset) |
| 10   | 🧩 VAEs and Clustering with Neural Networks                  | Variational Autoencoders: probabilistic latent spaces, reparameterization trick, reconstruction + KL loss; feature extraction; clustering with encoder + K-Means/DBSCAN; practical implementation and visualization in Keras |
| 11   | ⏳ Sequence Modeling with HMMs                               | HMM fundamentals: Markov property, hidden states, observable outputs; HMM architecture (transition, emission, initial probabilities); Forward, Backward, Viterbi, Forward-Backward algorithms; supervised vs. unsupervised training (Baum-Welch, EM); model selection (likelihood, AIC, BIC) |
| 12   | 🛠️ HMM Implementation, Inference & Keras Recap              | Implementing HMMs using Python/hmmlearn; simulated weather modeling; inference with Viterbi; evaluating and visualizing HMMs; initialization/convergence issues; summary of Keras APIs (compile, fit, evaluate, predict); model configuration best practices |
| 13   | 🎤 Final Project Presentations                               | Student-led final project presentations |
| 14   | 🧪 Final Exam                                                |theory and practical |


## 🧾 Marking Scheme
| Component         | Weight |
|-------------------|--------|
| In-Class Activity (5 total) | 20%    |
| Quizzes (4 total) | 20%    |
| Final Project     | 30%    |
| Final Exam        | 30%    |

**Quizzes**  
- Quiz #1 (6.67%): Weeks 1–2  
- Quiz #2 (6.67%): Weeks 3–5  
- Quiz #3 (6.67%): Weeks 6–9  

**In-Class Activities**  
- Activity #1 (5%): Based on Weeks 1–4  
- Activity #2 (5%): Based on Weeks 5–7  

**Final Project – 40%**  
Students will design, implement, and present an end-to-end deep learning solution using TensorFlow and Keras. The final deliverables must include:  
- A **written report** that clearly explains the code, architecture choices, and learning strategies  
- Well-documented and functional **source code** answering provided coding questions  
- A **results section** analyzing model performance, evaluation metrics, and key takeaways  
- A brief **presentation** of the project during Week 13  

This course offers a hands-on and applied journey into deep learning using TensorFlow and Keras. Students will build and tune real models, extract and preprocess open data, and implement both supervised and unsupervised learning. The course culminates with advanced sequence modeling using HMMs and a final project demonstrating technical, analytical, and communication skills.