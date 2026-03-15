# 🧠 AI Concepts Encyclopedia

**110 Essential AI Concepts • 10 Categories • From Fundamentals to Cutting Edge**

---

## Table of Contents

- [🏗️ Foundations (15 concepts)](#-foundations)
- [📊 Machine Learning (20 concepts)](#-machine-learning)
- [🧠 Deep Learning (20 concepts)](#-deep-learning)
- [💬 NLP & Language Models (17 concepts)](#-nlp--language-models)
- [👁️ Computer Vision (8 concepts)](#-computer-vision)
- [🎮 Reinforcement Learning (8 concepts)](#-reinforcement-learning)
- [🎨 Generative AI (8 concepts)](#-generative-ai)
- [⚙️ MLOps & Infrastructure (7 concepts)](#-mlops--infrastructure)
- [🛡️ AI Safety & Ethics (4 concepts)](#-ai-safety--ethics)
- [🔬 Advanced Research (3 concepts)](#-advanced-research)

---

## 🏗️ Foundations
**15 Concepts • Building blocks of AI math and data**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 1 | **Vector** | Beginner | A 1D array of numbers; represents a point in space or a direction |
| 2 | **Matrix** | Beginner | A 2D grid of numbers; used for representing data and transformations |
| 3 | **Tensor** | Beginner | Multi-dimensional array (generalization of vectors and matrices) |
| 4 | **Linear Algebra** | Beginner | Math of vectors, matrices, and operations on them; core to ML |
| 5 | **Dot Product** | Beginner | Scalar result of multiplying two vectors element-wise and summing |
| 6 | **Matrix Multiplication** | Beginner | Core operation in neural networks and transformations |
| 7 | **Eigenvalue & Eigenvector** | Intermediate | Eigenvectors don't change direction under transformation; eigenvalues scale them |
| 8 | **Derivative** | Beginner | Rate of change of a function; critical for optimization |
| 9 | **Partial Derivative** | Beginner | Derivative with respect to one variable, holding others constant |
| 10 | **Gradient** | Beginner | Vector of partial derivatives; points toward steepest ascent |
| 11 | **Chain Rule** | Intermediate | Method to compute derivatives of composite functions |
| 12 | **Optimization** | Beginner | Finding the best (minimum/maximum) of a function |
| 13 | **Convexity** | Intermediate | Property of functions/sets; convex functions have one global minimum |
| 14 | **Probability Distribution** | Beginner | Mathematical function describing likelihood of outcomes |
| 15 | **Bayes' Theorem** | Intermediate | P(A\|B) = P(B\|A)P(A)/P(B); foundation of Bayesian inference |

---

## 📊 Machine Learning
**20 Concepts • Core ML algorithms and techniques**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 16 | **Supervised Learning** | Beginner | Learning from labeled data to predict outputs |
| 17 | **Unsupervised Learning** | Beginner | Finding patterns in unlabeled data |
| 18 | **Classification** | Beginner | Predicting discrete categories (e.g., cat vs. dog) |
| 19 | **Regression** | Beginner | Predicting continuous values (e.g., house price) |
| 20 | **Feature Engineering** | Intermediate | Creating useful features from raw data |
| 21 | **Feature Scaling** | Beginner | Normalizing features to similar ranges (e.g., 0-1) |
| 22 | **Training/Validation/Test Split** | Beginner | Dividing data: train model, tune hyperparams, evaluate |
| 23 | **Cross-Validation** | Intermediate | Technique to evaluate model on multiple data subsets |
| 24 | **Bias-Variance Tradeoff** | Intermediate | Balance between underfitting (bias) and overfitting (variance) |
| 25 | **Overfitting** | Beginner | Model learns training data too well, fails on new data |
| 26 | **Regularization** | Intermediate | Penalizing model complexity to prevent overfitting |
| 27 | **Hyperparameter Tuning** | Intermediate | Finding optimal model settings (not learned during training) |
| 28 | **Decision Tree** | Beginner | Tree-like model making binary splits on features |
| 29 | **Random Forest** | Intermediate | Ensemble of decision trees voting on predictions |
| 30 | **Support Vector Machine (SVM)** | Intermediate | Finds optimal hyperplane to separate classes |
| 31 | **K-Means Clustering** | Beginner | Unsupervised algorithm grouping data into K clusters |
| 32 | **Principal Component Analysis (PCA)** | Intermediate | Reducing dimensionality by finding principal components |
| 33 | **Dimensionality Reduction** | Intermediate | Reducing number of features while preserving information |
| 34 | **Ensemble Methods** | Intermediate | Combining multiple models for better predictions |
| 35 | **Gradient Boosting** | Advanced | Sequentially building models to correct previous errors |

---

## 🧠 Deep Learning
**20 Concepts • Neural networks and modern deep learning**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 36 | **Perceptron** | Beginner | Simple neural network unit; foundation of all neural nets |
| 37 | **Neuron/Unit** | Beginner | Basic building block of neural networks |
| 38 | **Activation Function** | Beginner | Non-linear function applied to neuron outputs (ReLU, Sigmoid, Tanh) |
| 39 | **ReLU (Rectified Linear Unit)** | Beginner | f(x) = max(0, x); most common activation function |
| 40 | **Sigmoid** | Beginner | S-shaped function squashing output to (0,1); used in output layer |
| 41 | **Softmax** | Beginner | Converts outputs to probability distribution over classes |
| 42 | **Tanh (Hyperbolic Tangent)** | Beginner | Squashes output to (-1,1); similar to Sigmoid |
| 43 | **Neural Network Architecture** | Intermediate | Arrangement of layers and neurons |
| 44 | **Forward Pass** | Beginner | Computing output from input through network |
| 45 | **Backward Pass** | Intermediate | Computing gradients through network for learning |
| 46 | **Backpropagation** | Intermediate | Algorithm for computing gradients via chain rule |
| 47 | **Loss Function** | Beginner | Measures difference between predictions and true values |
| 48 | **Cross-Entropy Loss** | Intermediate | Standard loss for classification tasks |
| 49 | **Mean Squared Error (MSE)** | Beginner | Standard loss for regression tasks |
| 50 | **Optimizer** | Intermediate | Algorithm for updating weights (SGD, Adam, etc.) |
| 51 | **Stochastic Gradient Descent (SGD)** | Intermediate | Updating weights using gradient from random batches |
| 52 | **Adam Optimizer** | Intermediate | Adaptive optimizer combining momentum and RMSprop |
| 53 | **Learning Rate** | Beginner | Controls step size when updating weights |
| 54 | **Batch Size** | Beginner | Number of examples processed before weight update |
| 55 | **Epoch** | Beginner | One pass through entire training dataset |

---

## 💬 NLP & Language Models
**17 Concepts • Natural language and language models**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 56 | **Tokenization** | Beginner | Splitting text into tokens (words, subwords, characters) |
| 57 | **Word Embedding** | Intermediate | Vector representation of words capturing semantic meaning |
| 58 | **Word2Vec** | Intermediate | Algorithm creating word embeddings via neural network |
| 59 | **GloVe (Global Vectors)** | Intermediate | Word embedding method combining global statistics and local context |
| 60 | **Attention Mechanism** | Intermediate | Allows model to focus on relevant parts of input |
| 61 | **Self-Attention** | Intermediate | Attention between different positions in same sequence |
| 62 | **Multi-Head Attention** | Intermediate | Multiple attention mechanisms in parallel |
| 63 | **Transformer** | Advanced | Architecture based on attention; foundation of modern LLMs |
| 64 | **BERT** | Intermediate | Bidirectional Encoder Representations from Transformers; pre-trained model |
| 65 | **GPT (Generative Pre-trained Transformer)** | Intermediate | Autoregressive LLM; foundation of ChatGPT, GPT-4 |
| 66 | **Large Language Model (LLM)** | Intermediate | Neural network with billions of parameters trained on text |
| 67 | **In-Context Learning** | Intermediate | LLM learning from examples provided in prompt |
| 68 | **Fine-Tuning** | Intermediate | Training pre-trained model on task-specific data |
| 69 | **Prompt Engineering** | Beginner | Designing prompts to get desired outputs from LLMs |
| 70 | **Chain-of-Thought Prompting** | Intermediate | Asking LLM to reason step-by-step before answering |
| 71 | **Retrieval-Augmented Generation (RAG)** | Intermediate | Retrieving relevant docs and conditioning LLM on them |
| 72 | **LoRA (Low-Rank Adaptation)** | Advanced | Parameter-efficient fine-tuning; update small number of params |

---

## 👁️ Computer Vision
**8 Concepts • Image understanding and generation**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 73 | **Convolution** | Intermediate | Sliding filter over image; core operation in CNNs |
| 74 | **Convolutional Neural Network (CNN)** | Intermediate | Neural network using convolutions; ideal for images |
| 75 | **Pooling** | Beginner | Down-sampling operation reducing spatial dimensions |
| 76 | **Image Classification** | Beginner | Assigning image to category (cat, dog, etc.) |
| 77 | **Object Detection** | Intermediate | Locating and classifying objects in images |
| 78 | **Semantic Segmentation** | Intermediate | Classifying each pixel in image |
| 79 | **Instance Segmentation** | Advanced | Identifying individual object instances in image |
| 80 | **Transfer Learning (Vision)** | Intermediate | Using pre-trained CNN for new vision tasks |

---

## 🎮 Reinforcement Learning
**8 Concepts • Learning through interaction and reward**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 81 | **Agent** | Beginner | Entity interacting with environment and learning from rewards |
| 82 | **Environment** | Beginner | World agent interacts with; provides state and reward |
| 83 | **State** | Beginner | Current configuration of environment |
| 84 | **Action** | Beginner | Something agent can do, changing environment state |
| 85 | **Reward** | Beginner | Numerical signal indicating quality of action |
| 86 | **Markov Decision Process (MDP)** | Intermediate | Mathematical framework for RL problems |
| 87 | **Q-Learning** | Intermediate | Off-policy algorithm learning value of actions |
| 88 | **Policy Gradient** | Intermediate | Algorithm directly optimizing policy (action probabilities) |

---

## 🎨 Generative AI
**8 Concepts • Generating new content**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 89 | **Generative Model** | Intermediate | Model learning to generate new samples from data |
| 90 | **Discriminative Model** | Intermediate | Model learning to distinguish between classes |
| 91 | **Generative Adversarial Network (GAN)** | Advanced | Two networks: generator and discriminator competing |
| 92 | **Variational Autoencoder (VAE)** | Advanced | Generative model learning latent representation |
| 93 | **Autoencoder** | Intermediate | Neural network compressing data and reconstructing it |
| 94 | **Diffusion Model** | Advanced | Generative model learned by reversing noising process |
| 95 | **Latent Space** | Intermediate | Lower-dimensional space where data is represented |
| 96 | **Sampling** | Beginner | Generating new samples from probability distribution |

---

## ⚙️ MLOps & Infrastructure
**7 Concepts • Deploying and maintaining ML systems**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 97 | **Model Serialization** | Beginner | Saving trained model to disk for later use |
| 98 | **Model Serving** | Intermediate | Deploying model as API or service for inference |
| 99 | **Containerization** | Intermediate | Packaging code, dependencies in container (Docker) |
| 100 | **Continuous Integration/Continuous Deployment (CI/CD)** | Intermediate | Automating testing and deployment of code |
| 101 | **Model Monitoring** | Intermediate | Tracking model performance in production |
| 102 | **Data Drift** | Intermediate | When production data distribution changes from training data |
| 103 | **Model Versioning** | Beginner | Tracking versions of trained models |

---

## 🛡️ AI Safety & Ethics
**4 Concepts • Responsible AI**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 104 | **Bias in ML** | Beginner | Systematic errors from prejudiced training data |
| 105 | **Fairness** | Intermediate | Ensuring AI system treats groups equitably |
| 106 | **Interpretability/Explainability** | Intermediate | Understanding why model makes specific predictions |
| 107 | **Alignment** | Advanced | Ensuring AI systems behave according to human values |

---

## 🔬 Advanced Research
**3 Concepts • Cutting edge research directions**

| # | Concept | Difficulty | Description |
|---|---------|-----------|-------------|
| 108 | **Scaling Laws** | Advanced | How model performance improves with size, data, compute |
| 109 | **Emergent Abilities** | Advanced | Capabilities appearing only at large scale (not in smaller models) |
| 110 | **Foundation Model** | Advanced | Large pre-trained model that can be adapted to many tasks |

---

## Statistics by Category

| Category | Count | Level | Focus |
|----------|-------|-------|-------|
| 🏗️ Foundations | 15 | Beginner | Math & fundamentals |
| 📊 Machine Learning | 20 | Beginner-Intermediate | Core algorithms |
| 🧠 Deep Learning | 20 | Beginner-Advanced | Neural networks |
| 💬 NLP & Language Models | 17 | Beginner-Advanced | Language AI |
| 👁️ Computer Vision | 8 | Beginner-Advanced | Visual AI |
| 🎮 Reinforcement Learning | 8 | Intermediate-Advanced | Learning by interaction |
| 🎨 Generative AI | 8 | Intermediate-Advanced | Creating content |
| ⚙️ MLOps | 7 | Beginner-Intermediate | Production ML |
| 🛡️ Safety & Ethics | 4 | Intermediate-Advanced | Responsible AI |
| 🔬 Advanced Research | 3 | Advanced | Cutting edge |
| **TOTAL** | **110** | **All levels** | **Complete coverage** |

---

## How to Use This Encyclopedia

1. **Look up a concept** you encountered in course material or research paper
2. **Understand its definition** and key context
3. **Find it in the Roadmap** to see which topic covers it
4. **Follow the learning path** in the roadmap for deep dive
5. **Implement it** — code, not just theory
6. **Apply it** to your projects

---

## Prerequisites & Dependencies

Concepts build on each other. Suggested learning order:

**Phase 1 Foundation:**
Vector → Matrix → Tensor → Linear Algebra → Derivative → Gradient

**Phase 2 ML Basics:**
Supervised Learning → Classification → Training/Test Split → Overfitting → Regularization

**Phase 3 Deep Learning:**
Perceptron → Neural Network → Activation Functions → Forward/Backward Pass → Backpropagation → Optimizer

**Phase 4 Advanced:**
Attention → Self-Attention → Transformer → BERT/GPT

---

**Master these 110 concepts, and you'll understand AI at a deep level.**

**Start learning. Build projects. Stay curious. Keep growing.** 🚀

