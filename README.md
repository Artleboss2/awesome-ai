# 🧠 Awesome AI Knowledge Base

> A comprehensive, curated repository of Artificial Intelligence knowledge — concepts, algorithms, architectures, tools, papers, repos, datasets, and communities. Built in the spirit of the **Awesome List** tradition.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Lines](https://img.shields.io/badge/lines-8000%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Last Updated](https://img.shields.io/badge/updated-2025-brightgreen)

> **How to use this file:** Read top to bottom or jump to any section via the Table of Contents. The Glossary comes first — familiarize yourself with the terms before diving into the technical sections. Each section is self-contained but cross-referenced throughout.

---

## 📚 Table of Contents

### Meta
- [Legend](#legend)
- [Contributing](#contributing)

### 🔤 Glossary
- [Glossary A–F](#glossary-af)
- [Glossary G–Z](#glossary-gz)

### 🧮 Foundations
- [Mathematics for AI](#mathematics-for-ai)
  - [Linear Algebra](#linear-algebra)
  - [Calculus and Optimization](#calculus-and-optimization)
  - [Probability and Statistics](#probability-and-statistics)
  - [Information Theory](#information-theory)
- [Computational Complexity](#computational-complexity)
- [Logic and Symbolic AI](#logic-and-symbolic-ai)

### 🤖 Machine Learning
- [Core ML Concepts](#core-ml-concepts)
- [Supervised Learning](#supervised-learning)
  - [Linear Models](#linear-models)
  - [Decision Trees and Ensembles](#decision-trees-and-ensembles)
  - [Support Vector Machines](#support-vector-machines)
  - [k-Nearest Neighbors](#k-nearest-neighbors)
  - [Naive Bayes](#naive-bayes)
- [Unsupervised Learning](#unsupervised-learning)
  - [Clustering](#clustering)
  - [Dimensionality Reduction](#dimensionality-reduction)
  - [Density Estimation](#density-estimation)
- [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- [Reinforcement Learning Overview](#reinforcement-learning-overview)
- [Evaluation and Metrics](#evaluation-and-metrics)
- [Bias, Variance, and Regularization](#bias-variance-and-regularization)
- [Feature Engineering](#feature-engineering)

### 🧬 Deep Learning
- [Neural Network Fundamentals](#neural-network-fundamentals)
- [Activation Functions](#activation-functions)
- [Loss Functions](#loss-functions)
- [Optimizers](#optimizers)
- [Convolutional Neural Networks](#convolutional-neural-networks)
- [Recurrent Neural Networks](#recurrent-neural-networks)
- [Attention and Transformers](#attention-and-transformers)
- [Graph Neural Networks](#graph-neural-networks)
- [Generative Adversarial Networks](#generative-adversarial-networks)
- [Variational Autoencoders](#variational-autoencoders)
- [Diffusion Models](#diffusion-models)
- [Normalizing Flows](#normalizing-flows)
- [Neural Architecture Search](#neural-architecture-search)
- [Hyperparameter Tuning](#hyperparameter-tuning)

### 💬 NLP and Large Language Models
- [NLP Fundamentals](#nlp-fundamentals)
- [Tokenization](#tokenization)
- [Word Embeddings](#word-embeddings)
- [Language Model Architectures](#language-model-architectures)
- [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- [Prompt Engineering](#prompt-engineering)
- [RLHF and Alignment](#rlhf-and-alignment)
- [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- [Agents and Tool Use](#agents-and-tool-use)
- [Notable LLMs and Repos](#notable-llms-and-repos)

### 👁️ Computer Vision
- [CV Fundamentals](#cv-fundamentals)
- [Image Classification](#image-classification)
- [Object Detection](#object-detection)
- [Image Segmentation](#image-segmentation)
- [Image Generation and Editing](#image-generation-and-editing)
- [Video Understanding](#video-understanding)
- [3D Vision and NeRF](#3d-vision-and-nerf)

### 🎮 Deep Reinforcement Learning
- [RL Fundamentals](#rl-fundamentals)
- [Model-Free RL](#model-free-rl)
- [Model-Based RL](#model-based-rl)
- [Multi-Agent RL](#multi-agent-rl)
- [RL from Human Feedback](#rl-from-human-feedback)
- [Notable RL Environments and Repos](#notable-rl-environments-and-repos)

### 🔀 Multimodal AI
- [Vision-Language Models](#vision-language-models)
- [Audio and Speech AI](#audio-and-speech-ai)
- [Multimodal Architectures](#multimodal-architectures)

### ⚙️ MLOps and Production AI
- [MLOps Concepts](#mlops-concepts)
- [Experiment Tracking](#experiment-tracking)
- [Model Serving and Deployment](#model-serving-and-deployment)
- [Monitoring and Observability](#monitoring-and-observability)
- [Data Versioning and Pipelines](#data-versioning-and-pipelines)
- [Distributed Training](#distributed-training)

### 🛠️ Frameworks and Libraries
- [Core Frameworks](#core-frameworks)
- [NLP Libraries](#nlp-libraries)
- [CV Libraries](#cv-libraries)
- [RL Libraries](#rl-libraries)
- [Data Processing](#data-processing)
- [Visualization Tools](#visualization-tools)
- [AutoML Tools](#automl-tools)
- [Vector Databases](#vector-databases)

### 📄 Landmark Papers
- [Pre-2015 Classics](#pre-2015-classics)
- [2015–2018 Breakthroughs](#20152018-breakthroughs)
- [2019–2021 Scaling Era](#20192021-scaling-era)
- [2022–2025 Modern Era](#20222025-modern-era)

### 📦 Datasets
- [Image Datasets](#image-datasets)
- [NLP Datasets](#nlp-datasets)
- [Multimodal Datasets](#multimodal-datasets)
- [RL Environments](#rl-environments)
- [Benchmarks](#benchmarks)

### 🌐 Communities and Resources
- [Online Communities](#online-communities)
- [Courses and Tutorials](#courses-and-tutorials)
- [Blogs and Newsletters](#blogs-and-newsletters)
- [Conferences and Journals](#conferences-and-journals)
- [Research Labs and Organizations](#research-labs-and-organizations)

### ⚖️ AI Ethics and Safety
- [Fairness and Bias](#fairness-and-bias)
- [Interpretability and Explainability](#interpretability-and-explainability)
- [AI Safety Research](#ai-safety-research)
- [Privacy-Preserving ML](#privacy-preserving-ml)
- [Governance and Policy](#governance-and-policy)

### 🗂️ Index
- [Full Alphabetical Index](#full-alphabetical-index)

---

## Legend

| Symbol | Meaning |
|--------|---------|
| 📄 | Research paper |
| 🐙 | GitHub repository |
| 🎓 | Educational resource / course |
| 📺 | Video / lecture |
| 📰 | Blog post / article |
| 🌐 | Website / tool |
| ⭐ | Highly recommended starting point |
| 🔥 | Trending / state-of-the-art |
| 💡 | Key concept / insight |
| ⚠️ | Common pitfall / warning |
| 🧪 | Experimental / research-stage |

---

## Contributing

This document follows the Awesome List format. To suggest additions:
1. Open a GitHub issue with the tag `[knowledge]`
2. Provide: name, link, category, and a one-line description
3. Prefer primary sources (papers, official repos) over secondary aggregators
4. No self-promotion without disclosure

---

---

# 🔤 Glossary A–F

> Definitions are concise and practical. For deep dives, follow the cross-references to the relevant sections.

---

## A

**Ablation Study**
An experiment where components of a model or system are systematically removed or disabled to measure their individual contribution to overall performance. Standard practice in deep learning research to justify architectural choices.

**Accuracy**
The fraction of correct predictions out of total predictions. Formula: `(TP + TN) / (TP + TN + FP + FN)`. Misleading when class distribution is heavily imbalanced — prefer F1, AUC-ROC, or Matthews Correlation Coefficient in such cases.

**Action Space**
In reinforcement learning, the set of all possible actions an agent can take in an environment. Can be **discrete** (e.g., {left, right, jump}) or **continuous** (e.g., a torque value in robotics).

**Activation Function**
A non-linear function applied element-wise to the output of a neuron. Without activation functions, stacking layers would be equivalent to a single linear transformation. Common examples: ReLU, GELU, Sigmoid, Tanh, Swish. → See [Activation Functions](#activation-functions)

**Actor-Critic**
A reinforcement learning framework that combines two components: an **actor** (policy network that selects actions) and a **critic** (value network that evaluates how good the current state is). Reduces variance of policy gradient estimates. Foundation of PPO, SAC, and A3C.

**Adversarial Attack**
An intentional perturbation of input data — often imperceptible to humans — designed to cause a model to make incorrect predictions. Examples: FGSM (Fast Gradient Sign Method), PGD (Projected Gradient Descent). Highlights brittleness of neural networks.

**Adversarial Training**
A defense strategy against adversarial attacks where a model is trained on adversarial examples in addition to clean data. Improves robustness but often at the cost of standard accuracy (accuracy-robustness trade-off).

**Agent**
In RL: an entity that perceives its environment, makes decisions, and takes actions to maximize cumulative reward. In LLM contexts: an AI system that can use tools, call APIs, browse the web, write and execute code, and complete multi-step tasks autonomously. → See [Agents and Tool Use](#agents-and-tool-use)

**Aggregation (in GNNs)**
The process by which a node in a Graph Neural Network collects and combines information from its neighboring nodes. Common aggregation methods: sum, mean, max, attention-weighted. → See [Graph Neural Networks](#graph-neural-networks)

**AI Winter**
Periods of reduced funding and interest in AI research following inflated expectations. Two major winters: ~1974–1980 and ~1987–1993. The current period (2010s–present) has so far avoided a third winter due to practical results from deep learning.

**Alignment**
The problem of ensuring AI systems behave in accordance with human values, intentions, and goals — especially as systems become more capable. Encompasses RLHF, Constitutional AI, interpretability research, and formal specification of objectives. → See [RLHF and Alignment](#rlhf-and-alignment)

**Aleatoric Uncertainty**
Uncertainty that comes from inherent randomness or noise in data — it cannot be reduced by collecting more data. Contrasted with **epistemic uncertainty** (model uncertainty), which can be reduced with more data or better models.

**Attention Mechanism**
A neural network module that learns to dynamically weight different parts of an input sequence when generating each output element. Originally proposed for machine translation (Bahdanau, 2015). The foundation of Transformers. → See [Attention and Transformers](#attention-and-transformers)

**Autoencoder**
An unsupervised neural network architecture consisting of an encoder (compresses input to a latent representation) and a decoder (reconstructs the input from the latent representation). Variants: Denoising AE, Sparse AE, Variational AE (VAE).

**Autoregressive Model**
A model that generates output one token (or step) at a time, conditioning each new token on all previously generated tokens. GPT-style models are autoregressive. Contrasted with masked models (BERT) and diffusion models.

**AutoML**
Automated Machine Learning — the use of algorithms to automate the end-to-end process of building ML models, including feature engineering, model selection, and hyperparameter optimization. Tools: AutoKeras, H2O AutoML, Google AutoML, TPOT, AutoGluon.

---

## B

**Backpropagation**
The algorithm used to compute gradients of the loss function with respect to model parameters. Uses the chain rule of calculus applied backwards through the computational graph. Proposed by Rumelhart, Hinton & Williams (1986). The workhorse of all gradient-based neural network training.

**Batch Normalization (BatchNorm)**
A technique that normalizes the inputs to each layer using the mean and variance computed over the current mini-batch. Proposed by Ioffe & Szegedy (2015). Stabilizes training, allows higher learning rates, and acts as regularization. Less effective with very small batch sizes — prefer LayerNorm for Transformers.

**Batch Size**
The number of training examples used to compute one gradient update. Large batches: more stable gradients, better hardware utilization, but may generalize worse. Small batches: noisier gradients (acts as implicit regularization), better generalization in many settings.

**Bayesian Inference**
A statistical framework for updating beliefs (probability distributions over parameters) in light of new evidence, using Bayes' theorem: `P(θ|data) ∝ P(data|θ) × P(θ)`. Applied in ML as Bayesian Neural Networks, Gaussian Processes, and Bayesian Optimization.

**Bayesian Optimization**
A strategy for black-box function optimization that builds a probabilistic surrogate model (typically a Gaussian Process) of the objective function and uses an acquisition function (e.g., Expected Improvement) to decide where to evaluate next. Highly effective for hyperparameter tuning.

**BERT (Bidirectional Encoder Representations from Transformers)**
A landmark NLP model by Google (Devlin et al., 2018) pre-trained using Masked Language Modeling (MLM) and Next Sentence Prediction (NSP). Bidirectional — reads context from both left and right simultaneously. Fine-tuned for downstream tasks. 📄 [Paper](https://arxiv.org/abs/1810.04805) 🐙 [Repo](https://github.com/google-research/bert)

**Bias (in ML models)**
Has two meanings: (1) **Statistical bias**: the error introduced by approximating a real-world problem with a simplified model — a high-bias model underfits. (2) **Societal bias**: systematic unfairness encoded in training data or model outputs that discriminates against certain groups.

**Bias-Variance Tradeoff**
The fundamental tension in ML: models with high bias underfit (too simple), models with high variance overfit (too complex, sensitive to training data). Optimal model minimizes total error = Bias² + Variance + Irreducible Noise. → See [Bias, Variance, and Regularization](#bias-variance-and-regularization)

**Bootstrapping**
A statistical resampling technique where datasets are created by sampling with replacement from the original dataset. Used in ensemble methods (e.g., Bagging/Random Forests) and for estimating confidence intervals.

**Bounding Box**
In computer vision, a rectangle defined by coordinates (x_min, y_min, x_max, y_max) or (center_x, center_y, width, height) used to localize objects in images. The standard annotation format for object detection tasks.

**Byte Pair Encoding (BPE)**
A subword tokenization algorithm originally from data compression. Iteratively merges the most frequent pairs of characters/subwords to build a vocabulary. Used by GPT-2, GPT-3, RoBERTa, and many others. Handles rare and out-of-vocabulary words gracefully. → See [Tokenization](#tokenization)

---

## C

**Catastrophic Forgetting**
The tendency of neural networks to abruptly lose previously learned information when trained on new tasks. A central challenge in continual/lifelong learning. Mitigations: Elastic Weight Consolidation (EWC), progressive networks, experience replay.

**Chain-of-Thought (CoT)**
A prompting technique where the model is instructed (or learns) to produce step-by-step reasoning before arriving at a final answer. Significantly improves performance on math, logic, and multi-step tasks. Introduced by Wei et al. (2022). 📄 [Paper](https://arxiv.org/abs/2201.11903)

**Checkpoint**
A saved snapshot of model weights (and optionally optimizer state) at a specific point during training. Used for fault tolerance, resuming training, and selecting the best model from a training run.

**Classification**
A supervised learning task where the goal is to assign an input to one of a finite set of categories (classes). Binary (2 classes) or multiclass (>2 classes). Algorithms: logistic regression, SVM, decision trees, neural networks.

**CLIP (Contrastive Language-Image Pretraining)**
A model by OpenAI (Radford et al., 2021) trained on 400 million image-text pairs using contrastive learning. Learns a shared embedding space for images and text. Enables zero-shot image classification and is widely used in vision-language models. 📄 [Paper](https://arxiv.org/abs/2103.00020) 🐙 [Repo](https://github.com/openai/CLIP)

**Clustering**
An unsupervised learning task that groups data points such that points within a cluster are more similar to each other than to points in other clusters. Algorithms: K-Means, DBSCAN, Hierarchical Clustering, Gaussian Mixture Models. → See [Clustering](#clustering)

**Confusion Matrix**
A table used to evaluate classification models showing true positives (TP), true negatives (TN), false positives (FP), and false negatives (FN) for each class. Foundation for computing accuracy, precision, recall, F1, and other metrics.

**Constitutional AI (CAI)**
An alignment technique by Anthropic where a model is trained to follow a set of principles (a "constitution") using self-critique and revision. Reduces reliance on human labelers for harmful content filtering. 📄 [Paper](https://arxiv.org/abs/2212.08073)

**Context Length / Context Window**
The maximum number of tokens a model can process in a single forward pass — effectively its "working memory." GPT-2: 1024 tokens. GPT-4: 128k tokens. Claude 3: 200k tokens. Extending context length is an active research area.

**Contrastive Learning**
A self-supervised learning approach that trains a model to bring representations of similar examples closer together and push dissimilar examples apart in embedding space. Key methods: SimCLR, MoCo, BYOL, CLIP. → See [Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)

**Convolutional Neural Network (CNN)**
A neural architecture designed for grid-like data (images, time-series). Uses convolutional filters that share weights across spatial positions, enabling translation equivariance and reducing the number of parameters vs. fully connected networks. → See [Convolutional Neural Networks](#convolutional-neural-networks)

**Cosine Similarity**
A measure of similarity between two vectors: `cos(θ) = (A·B) / (||A|| × ||B||)`. Range: [-1, 1]. Value of 1 = identical direction, 0 = orthogonal, -1 = opposite. Widely used for comparing embeddings in NLP and retrieval systems.

**Cross-Entropy Loss**
The most common loss function for classification. Measures the difference between the predicted probability distribution and the true distribution. For binary classification: `-[y·log(p) + (1-y)·log(1-p)]`. For multiclass: `-Σ y_i·log(p_i)`. Directly minimizing cross-entropy maximizes log-likelihood.

**Cross-Validation**
A model evaluation technique that partitions data into k folds, trains on k-1 folds, and validates on the remaining fold, repeating k times. **k-fold CV** gives a robust estimate of generalization performance. **Leave-one-out CV** is the extreme case (k = n).

**Curriculum Learning**
A training strategy where examples are presented in a meaningful order, typically from easy to hard, mimicking how humans learn. Bengio et al. (2009) showed this can speed up training and improve generalization.

---

## D

**Data Augmentation**
Artificially expanding a training dataset by applying transformations to existing examples (e.g., flipping, rotating, cropping images; back-translation for text). Improves generalization and robustness by exposing the model to more variation.

**Data Leakage**
A subtle but catastrophic problem where information from the test set inadvertently influences model training or selection, leading to overly optimistic evaluation metrics. Common causes: normalization with global statistics, time-series splits done incorrectly, features that contain future information.

**Data Parallelism**
A distributed training strategy where the same model is replicated on multiple devices and each device processes a different mini-batch. Gradients are averaged across devices. Contrasted with **model parallelism** (splitting the model itself across devices).

**Decision Boundary**
The hypersurface in feature space that separates different predicted classes. Linear classifiers produce linear boundaries; neural networks can produce arbitrarily complex boundaries.

**Decision Tree**
A supervised learning model that splits data recursively based on feature values, creating a tree where leaves represent class labels or regression values. Highly interpretable but prone to overfitting. Building block of Random Forests and Gradient Boosting. → See [Decision Trees and Ensembles](#decision-trees-and-ensembles)

**Deep Learning**
A subfield of machine learning using neural networks with many layers (deep architectures) to learn hierarchical representations from data. Responsible for breakthroughs in image recognition (AlexNet, 2012), NLP (Transformers, 2017), and generative AI (diffusion models, LLMs).

**Denoising**
The task of recovering clean data from corrupted or noisy observations. Denoising Autoencoders learn robust representations by reconstructing clean inputs from noisy versions. The denoising objective is also foundational to diffusion models.

**Dense Retrieval**
A retrieval paradigm where both queries and documents are encoded as dense vectors (embeddings), and retrieval is performed by approximate nearest neighbor search in vector space. Contrasted with sparse retrieval (BM25, TF-IDF). Key model: DPR (Dense Passage Retrieval). → See [Retrieval-Augmented Generation](#retrieval-augmented-generation)

**Depthwise Separable Convolution**
A factorized form of convolution used in MobileNet and Xception that applies a spatial convolution independently for each input channel, then mixes channels with a 1×1 convolution. Dramatically reduces computation vs. standard convolutions with minimal accuracy loss.

**Differentiable Programming**
A paradigm where entire programs (not just neural networks) are made differentiable end-to-end, allowing gradient-based optimization. PyTorch and JAX enable this. Connects ML to classical algorithms and scientific computing.

**Diffusion Model**
A generative model that learns to denoise data across a series of steps. Training: add noise to data progressively; inference: start from pure noise and denoise step-by-step. Powers DALL-E 2, Stable Diffusion, Imagen. → See [Diffusion Models](#diffusion-models)

**Dimensionality Reduction**
The process of reducing the number of input features while preserving important structure. Methods: PCA (linear), t-SNE and UMAP (non-linear, good for visualization), autoencoders (learned, non-linear). → See [Dimensionality Reduction](#dimensionality-reduction)

**Disentangled Representation**
A learned representation where different dimensions correspond to independent generative factors of the data (e.g., object position, color, shape as separate dimensions). Goal of disentangled VAEs (β-VAE). Useful for controllable generation and robustness.

**Distillation (Knowledge Distillation)**
Training a small "student" model to mimic the outputs (soft logits) of a larger "teacher" model. Proposed by Hinton et al. (2015). The student learns from the teacher's probability distributions, which contain richer information than hard labels. Used to create efficient models (DistilBERT, TinyBERT).

**Dropout**
A regularization technique (Srivastava et al., 2014) that randomly sets a fraction p of neurons to zero during each training forward pass. At test time, all neurons are active but outputs are scaled by (1-p). Prevents co-adaptation of neurons and acts as an ensemble of many sub-networks.

**Dynamic Computation Graph**
A computational graph built anew on each forward pass (as in PyTorch). Contrasted with static graphs (TensorFlow 1.x). Enables conditional computation, variable-length sequences, and easier debugging.

---

## E

**Early Stopping**
A regularization technique where training is halted when validation loss stops improving. Prevents overfitting by avoiding training to convergence on the training set. Requires a separate validation set monitored throughout training.

**Embedding**
A dense, low-dimensional vector representation of discrete objects (words, items, nodes, etc.) in a continuous vector space. Learned such that similar objects have similar vectors. Foundation of word2vec, GloVe, and the first layer of most NLP models. → See [Word Embeddings](#word-embeddings)

**Encoder-Decoder**
An architecture with two main parts: an encoder that maps input to a latent representation, and a decoder that generates output from that representation. Used in seq2seq models, image segmentation (U-Net), and translation. Transformers use encoder-decoder for translation but decoder-only for language modeling.

**Ensemble Method**
Combining multiple models to produce predictions that are better than any individual model. Types: **Bagging** (train models on bootstrap samples, average — e.g., Random Forest), **Boosting** (train models sequentially, each focusing on previous errors — e.g., XGBoost), **Stacking** (train a meta-model on base model outputs).

**Entropy**
From information theory: a measure of uncertainty or randomness in a probability distribution. `H(X) = -Σ p(x)·log p(x)`. High entropy = high uncertainty (uniform distribution). Zero entropy = certainty (deterministic outcome). Used in decision trees (information gain) and loss functions (cross-entropy).

**Environment (RL)**
In reinforcement learning, the world in which an agent operates. Provides observations, accepts actions, and returns rewards. Defined by a state space, action space, transition dynamics, and reward function. Examples: OpenAI Gym, Atari, MuJoCo, StarCraft II.

**Epoch**
One complete pass through the entire training dataset. Training typically runs for multiple epochs. The number of epochs is a hyperparameter — too few: underfitting; too many: overfitting (without regularization or early stopping).

**Epistemic Uncertainty**
Model uncertainty arising from lack of knowledge — can be reduced by collecting more data or using better models. Contrasted with aleatoric uncertainty (irreducible noise). Bayesian methods attempt to quantify epistemic uncertainty through posterior distributions over parameters.

**Equivariance**
A property of a function where transforming the input produces a corresponding transformation of the output. CNNs are translation-equivariant (shifting an image shifts the feature map). Equivariance is exploited in geometric deep learning and molecular modeling.

**Ethics in AI**
The study of moral questions arising from AI systems: fairness, accountability, transparency, privacy, job displacement, dual use, autonomy, and existential risk. → See [AI Ethics and Safety](#ai-ethics-and-safety)

**Expectation-Maximization (EM)**
An iterative algorithm for maximum likelihood estimation with latent variables. E-step: compute expected log-likelihood given current parameters. M-step: maximize expected log-likelihood to update parameters. Used in Gaussian Mixture Models (GMM) and HMMs.

**Explainability**
The ability to describe why a model made a particular prediction in human-understandable terms. Distinct from interpretability (understanding the model's internal mechanics). Methods: LIME, SHAP, attention visualization. → See [Interpretability and Explainability](#interpretability-and-explainability)

**Exponential Moving Average (EMA)**
A weighted average of past values where recent values are weighted more. In DL: used for stable evaluation copies of model weights (e.g., in DDPM, EMA teacher in BYOL). Formula: `EMA_t = α × value_t + (1-α) × EMA_{t-1}`.

---

## F

**F1 Score**
The harmonic mean of precision and recall: `F1 = 2 × (Precision × Recall) / (Precision + Recall)`. Balanced metric that penalizes extreme imbalances between precision and recall. **Macro F1**: average F1 per class. **Micro F1**: aggregate TP/FP/FN across all classes.

**Feature**
An individual measurable property or characteristic of the data used as input to a model. Can be raw (pixel values, raw text) or engineered (TF-IDF scores, moving averages, domain-specific statistics). Feature quality is often the dominant factor in ML system performance.

**Feature Engineering**
The process of using domain knowledge to create, transform, or select features from raw data to improve model performance. Often more impactful than model selection in traditional ML. In deep learning, feature learning is partially automated through representation learning.

**Feature Importance**
A measure of how much each feature contributes to model predictions. Methods: permutation importance (model-agnostic), SHAP values (additive attribution), impurity-based importance (tree-based models). Critical for model debugging and understanding.

**Feature Map**
In CNNs, the output tensor produced by applying a convolutional filter to an input. Each filter produces one feature map. The depth of the feature map stack equals the number of filters. Earlier layers: low-level features (edges, colors); deeper layers: high-level semantic features.

**Few-Shot Learning**
Learning to generalize from very few labeled examples per class (typically 1–5). Approaches: metric learning (Prototypical Networks, Matching Networks), model-agnostic meta-learning (MAML), and prompting LLMs with examples. → See [Prompt Engineering](#prompt-engineering)

**Fine-Tuning**
Adapting a pre-trained model to a specific downstream task by continuing training on task-specific data (usually with a smaller learning rate). Transfers knowledge from large pre-training corpora to specialized tasks with minimal data. → See [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)

**Focal Loss**
A modified cross-entropy loss (Lin et al., 2017, RetinaNet) that down-weights the loss from easy, well-classified examples and focuses training on hard examples. Addresses extreme class imbalance in object detection. `FL(p_t) = -α_t × (1 - p_t)^γ × log(p_t)`.

**Forward Pass**
The computation of a neural network's output given an input, by propagating data through each layer sequentially. Contrasted with the **backward pass** (backpropagation), which computes gradients. During inference, only the forward pass is performed.

**Foundation Model**
A large model pre-trained on broad data at scale, designed to be adapted (fine-tuned, prompted) to a wide range of downstream tasks. Term coined by Bommasani et al. (2021) at Stanford. Examples: GPT-4, Claude, Gemini, DALL-E, CLIP, Stable Diffusion.

**Frozen Layers**
Layers of a neural network whose weights are not updated during training. Common practice in fine-tuning: freeze early layers (general features) and only train later layers (task-specific features). Reduces computation and prevents catastrophic forgetting.

**Function Approximation**
The use of parameterized functions (e.g., neural networks) to approximate complex, unknown functions — such as the value function or policy in RL, or the input-output mapping in supervised learning.

## G

**Gaussian Process (GP)**
A non-parametric probabilistic model that defines a distribution over functions. Fully specified by a mean function and a covariance (kernel) function. Used in Bayesian optimization, regression with uncertainty estimates, and spatial modeling. Computationally expensive: O(n³) for exact inference.

**Generalization**
A model's ability to perform well on unseen data not present during training. The central goal of machine learning. Poor generalization = overfitting. Measured via a held-out test set. Influenced by model capacity, training data size, regularization, and data distribution shift.

**Generative Adversarial Network (GAN)**
An architecture (Goodfellow et al., 2014) where a generator network creates fake samples and a discriminator network tries to distinguish real from fake. Trained via minimax game. → See [Generative Adversarial Networks](#generative-adversarial-networks) 📄 [Paper](https://arxiv.org/abs/1406.2661)

**Generative Model**
A model that learns the underlying distribution of training data and can sample new data points. Examples: GANs, VAEs, diffusion models, autoregressive LLMs, normalizing flows. Contrasted with discriminative models.

**GELU (Gaussian Error Linear Unit)**
Activation: `GELU(x) = x × Φ(x)`. Smooth, non-monotonic near zero. Used in BERT, GPT, and most modern Transformers. Generally outperforms ReLU on NLP tasks.

**Gradient**
A vector of partial derivatives of a scalar function w.r.t. all its inputs. In ML: gradient of the loss w.r.t. model parameters. Points in the direction of steepest ascent. Gradient descent moves opposite the gradient to minimize loss.

**Gradient Checkpointing**
A memory-saving technique that trades compute for memory: intermediate activations are discarded during the forward pass and recomputed during backpropagation. Allows training larger models on limited GPU memory at ~33% extra compute cost.

**Gradient Clipping**
Capping the norm or value of gradients before applying an optimizer update. Prevents exploding gradients in RNNs and Transformers. Common threshold: clip gradient norm to 1.0.

**Gradient Descent**
An iterative optimization algorithm: `θ ← θ - η × ∇_θ L(θ)`. Variants: **Batch GD** (all data), **Stochastic GD** (one sample), **Mini-batch GD** (subset). Foundation of all neural network training. → See [Optimizers](#optimizers)

**Graph Neural Network (GNN)**
A neural network operating on graph-structured data. Learns node/edge/graph representations via message passing between neighbors. Applications: molecular property prediction, social network analysis, knowledge graphs, recommender systems. → See [Graph Neural Networks](#graph-neural-networks)

**Ground Truth**
The true label or target value for a training or evaluation example. In supervised learning, ground truth annotations come from human labelers, sensors, or known physical processes. Model predictions are compared against ground truth to compute loss and metrics.

**GroupNorm (Group Normalization)**
Normalizes within groups of channels rather than across the batch dimension. Proposed by Wu & He (2018). Performs well at small batch sizes where BatchNorm degrades. Widely used in object detection and segmentation. 📄 [Paper](https://arxiv.org/abs/1803.08494)

---

## H

**Hallucination**
When a language model generates text that is fluent and confident but factually incorrect, fabricated, or unsupported by its context. A critical failure mode of LLMs. Caused by distribution shifts between pre-training and inference, lack of grounding, and autoregressive error accumulation.

**Hard Negative Mining**
A training strategy that specifically selects difficult negative examples (ones the model currently confuses with positives) rather than random negatives. Dramatically improves the quality of learned embeddings in metric learning and contrastive learning.

**Head (in Neural Networks)**
A task-specific module attached to a backbone/encoder. For example, a classification head is a linear layer on top of a pre-trained Transformer. Multiple heads can be attached to the same backbone for multi-task learning.

**Heuristic**
A rule of thumb or practical strategy used to solve problems efficiently when an optimal solution is computationally infeasible. In AI: used in search algorithms (A* heuristic), feature engineering, and architecture design.

**Hidden Layer**
Any layer in a neural network between the input layer and the output layer. Learns intermediate representations. The depth (number of hidden layers) and width (neurons per layer) determine the network's capacity.

**Hidden State**
In RNNs: the vector that summarizes the network's memory of all previous inputs in the sequence. Passed from one time step to the next. In Transformers: the representation of each token after processing through attention and feed-forward layers.

**Hierarchical Learning**
Learning representations at multiple levels of abstraction, with higher levels building on lower levels. CNNs naturally do this: pixels → edges → textures → parts → objects. Transformers learn hierarchical representations across layers.

**Hyperparameter**
A parameter that controls the training process rather than being learned from data. Examples: learning rate, batch size, number of layers, dropout rate, weight decay. Must be tuned separately via search or domain knowledge. → See [Hyperparameter Tuning](#hyperparameter-tuning)

**Hyperparameter Optimization (HPO)**
The process of finding the hyperparameter configuration that maximizes validation performance. Methods: grid search, random search, Bayesian optimization, evolutionary algorithms, Hyperband. Tools: Optuna, Ray Tune, W&B Sweeps.

---

## I

**Imbalanced Dataset**
A dataset where some classes have significantly more examples than others. Can cause models to be biased toward the majority class. Solutions: oversampling (SMOTE), undersampling, class-weighted loss, focal loss, and collecting more minority class data.

**In-Context Learning (ICL)**
The ability of large language models to perform new tasks by conditioning on examples provided directly in the prompt (few-shot) or instructions alone (zero-shot), without any gradient updates. Emergent property of large-scale pre-training. → See [Prompt Engineering](#prompt-engineering)

**Inference**
The process of using a trained model to make predictions on new data. Contrasted with training. Inference optimization is critical for production deployment: quantization, pruning, batching, caching, hardware acceleration (TensorRT, ONNX Runtime).

**Instance Normalization**
Normalizes each sample independently across spatial dimensions but separately per channel. Used in style transfer (Ulyanov et al., 2016) because it removes instance-specific contrast information while preserving style-relevant statistics.

**Invariance**
A property where a function's output does not change under certain input transformations. CNNs are approximately translation-invariant (pooling). Invariance is often desired in classification (a cat is a cat regardless of position). Contrasted with equivariance.

**IoU (Intersection over Union)**
A metric measuring overlap between two regions: `IoU = |A ∩ B| / |A ∪ B|`. Standard metric for object detection and segmentation. A prediction is typically considered correct if IoU > 0.5. Used in non-maximum suppression (NMS).

---

## J

**Jacobian**
A matrix of all first-order partial derivatives of a vector-valued function. For a function f: ℝⁿ → ℝᵐ, the Jacobian is m×n. Used in backpropagation, generative model training (change-of-variables formula in normalizing flows), and robustness analysis.

**JAX**
A Python library by Google for high-performance numerical computing with composable function transformations: `grad` (automatic differentiation), `jit` (JIT compilation via XLA), `vmap` (vectorization), `pmap` (parallelization). Increasingly popular for research. 🐙 [Repo](https://github.com/google/jax)

---

## K

**Kernel (in SVMs and GPs)**
A function k(x, x') that computes the similarity between two inputs in an implicit, potentially infinite-dimensional feature space without explicitly computing the features. Examples: RBF (Gaussian), polynomial, Matérn. The "kernel trick" enables SVMs to find non-linear decision boundaries.

**Kernel (in CNNs)**
A small learnable filter (e.g., 3×3 or 5×5) that slides over the input and computes dot products at each position, producing a feature map. Each kernel detects a specific pattern (edge, curve, etc.).

**KL Divergence (Kullback-Leibler)**
A measure of how one probability distribution P differs from a reference distribution Q: `KL(P||Q) = Σ P(x) log(P(x)/Q(x))`. Not symmetric. Used in VAE loss, knowledge distillation, and RL policy optimization (PPO uses KL as a penalty).

**Knowledge Distillation**
→ See [Distillation](#distillation-knowledge-distillation)

**Knowledge Graph**
A structured representation of entities and their relationships as a directed graph. Used in question answering, recommendation, and as external memory for LLMs. Examples: Wikidata, Freebase, ConceptNet. GNNs are often used to reason over knowledge graphs.

**K-Means Clustering**
An iterative clustering algorithm that partitions n points into k clusters by alternating between assigning points to the nearest centroid and recomputing centroids. Simple, fast, but sensitive to initialization and assumes spherical clusters. → See [Clustering](#clustering)

---

## L

**L1 Regularization (Lasso)**
Adds `λ × Σ|w_i|` to the loss. Induces sparsity — drives some weights exactly to zero — acting as feature selection. Useful when you believe many features are irrelevant.

**L2 Regularization (Ridge / Weight Decay)**
Adds `λ × Σw_i²` to the loss. Penalizes large weights, shrinks them toward zero but rarely to exactly zero. Improves generalization. In neural networks, commonly called weight decay and implemented directly in the optimizer.

**Label Smoothing**
A regularization technique that replaces hard one-hot labels (0 or 1) with soft targets (e.g., 0.1 / (K-1) for wrong classes, 1 - 0.1 for the correct class). Prevents the model from becoming overconfident and improves calibration.

**Latent Space**
The compressed, low-dimensional representation space learned by an encoder (in autoencoders, VAEs) or the hidden space of a generative model. Points in latent space correspond to data points; nearby points should correspond to semantically similar data.

**Layer Normalization (LayerNorm)**
Normalizes across the feature dimension for each individual sample: computes mean and variance over all features of a single token/sample. Proposed by Ba et al. (2016). Standard in Transformers. Does not depend on batch size, unlike BatchNorm. 📄 [Paper](https://arxiv.org/abs/1607.06450)

**Leaky ReLU**
Activation: `f(x) = x if x > 0, else αx` (α typically 0.01). Prevents the dying ReLU problem by allowing a small gradient for negative inputs. Variants: Parametric ReLU (PReLU) learns α; Randomized ReLU (RReLU) uses random α during training.

**Learning Rate**
The scaling factor applied to gradients during parameter updates: `θ ← θ - lr × gradient`. The most important hyperparameter in deep learning. Too high: training diverges. Too low: training is slow or gets stuck. Typically scheduled (warm-up + decay).

**Learning Rate Schedule**
A strategy for changing the learning rate during training. Common schedules: step decay, exponential decay, cosine annealing, linear warmup + cosine decay (standard for Transformers), OneCycleLR. Warmup is critical for Transformers to stabilize early training.

**Linear Regression**
The simplest supervised learning model: predicts a continuous output as a linear combination of input features: `ŷ = wᵀx + b`. Estimated via OLS (Ordinary Least Squares) or gradient descent. Assumptions: linearity, homoscedasticity, independence of errors.

**LSTM (Long Short-Term Memory)**
An RNN variant (Hochreiter & Schmidhuber, 1997) with a gating mechanism (input, forget, output gates) that allows learning long-range dependencies. Solved the vanishing gradient problem in RNNs. Now largely superseded by Transformers for sequence tasks. 📄 [Paper](https://www.bioinf.jku.at/publications/older/2604.pdf)

**LoRA (Low-Rank Adaptation)**
A parameter-efficient fine-tuning method (Hu et al., 2021) that adds low-rank decomposition matrices to frozen pre-trained weight matrices. Drastically reduces trainable parameters (e.g., from 7B to ~4M). Widely used for fine-tuning LLMs. 📄 [Paper](https://arxiv.org/abs/2106.09685) 🐙 [Repo](https://github.com/microsoft/LoRA)

**Loss Function**
A function measuring the discrepancy between model predictions and ground truth. The training objective that gets minimized. Examples: MSE (regression), cross-entropy (classification), contrastive loss (metric learning). → See [Loss Functions](#loss-functions)

**LLM (Large Language Model)**
A language model with billions of parameters pre-trained on massive text corpora. Exhibits emergent capabilities (reasoning, translation, coding) not present in smaller models. Examples: GPT-4, Claude, Gemini, Llama, Mistral. → See [Notable LLMs and Repos](#notable-llms-and-repos)

---

## M

**MAML (Model-Agnostic Meta-Learning)**
A meta-learning algorithm (Finn et al., 2017) that learns an initialization for model parameters such that a few gradient steps on a new task produce good performance. The initialization is task-agnostic and adapts quickly. 📄 [Paper](https://arxiv.org/abs/1703.03400)

**MAP (Maximum A Posteriori)**
A Bayesian estimation method that finds the parameter values maximizing the posterior distribution: `θ_MAP = argmax P(θ|data) = argmax P(data|θ)P(θ)`. Equivalent to MLE with regularization. The regularization term corresponds to the log prior.

**Markov Decision Process (MDP)**
The mathematical framework for RL. Defined by (S, A, P, R, γ): state space S, action space A, transition function P(s'|s,a), reward function R(s,a,s'), discount factor γ. The Markov property: the next state depends only on the current state and action.

**Masked Language Modeling (MLM)**
A pre-training objective (used in BERT) where a random fraction of input tokens are replaced with [MASK] tokens and the model must predict the original tokens. Enables bidirectional context and produces strong representations for understanding tasks.

**Maximum Likelihood Estimation (MLE)**
A method for estimating model parameters by maximizing the likelihood of observing the training data: `θ_MLE = argmax Π P(x_i|θ)`. Minimizing cross-entropy loss is equivalent to MLE for categorical distributions.

**Mean Squared Error (MSE)**
Loss for regression: `MSE = (1/n) Σ(y_i - ŷ_i)²`. Penalizes large errors more than small ones. Sensitive to outliers. Root MSE (RMSE) has the same units as the target variable.

**Message Passing**
The computational paradigm in GNNs: nodes aggregate messages from their neighbors, update their representations, and send updated representations in the next round. Multiple rounds = multi-hop neighborhood aggregation. → See [Graph Neural Networks](#graph-neural-networks)

**Meta-Learning**
"Learning to learn" — algorithms that improve learning efficiency across tasks by leveraging experience from previous tasks. Approaches: optimization-based (MAML), metric-based (Prototypical Networks), model-based (memory-augmented networks).

**MLP (Multi-Layer Perceptron)**
A fully connected feedforward neural network: each neuron in one layer is connected to all neurons in the next layer. The simplest form of deep neural network. Also called "dense network" or "feed-forward network."

**Model Capacity**
The ability of a model to fit a wide variety of functions. Controlled by number of parameters, depth, and width. High capacity: can fit complex patterns but may overfit. Low capacity: may underfit. Should be matched to data complexity.

**Model Parallelism**
Splitting a single model across multiple devices (different layers or parts of layers on different GPUs). Required for models too large to fit on a single device. Variants: pipeline parallelism (layers on different GPUs), tensor parallelism (matrices split across GPUs).

**Momentum**
An optimization technique that accumulates a velocity vector in the direction of persistent gradients, dampening oscillations and accelerating progress in consistent directions: `v ← βv - η∇L; θ ← θ + v`. Used in SGD with momentum and as a component of Adam.

**Multi-Head Attention**
Attention computed in parallel across multiple "heads," each with its own projection matrices. Each head can attend to different aspects of the input. Outputs are concatenated and projected. Core component of Transformers. → See [Attention and Transformers](#attention-and-transformers)

**Multi-Task Learning**
Training a single model on multiple related tasks simultaneously, sharing representations across tasks. Improves generalization, acts as regularization, and makes deployment efficient. Used in NLP (GLUE fine-tuning), robotics, and autonomous driving.

---

## N

**Neural Architecture Search (NAS)**
Automated search for the best neural network architecture using RL, evolutionary algorithms, or gradient-based methods. Produced EfficientNet, NASNet, DARTS. → See [Neural Architecture Search](#neural-architecture-search)

**Neural ODE**
A neural network where the hidden state evolves according to an ordinary differential equation: `dh/dt = f(h(t), t, θ)`. Proposed by Chen et al. (2018). Memory-efficient, continuous-depth alternative to ResNets. 📄 [Paper](https://arxiv.org/abs/1806.07366)

**Noise Contrastive Estimation (NCE)**
A technique for training unnormalized probabilistic models by distinguishing real data from artificially generated noise. Used to train word embeddings (word2vec's negative sampling) and language models efficiently.

**Non-Maximum Suppression (NMS)**
A post-processing step in object detection that removes redundant overlapping bounding boxes, keeping only the highest-confidence prediction for each object. Boxes with IoU > threshold relative to a higher-confidence box are suppressed.

**Normalization**
Scaling input features or layer activations to a standard range or distribution. Improves training stability, convergence speed, and generalization. Types: BatchNorm, LayerNorm, InstanceNorm, GroupNorm, RMSNorm.

---

## O

**Object Detection**
A computer vision task that simultaneously classifies and localizes objects in an image. Output: bounding boxes + class labels + confidence scores. Architectures: YOLO, SSD (one-stage), Faster R-CNN (two-stage), DETR (Transformer-based). → See [Object Detection](#object-detection)

**Offline RL**
Reinforcement learning from a fixed dataset of previously collected transitions, without any further interaction with the environment. Also called batch RL. Challenge: distributional shift — the learned policy may query state-action regions not covered by the dataset.

**One-Hot Encoding**
A representation of categorical variables as binary vectors where one element is 1 and all others are 0. Used for class labels in classification and as input to embedding layers. Limitations: high dimensionality, no notion of similarity between categories.

**Online Learning**
Training a model incrementally on a stream of data, updating after each example or mini-batch. Contrasted with batch learning. Required for non-stationary environments where the data distribution changes over time.

**Out-of-Distribution (OOD)**
Data that comes from a different distribution than the training data. Models often fail catastrophically on OOD data. Detecting OOD inputs and quantifying model uncertainty on them is an active research area.

**Overfitting**
When a model learns the training data too well — including its noise — and performs poorly on unseen data. Signs: large gap between training and validation performance. Solutions: regularization, dropout, early stopping, more data, data augmentation.

---

## P

**Parameter**
A learnable variable in a model that is updated during training via gradient descent. In neural networks: weights and biases. In GPT-3: 175 billion parameters. "Model size" typically refers to number of parameters.

**Parameter-Efficient Fine-Tuning (PEFT)**
Fine-tuning techniques that update only a small fraction of model parameters. Includes LoRA, Adapters, Prefix Tuning, Prompt Tuning. Enables fine-tuning large models with limited compute and memory. 🐙 [Hugging Face PEFT](https://github.com/huggingface/peft)

**Perplexity**
A standard metric for evaluating language models: `PPL = exp(-1/N Σ log P(w_i))`. Lower is better. Measures how "surprised" the model is by the test data. A perplexity of k means the model is as uncertain as if choosing uniformly among k options at each step.

**Pipeline (ML)**
A sequence of data processing and model training steps assembled as a single end-to-end workflow. In sklearn: `Pipeline([('scaler', StandardScaler()), ('clf', SVC())])`. In production: data ingestion → preprocessing → feature engineering → model training → evaluation → deployment.

**Policy (RL)**
A function mapping states to actions: `π(a|s)` (stochastic) or `π(s) → a` (deterministic). The goal of RL is to find the optimal policy maximizing expected cumulative discounted reward.

**Pooling**
A downsampling operation in CNNs that reduces spatial dimensions. **Max pooling**: takes the maximum value in a window. **Average pooling**: takes the mean. **Global Average Pooling (GAP)**: averages over the entire spatial dimension to a single vector.

**Posterior**
In Bayesian inference: the distribution over parameters after observing data: `P(θ|data) ∝ P(data|θ)P(θ)`. Combines the likelihood with the prior. The posterior predictive distribution is used for prediction with uncertainty.

**Precision**
`Precision = TP / (TP + FP)`. The fraction of positive predictions that are actually positive. High precision = few false alarms. Trade-off with recall. Important when the cost of false positives is high (e.g., spam filters, cancer screening follow-ups).

**Pre-training**
Training a model on a large, general dataset before fine-tuning on a specific task. Transfers knowledge from large-scale data to downstream tasks. The standard paradigm in NLP (BERT, GPT) and increasingly in vision (ViT, CLIP, MAE).

**Prior**
In Bayesian inference: the distribution over parameters before observing data: `P(θ)`. Encodes prior beliefs about parameter values. Informative priors incorporate domain knowledge; uninformative priors minimize assumptions.

**Prompt**
The input text provided to a language model to elicit a desired output. Prompt design dramatically affects LLM behavior. → See [Prompt Engineering](#prompt-engineering)

**Pruning**
Removing weights, neurons, or entire layers from a trained model to reduce size and inference cost. Methods: magnitude pruning (remove smallest weights), structured pruning (remove entire neurons/heads), lottery ticket hypothesis. Often followed by fine-tuning to recover accuracy.

---

## Q

**Q-Learning**
A model-free, off-policy RL algorithm that learns the action-value function Q(s,a): the expected cumulative reward from state s, taking action a, and following the optimal policy thereafter. Update rule: Bellman equation. Deep Q-Network (DQN) uses a neural network to approximate Q. → See [Model-Free RL](#model-free-rl)

**Quantization**
Representing model weights and/or activations with lower-precision numbers (e.g., INT8 or INT4 instead of FP32). Reduces model size and speeds up inference with minimal accuracy loss. Types: post-training quantization (PTQ), quantization-aware training (QAT). Tools: bitsandbytes, GPTQ, AWQ.

**Query, Key, Value (QKV)**
The three learned projections of the input in the attention mechanism. The query (Q) is compared against all keys (K) via dot product to compute attention weights, which are then applied to values (V): `Attention(Q,K,V) = softmax(QKᵀ/√d_k)V`. → See [Attention and Transformers](#attention-and-transformers)

---

## R

**Random Forest**
An ensemble of decision trees trained on bootstrap samples with random feature subsets. Predictions are averaged (regression) or majority-voted (classification). Robust, high-performing, and interpretable via feature importance. Hyperparameters: n_estimators, max_depth, max_features. → See [Decision Trees and Ensembles](#decision-trees-and-ensembles)

**Recall**
`Recall = TP / (TP + FN)`. The fraction of actual positives correctly identified. High recall = few missed positives. Trade-off with precision. Critical when missing a positive is costly (e.g., disease detection, fraud detection).

**Receptive Field**
The region of the input that influences a particular neuron's output. Grows with depth in CNNs. Larger receptive fields capture more global context. Attention in Transformers has a global receptive field from the first layer.

**Reconstruction Loss**
In autoencoders and VAEs: the loss measuring how well the decoder reconstructs the input from the latent representation. Typically MSE (continuous data) or binary cross-entropy (binary data). Balanced against the KL divergence term in VAEs.

**Rectified Linear Unit (ReLU)**
Activation function: `f(x) = max(0, x)`. Simple, computationally efficient, and alleviates the vanishing gradient problem. Can suffer from dying neurons (permanently outputting 0 if inputs are always negative). Most widely used activation in CNNs.

**Recurrent Neural Network (RNN)**
A neural network with connections that form cycles, enabling processing of sequential data. Hidden state persists across time steps, acting as memory. Suffers from vanishing/exploding gradients for long sequences. Superseded by Transformers. → See [Recurrent Neural Networks](#recurrent-neural-networks)

**Regularization**
Techniques to prevent overfitting by adding constraints or penalties to the learning process. Examples: L1/L2 weight penalties, dropout, data augmentation, early stopping, batch normalization. → See [Bias, Variance, and Regularization](#bias-variance-and-regularization)

**Reinforcement Learning (RL)**
A learning paradigm where an agent learns by interacting with an environment, receiving rewards for actions. Goal: maximize cumulative discounted reward. Key concepts: policy, value function, reward, Bellman equation. → See [RL Fundamentals](#rl-fundamentals)

**Representation Learning**
Learning useful representations of data — typically as dense vectors — that make downstream tasks easier. The core of deep learning. Self-supervised and contrastive methods learn representations without labels.

**ResNet (Residual Network)**
A CNN architecture (He et al., 2015) that introduces skip/residual connections: `F(x) + x`. Allows training very deep networks (50, 101, 152 layers) by mitigating vanishing gradients. Won ImageNet 2015. Widely influential across all of deep learning. 📄 [Paper](https://arxiv.org/abs/1512.03385)

**Reward Function**
In RL: a function specifying the immediate reward received after taking an action in a state: `R(s, a, s')`. Designing good reward functions is notoriously difficult (reward hacking, sparse rewards). RLHF replaces hand-designed rewards with human preferences.

**RLHF (Reinforcement Learning from Human Feedback)**
A technique to align language models with human preferences. Steps: (1) supervised fine-tuning on demonstrations, (2) train a reward model from human comparisons, (3) optimize the LLM with PPO against the reward model. Used in InstructGPT, ChatGPT, Claude. → See [RLHF and Alignment](#rlhf-and-alignment)

**RMSNorm**
A simplified LayerNorm that normalizes using only the root mean square (no mean subtraction): `RMSNorm(x) = x / RMS(x) × γ`. Used in LLaMA, T5. Slightly faster than LayerNorm with comparable performance.

**ROC Curve (Receiver Operating Characteristic)**
A plot of True Positive Rate vs. False Positive Rate at all classification thresholds. **AUC-ROC** (area under the curve) summarizes classifier performance across all thresholds. AUC = 0.5: random; AUC = 1.0: perfect.

**RoPE (Rotary Position Embedding)**
A position encoding technique (Su et al., 2021) that encodes absolute position information into query and key vectors via rotation matrices, while naturally capturing relative positions. Used in LLaMA, GPT-NeoX, PaLM. Better length generalization than sinusoidal embeddings. 📄 [Paper](https://arxiv.org/abs/2104.09864)

---

## S

**Self-Attention**
Attention where queries, keys, and values all come from the same sequence. Allows each position to attend to all other positions, capturing global dependencies. The core mechanism in Transformer encoders and decoders. O(n²) in sequence length.

**Self-Supervised Learning**
Learning representations from unlabeled data by creating supervisory signals from the data itself (e.g., predicting masked tokens, predicting the next frame, contrastive learning). Dominant pre-training paradigm for LLMs and increasingly for vision models.

**Semantic Segmentation**
Assigning a class label to every pixel in an image (without distinguishing individual instances). Architectures: FCN, U-Net, DeepLab, SegFormer. Evaluated with mean IoU (mIoU). → See [Image Segmentation](#image-segmentation)

**Sigmoid**
Activation: `σ(x) = 1 / (1 + e^(-x))`. Output in (0,1). Historically used in binary classification outputs and LSTM gates. Suffers from vanishing gradients for large |x|. Largely replaced by ReLU/GELU in hidden layers.

**Softmax**
A function that converts a vector of logits into a probability distribution: `softmax(z_i) = exp(z_i) / Σ exp(z_j)`. Used in the output layer of classifiers and in the attention mechanism. Temperature scaling: `softmax(z/T)` — lower T sharpens, higher T flattens.

**Sparse Attention**
Attention mechanisms that restrict which positions can attend to which, reducing the O(n²) cost. Examples: local window attention (Longformer), strided attention, axial attention, FlashAttention (memory-efficient exact attention). Enables processing very long sequences.

**Stable Diffusion**
An open-source latent diffusion model (Rombach et al., 2022) for text-to-image generation. Performs the diffusion process in a compressed latent space rather than pixel space, making it much more efficient. 🐙 [Repo](https://github.com/CompVis/stable-diffusion)

**Stochastic Gradient Descent (SGD)**
Gradient descent using a single or mini-batch of examples per update. The noise from small batches provides implicit regularization and helps escape local minima. With momentum and weight decay, competitive with Adam for vision tasks.

**Stride**
In convolutions: the number of pixels the filter moves at each step. Stride=1: dense feature map. Stride=2: halves spatial dimensions (used instead of pooling in some architectures like strided convolutions in ResNets).

**Surrogate Model**
In Bayesian optimization: a probabilistic model (usually a Gaussian Process) used to approximate the objective function. Cheaper to evaluate than the real function, used to guide the search for optimal hyperparameters.

---

## T

**Teacher Forcing**
A training strategy for sequence models where the ground truth token (instead of the model's own prediction) is fed as input at each step. Speeds up training but can cause exposure bias (model behaves differently during inference).

**Temperature (Sampling)**
A parameter controlling the randomness of LLM outputs. `T=0`: deterministic (greedy). `T=1`: standard sampling. `T>1`: more random/creative. `T<1`: more focused. Applied by dividing logits by T before softmax.

**Tensor**
A multi-dimensional array. The fundamental data structure of deep learning. Scalars (rank 0), vectors (rank 1), matrices (rank 2), and higher-dimensional arrays (rank n) are all tensors. In PyTorch/TensorFlow, tensors are differentiable and GPU-accelerated.

**TensorFlow**
An open-source deep learning framework by Google. Features: static/dynamic computation graphs, Keras high-level API, TF Serving for deployment, TFLite for mobile, TF.js for browser. 🐙 [Repo](https://github.com/tensorflow/tensorflow)

**Tokenization**
Converting raw text into a sequence of tokens (subwords, words, or characters) that serve as model inputs. Modern LLMs use subword tokenization (BPE, WordPiece, SentencePiece). → See [Tokenization](#tokenization)

**Transfer Learning**
Applying knowledge learned on one task/domain to a different but related task/domain. The dominant paradigm in NLP (pre-train on large corpus, fine-tune on task) and CV (ImageNet pre-training). → See [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)

**Transformer**
The dominant neural architecture for sequence modeling. Based entirely on self-attention (no recurrence or convolutions). Proposed by Vaswani et al. (2017). Foundation of BERT, GPT, T5, and nearly all modern LLMs. 📄 [Attention Is All You Need](https://arxiv.org/abs/1706.03762) → See [Attention and Transformers](#attention-and-transformers)

**t-SNE (t-Distributed Stochastic Neighbor Embedding)**
A non-linear dimensionality reduction technique (van der Maaten & Hinton, 2008) excellent for visualizing high-dimensional data in 2D/3D. Preserves local neighborhood structure. Not suitable for downstream ML tasks — use PCA or UMAP for that.

---

## U

**U-Net**
An encoder-decoder CNN architecture (Ronneberger et al., 2015) with skip connections between corresponding encoder and decoder layers. Designed for biomedical image segmentation. Widely used in image segmentation and as the denoising backbone in diffusion models. 📄 [Paper](https://arxiv.org/abs/1505.04597)

**Underfitting**
When a model is too simple to capture the underlying patterns in the data, resulting in high training error. Opposite of overfitting. Solution: increase model capacity, train longer, reduce regularization, add features.

**UMAP (Uniform Manifold Approximation and Projection)**
A dimensionality reduction technique that preserves both local and global structure better than t-SNE and runs much faster. Suitable for visualization and as a preprocessing step for clustering. 🐙 [Repo](https://github.com/lmcinnes/umap)

**Unsupervised Learning**
Learning from data without labels, discovering inherent structure. Includes clustering, dimensionality reduction, density estimation, and generative modeling. Increasingly powerful with modern self-supervised methods.

---

## V

**Validation Set**
A subset of data held out from training and used to monitor model performance during training and tune hyperparameters. Separate from the test set (which should only be used for final evaluation). Essential for early stopping and model selection.

**Value Function**
In RL: `V(s)` = expected cumulative discounted reward starting from state s under policy π. The state-action value function `Q(s,a)` = expected return starting from s, taking action a. Central to dynamic programming, Q-learning, and actor-critic methods.

**Vanishing Gradient**
A training problem where gradients become exponentially small as they backpropagate through many layers (especially in RNNs with long sequences or very deep networks). Causes early layers to learn very slowly. Solutions: ReLU, ResNets, LSTMs, gradient clipping, LayerNorm.

**VAE (Variational Autoencoder)**
A generative model combining autoencoders with variational inference. The encoder outputs a distribution (mean + variance) over latent codes rather than a single point. Trained with ELBO = reconstruction loss + KL divergence. Enables smooth interpolation in latent space. → See [Variational Autoencoders](#variational-autoencoders)

**Vision Transformer (ViT)**
A Transformer applied directly to image patches. Images are split into fixed-size patches, linearly embedded, and processed with standard Transformer self-attention. Proposed by Dosovitskiy et al. (2020). Competitive with or better than CNNs at scale. 📄 [Paper](https://arxiv.org/abs/2010.11929)

**Vocabulary**
The set of unique tokens a model knows. For BPE tokenizers, typically 30k–100k subword tokens. Out-of-vocabulary words are handled by breaking them into known subword units.

---

## W

**Weight Initialization**
The strategy for setting initial parameter values before training. Poor initialization can cause vanishing/exploding gradients. Common methods: Xavier/Glorot (for tanh), He/Kaiming (for ReLU), orthogonal initialization. Transformers often use scaled random normal initialization.

**Weight Sharing**
Using the same weights in multiple parts of a network. CNNs share filter weights across spatial positions. Transformers share attention weights across sequence positions. Dramatically reduces parameter count.

**Word2Vec**
A family of models (Mikolov et al., 2013) for learning word embeddings via two objectives: **CBOW** (predict word from context) and **Skip-gram** (predict context from word). First demonstration that distributed word representations capture semantic relationships. 📄 [Paper](https://arxiv.org/abs/1301.3781)

---

## X

**XGBoost (eXtreme Gradient Boosting)**
A highly optimized, scalable implementation of gradient boosted decision trees. Dominates tabular data competitions. Features: regularization, parallel tree construction, handling missing values. 🐙 [Repo](https://github.com/dmlc/xgboost)

---

## Z

**Zero-Shot Learning**
A model's ability to handle tasks or classes it has never seen during training. LLMs exhibit strong zero-shot performance on many tasks via in-context learning. In CV: classifying new categories using semantic descriptions or embeddings.

**Z-Score Normalization (Standardization)**
Transforms features to have zero mean and unit variance: `z = (x - μ) / σ`. Standard preprocessing for many ML algorithms. Does not bound the range (unlike min-max normalization). Sensitive to outliers.

---

---

# 🧮 Mathematics for AI

> Mathematics is the language of machine learning. This section covers the essential mathematical foundations every ML practitioner should know.

---

## Linear Algebra

Linear algebra is the backbone of neural networks — every forward pass is fundamentally a series of matrix multiplications.

### Core Concepts

**Vector**
An ordered list of numbers: `v = [v₁, v₂, ..., vₙ]`. Represents a point or direction in n-dimensional space. In ML: a data point, a word embedding, an activations vector.

**Matrix**
A 2D array of numbers: `A ∈ ℝᵐˣⁿ`. Represents a linear transformation from ℝⁿ to ℝᵐ. In ML: weight matrices, covariance matrices, attention matrices.

**Matrix Multiplication**
`C = AB` where `C[i,j] = Σₖ A[i,k] × B[k,j]`. Not commutative (AB ≠ BA in general). The core operation of every neural network layer: `output = W × input + b`.

**Transpose**
`Aᵀ[i,j] = A[j,i]`. Flips rows and columns. Key identity: `(AB)ᵀ = BᵀAᵀ`.

**Dot Product**
`a · b = Σᵢ aᵢbᵢ = ||a|| ||b|| cos(θ)`. Measures alignment between vectors. Foundation of attention scores, cosine similarity, and linear regression prediction.

**Norm**
Measures the "size" of a vector. L2 norm (Euclidean): `||v||₂ = √(Σvᵢ²)`. L1 norm: `||v||₁ = Σ|vᵢ|`. L∞ norm: `max|vᵢ|`. Used in gradient clipping, regularization, and distance metrics.

**Eigenvalues and Eigenvectors**
For matrix A: `Av = λv`. Eigenvectors v are directions unchanged by the transformation A; eigenvalues λ are the scaling factors. Fundamental to PCA, spectral clustering, and understanding optimization landscapes.

**Singular Value Decomposition (SVD)**
`A = UΣVᵀ` decomposes any matrix into rotation × scaling × rotation. Used in PCA, collaborative filtering, dimensionality reduction, LoRA (low-rank approximation). Every matrix has an SVD; not every matrix has an eigendecomposition.

**Principal Component Analysis (PCA)**
Projects data onto the directions of maximum variance (principal components = eigenvectors of the covariance matrix). Used for dimensionality reduction, visualization, noise reduction. Linear method — cannot capture non-linear structure.

**Rank**
The number of linearly independent rows (or columns) of a matrix. A rank-k approximation captures the k most important dimensions. LoRA exploits low-rank structure of weight update matrices.

**Positive Definite Matrix**
A symmetric matrix A is positive definite if `xᵀAx > 0` for all non-zero x. Equivalently: all eigenvalues are positive. Covariance matrices and Hessians at local minima are positive (semi-)definite.

### Resources
- 🎓 [3Blue1Brown: Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) ⭐
- 🎓 [Gilbert Strang MIT 18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- 📄 [The Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

---

## Calculus and Optimization

**Derivative**
The instantaneous rate of change of a function: `f'(x) = lim_{h→0} [f(x+h) - f(x)] / h`. In ML: how the loss changes with respect to a parameter.

**Partial Derivative**
Derivative with respect to one variable while holding others constant: `∂f/∂xᵢ`. The gradient is the vector of all partial derivatives.

**Chain Rule**
`d/dx [f(g(x))] = f'(g(x)) × g'(x)`. The fundamental rule behind backpropagation. Applied recursively through computational graphs to compute gradients of the loss with respect to all parameters.

**Gradient**
`∇_θ L = [∂L/∂θ₁, ∂L/∂θ₂, ..., ∂L/∂θₙ]`. Points in the direction of steepest ascent. Gradient descent moves in the opposite direction: `θ ← θ - η∇L`.

**Hessian**
Matrix of second-order partial derivatives: `H[i,j] = ∂²L / ∂θᵢ∂θⱼ`. Describes the curvature of the loss landscape. Positive definite Hessian at a point = local minimum. Too expensive to compute for large networks (Newton's method requires inverting it).

**Automatic Differentiation (Autograd)**
Programmatic computation of exact gradients by tracking operations in a computational graph and applying the chain rule. Unlike symbolic differentiation (slow, complex) or numerical differentiation (approximate). Implemented in PyTorch (dynamic graph) and JAX (functional transformations).

**Convexity**
A function is convex if the line segment between any two points lies above the function: `f(λx + (1-λ)y) ≤ λf(x) + (1-λ)f(y)`. Convex optimization has no local minima (only global). Deep learning loss landscapes are non-convex — but in practice, most local minima are good.

**Saddle Points**
Points where the gradient is zero but are neither local minima nor maxima. Common in high-dimensional landscapes. SGD with momentum naturally escapes saddle points due to gradient noise.

**Learning Rate Schedules in Detail**
- **Cosine Annealing**: `lr = lr_min + 0.5(lr_max - lr_min)(1 + cos(πt/T))`
- **Linear Warmup**: gradually increase lr from 0 to max over first k steps
- **Step Decay**: multiply lr by γ (e.g., 0.1) every N epochs
- **ReduceLROnPlateau**: reduce lr when a metric stops improving
- **1-Cycle Policy**: Smith (2018) — one cycle of warmup then cool-down

### Resources
- 🎓 [3Blue1Brown: Calculus series](https://www.3blue1brown.com/topics/calculus) ⭐
- 🎓 [Karpathy: Yes you should understand backprop](https://karpathy.medium.com/yes-you-should-understand-backprop-e2f06eab496b)
- 📄 [Convex Optimization — Boyd & Vandenberghe (free PDF)](https://web.stanford.edu/~boyd/cvxbook/)

---

## Probability and Statistics

**Random Variable**
A variable whose value is determined by a random process. Discrete (finite/countable values) or continuous (real-valued). Described by probability mass functions (PMF) or probability density functions (PDF).

**Probability Distributions**

| Distribution | Use in ML |
|---|---|
| **Gaussian (Normal)** | Noise models, weight initialization, VAE priors |
| **Bernoulli** | Binary classification outputs |
| **Categorical** | Multiclass classification, token sampling |
| **Uniform** | Random search, random initialization |
| **Beta** | Bayesian conjugate prior for Bernoulli |
| **Dirichlet** | Prior over categorical distributions (LDA) |
| **Laplace** | L1 regularization (corresponds to Laplace prior) |
| **Poisson** | Count data modeling |

**Bayes' Theorem**
`P(A|B) = P(B|A) × P(A) / P(B)`. Foundation of Bayesian inference, Naive Bayes classifiers, and generative models. Posterior ∝ Likelihood × Prior.

**Expectation and Variance**
- `E[X] = Σ x P(x)` (discrete) or `∫ x p(x) dx` (continuous)
- `Var(X) = E[(X - E[X])²] = E[X²] - E[X]²`
- `Cov(X,Y) = E[(X-μX)(Y-μY)]`

**Central Limit Theorem**
The sum of many independent random variables tends toward a Gaussian distribution regardless of the original distribution. Explains why Gaussian noise assumptions are robust and why averaging works.

**Maximum Likelihood Estimation (MLE)**
`θ_MLE = argmax_θ Σ log P(xᵢ|θ)`. The standard objective for fitting probabilistic models. Minimizing cross-entropy loss is equivalent to MLE for categorical distributions.

**ELBO (Evidence Lower BOund)**
In variational inference: `log P(x) ≥ E_q[log P(x|z)] - KL(q(z|x) || p(z))`. The VAE training objective maximizes the ELBO — reconstruction quality minus KL divergence from prior. Tight when q matches the true posterior.

**Hypothesis Testing**
Statistical framework for making decisions from data. p-value: probability of observing results as extreme as observed under the null hypothesis. Common tests: t-test, chi-squared, ANOVA. Often misused in ML evaluation — prefer confidence intervals and effect sizes.

**Monte Carlo Methods**
Approximating deterministic quantities using random sampling. In ML: MC gradient estimation, Monte Carlo Tree Search (MCTS in AlphaGo), approximate Bayesian inference. Law of large numbers guarantees convergence.

### Resources
- 🎓 [Probability for Computer Scientists (Stanford CS109)](https://web.stanford.edu/class/cs109/)
- 📚 [Pattern Recognition and Machine Learning — Bishop (free PDF)](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- 🎓 [StatQuest with Josh Starmer (YouTube)](https://www.youtube.com/c/joshstarmer) ⭐

---

## Information Theory

**Entropy**
`H(X) = -Σ p(x) log p(x)`. Measures average uncertainty. Uniform distribution: maximum entropy. Deterministic distribution: zero entropy. Used in decision trees (information gain), compression, and loss functions.

**Cross-Entropy**
`H(P, Q) = -Σ P(x) log Q(x)`. Measures the cost of encoding distribution P using code optimized for Q. In ML: the standard classification loss. `H(P,Q) = H(P) + KL(P||Q)`.

**KL Divergence**
`KL(P||Q) = Σ P(x) log [P(x)/Q(x)]`. Non-symmetric measure of difference between distributions. Always ≥ 0. Zero iff P=Q. Used in VAEs, RL (PPO KL penalty), knowledge distillation.

**Mutual Information**
`I(X;Y) = KL(P(X,Y) || P(X)P(Y))`. Measures the reduction in uncertainty about X given knowledge of Y. Used in feature selection, representation learning (InfoNCE loss, DIM), and causal discovery.

**Jensen-Shannon Divergence**
Symmetric, bounded version of KL divergence: `JSD(P||Q) = 0.5 KL(P||M) + 0.5 KL(Q||M)` where M = 0.5(P+Q). Used as the original GAN loss (in theory). Bounded in [0, 1] when using log base 2.

**Bits and Nats**
Entropy can be measured in bits (log base 2) or nats (natural log). Perplexity = 2^entropy (bits) or e^entropy (nats). Models that compress well have low perplexity.

### Resources
- 📚 [Elements of Information Theory — Cover & Thomas](http://staff.ustc.edu.cn/~cgong821/Wiley.Interscience.Elements.of.Information.Theory.Jul.2006.eBook-DDU.pdf)
- 📰 [Visual Information Theory — Colah's Blog](https://colah.github.io/posts/2015-09-Visual-Information/)

---

## Computational Complexity

**Big-O Notation**
Describes the asymptotic behavior of algorithms as input size grows. Common complexities in ML:
- `O(1)`: constant — lookup table
- `O(n)`: linear — scanning a dataset
- `O(n²)`: quadratic — pairwise similarity, standard self-attention
- `O(n³)`: cubic — exact Gaussian Process inference, matrix inversion
- `O(d × n)`: CNN convolution (d = filter size, n = spatial positions)

**Why Self-Attention is O(n²)**
For a sequence of length n tokens, each token attends to all other tokens: n × n attention matrix. Memory: O(n²). Computation: O(n²d) where d is model dimension. Problem for long documents — motivates sparse attention (Longformer, BigBird) and FlashAttention.

**NP-Hardness in ML**
Several ML problems are NP-hard in theory: training an optimal neural network, finding the minimum description length representation, solving exact MAP inference in general graphical models. In practice, local optima found by SGD are often good enough.

**Space vs. Time Trade-offs**
Gradient checkpointing: trade time (recompute) for space (don't store activations). Mixed precision: trade precision for speed. Caching KV attention: trade space for inference speed.

---

## Logic and Symbolic AI

**Propositional Logic**
Formal system with propositions (true/false), logical connectives (AND, OR, NOT, →, ↔), and inference rules. Foundation of classical AI search and constraint satisfaction.

**First-Order Logic (FOL)**
Extends propositional logic with variables, quantifiers (∀, ∃), predicates, and functions. Enables reasoning about objects and their relationships. Used in knowledge representation, automated theorem proving, and neuro-symbolic AI.

**Knowledge Representation**
Encoding facts about the world in a form a computer can reason about. Methods: semantic networks, frames, ontologies (OWL/RDF), knowledge graphs, logic programs (Prolog). Challenge: the frame problem (updating only relevant knowledge after an action).

**Search Algorithms**
Classical AI relies on search over state spaces. **Uninformed**: BFS, DFS, Dijkstra. **Informed**: A* (uses heuristic estimate to guide search). **Adversarial**: Minimax + Alpha-Beta pruning (chess, Go). **Stochastic**: MCTS (Monte Carlo Tree Search — used in AlphaGo/AlphaZero).

**Expert Systems**
Early AI systems encoding human expert knowledge as if-then rules. Prominent in the 1980s (MYCIN for medical diagnosis). Brittle — cannot handle cases outside predefined rules. Replaced by statistical/learning approaches.

**Neuro-Symbolic AI**
Combining neural networks (sub-symbolic pattern recognition) with symbolic reasoning (logical inference, knowledge graphs). Goal: systems with both the perceptual capabilities of NNs and the reasoning/compositionality of symbolic AI. Active research area.

**Constraint Satisfaction Problems (CSP)**
Problems where variables must be assigned values satisfying a set of constraints. Examples: Sudoku, scheduling, configuration. Solved via backtracking search + constraint propagation. Used in planning and configuration in AI systems.

---

# 🤖 Machine Learning

---

## Core ML Concepts

**The ML Pipeline**
```
Raw Data → Data Collection → EDA → Preprocessing → Feature Engineering
→ Model Selection → Training → Evaluation → Hyperparameter Tuning
→ Final Evaluation → Deployment → Monitoring
```

**Types of ML**

| Type | Labels | Goal | Examples |
|---|---|---|---|
| Supervised | Yes (input→output) | Predict outputs | Classification, Regression |
| Unsupervised | No | Find structure | Clustering, Dimensionality Reduction |
| Semi-supervised | Partial | Leverage unlabeled data | Self-training, Label Propagation |
| Self-supervised | Generated from data | Learn representations | BERT MLM, SimCLR, MAE |
| Reinforcement | Reward signal | Maximize reward | Games, Robotics, RLHF |

**The No Free Lunch Theorem**
No single algorithm is best for all problems. Every algorithm has an inductive bias — assumptions built into it. The best algorithm depends on the specific data distribution and task. Practical implication: always experiment with multiple approaches.

**Inductive Bias**
The set of assumptions a learning algorithm uses to generalize from training examples to unseen inputs. Examples: CNNs assume translation invariance; RNNs assume sequential dependence; Transformers assume pairwise token interactions. Choosing the right inductive bias for your problem is crucial.

**Generalization Bounds**
Theoretical guarantees on how well a model trained on a finite dataset will generalize to unseen data. From PAC learning theory: `generalization error ≤ training error + O(√(VC_dimension / n))`. In practice, these bounds are loose — empirical validation is essential.

**Train/Validation/Test Split**
- **Training set**: used to fit model parameters
- **Validation set**: used to tune hyperparameters and make model selection decisions
- **Test set**: used only once for final, unbiased performance estimate
- Typical splits: 70/15/15 or 80/10/10. For small datasets: use cross-validation.

**Data Preprocessing**
- **Missing values**: impute (mean, median, KNN) or remove
- **Categorical encoding**: one-hot, label encoding, target encoding, embeddings
- **Feature scaling**: standardization (z-score), min-max normalization, robust scaling
- **Outlier handling**: clip, remove, or use robust models
- **Class imbalance**: oversampling (SMOTE), undersampling, class weights

**Exploratory Data Analysis (EDA)**
The process of visualizing and summarizing a dataset to understand its structure before modeling. Key tasks: distribution analysis, correlation matrix, missing value audit, outlier detection, class balance check. Libraries: pandas, matplotlib, seaborn, plotly.

**Leakage Prevention Checklist**
- ✅ Fit preprocessing (scalers, imputers) on training set only, transform validation/test
- ✅ Ensure no future information in features for time-series
- ✅ No shared examples between train and test
- ✅ Target encoding done inside cross-validation folds
- ✅ Check for duplicates across splits

---

## Supervised Learning

### Linear Models

**Linear Regression**
`ŷ = wᵀx + b`. Closed-form solution: `w = (XᵀX)⁻¹Xᵀy` (OLS). Gradient descent solution for large n. Assumes linearity, homoscedasticity, independent errors, no multicollinearity.

**Ridge Regression (L2)**
`minimize ||Xw - y||² + λ||w||²`. Shrinks coefficients toward zero. Better than OLS when features are correlated. Closed-form: `w = (XᵀX + λI)⁻¹Xᵀy`.

**Lasso Regression (L1)**
`minimize ||Xw - y||² + λ||w||₁`. Produces sparse solutions — some coefficients are exactly zero. Acts as feature selection. No closed form — requires coordinate descent or proximal gradient methods.

**Elastic Net**
Combines L1 and L2: `minimize ||Xw - y||² + λ₁||w||₁ + λ₂||w||²`. Best of both: sparsity from L1, handling of correlated features from L2.

**Logistic Regression**
`P(y=1|x) = σ(wᵀx + b)`. Despite the name, it's a classification model. Outputs calibrated probabilities. Trained by maximizing log-likelihood (equivalent to minimizing cross-entropy). Fast, interpretable, strong baseline.

**Generalized Linear Models (GLMs)**
Extend linear regression to non-Gaussian outcomes via a link function. Poisson regression for counts, logistic regression for binary, gamma regression for positive continuous. Foundation of classical statistics.

### Decision Trees and Ensembles

**Decision Tree**
A tree where internal nodes test a feature, branches represent outcomes, and leaves give predictions. Splitting criteria: **Gini impurity** (CART), **Information Gain** (ID3, C4.5), **Variance reduction** (regression). Prone to overfitting — limit depth or prune.

**Random Forest**
N decision trees on bootstrap samples with random feature subsets. Reduces variance through averaging. Hyperparameters: `n_estimators` (more is better up to diminishing returns), `max_features` (√d for classification, d/3 for regression), `max_depth`.

**Gradient Boosting**
Sequential ensemble: each tree corrects the residuals of the previous ensemble. Very powerful for tabular data. Implementations:
- 🐙 [XGBoost](https://github.com/dmlc/xgboost) — regularized, parallel, handles missing values
- 🐙 [LightGBM](https://github.com/microsoft/LightGBM) — leaf-wise growth, faster on large datasets
- 🐙 [CatBoost](https://github.com/catboost/catboost) — handles categorical features natively

**AdaBoost**
The first successful boosting algorithm. Reweights training examples: misclassified examples get higher weights in subsequent rounds. Each weak learner is typically a shallow decision tree (stump).

**Stacking**
A meta-ensemble where base models' predictions are used as features to train a meta-model (blender). Can combine models of different types (trees + neural nets + SVMs). Requires careful cross-validation to avoid leakage.

### Support Vector Machines

**SVM (Support Vector Machine)**
Finds the maximum-margin hyperplane separating classes. Support vectors: the training points closest to the decision boundary (and most influential). Dual formulation enables the kernel trick.

**Kernel Trick**
Computes dot products in a high-dimensional feature space without explicitly mapping to that space: `k(x, x') = φ(x)·φ(x')`. Enables non-linear decision boundaries with a linear classifier in the implicit feature space.

**Common Kernels**
- **Linear**: `k(x,x') = xᵀx'`
- **RBF (Gaussian)**: `k(x,x') = exp(-γ||x-x'||²)` — most popular
- **Polynomial**: `k(x,x') = (xᵀx' + c)^d`
- **Sigmoid**: `k(x,x') = tanh(αxᵀx' + c)`

**SVR (Support Vector Regression)**
SVM for regression: finds a function within an ε-tube around the data points, ignoring errors smaller than ε. Robust to outliers.

### k-Nearest Neighbors

**k-NN**
A non-parametric, instance-based learning algorithm. Prediction for a new point: find k nearest training points (by Euclidean, Manhattan, or Minkowski distance) and take majority vote (classification) or mean (regression). No training phase — all computation at inference. Suffers from the curse of dimensionality.

**Curse of Dimensionality**
In high-dimensional spaces, data becomes sparse — all points become approximately equidistant from each other. Nearest neighbors lose meaning. Volume of a unit ball shrinks relative to its bounding box. Most ML algorithms degrade with very high dimensionality.

**Approximate Nearest Neighbor (ANN)**
For large-scale k-NN, exact search is too slow. ANN algorithms trade accuracy for speed: HNSW, LSH (Locality Sensitive Hashing), FAISS (Facebook AI Similarity Search). Essential for dense retrieval and vector databases.

### Naive Bayes

**Naive Bayes Classifier**
Applies Bayes' theorem with the "naive" assumption that features are conditionally independent given the class: `P(y|x) ∝ P(y) × Π P(xᵢ|y)`. Despite the unrealistic independence assumption, works surprisingly well for text classification.

**Variants**
- **Gaussian NB**: features follow Gaussian distribution — good for continuous features
- **Multinomial NB**: for count data (word counts in documents)
- **Bernoulli NB**: for binary features (word presence/absence)

**Laplace Smoothing**
Adds a small constant α (usually 1) to all counts to avoid zero probability for unseen feature-class combinations: `P(xᵢ|y) = (count(xᵢ,y) + α) / (count(y) + α × |V|)`.

---

## Unsupervised Learning

### Clustering

**K-Means**
Initialize k centroids → assign each point to nearest centroid → recompute centroids → repeat until convergence. Objective: minimize within-cluster sum of squares (inertia). Sensitive to initialization — use K-Means++ for better initialization.

**DBSCAN (Density-Based Spatial Clustering)**
Groups densely connected points; marks low-density points as noise/outliers. Two hyperparameters: `eps` (neighborhood radius), `min_samples` (minimum points to form a core point). Can find clusters of arbitrary shapes. No need to specify k.

**Hierarchical Clustering**
Builds a tree (dendrogram) of clusters. **Agglomerative** (bottom-up): start with each point as its own cluster, merge closest clusters. **Divisive** (top-down): start with all points, split recursively. Linkage criteria: single, complete, average, Ward.

**Gaussian Mixture Models (GMM)**
Soft clustering assuming data comes from a mixture of Gaussian distributions. Trained with EM algorithm. Provides probabilistic cluster assignments (unlike hard assignment in K-Means). Can model elliptical clusters.

**Evaluation Metrics for Clustering**
- **Silhouette score**: measures how similar a point is to its own cluster vs. other clusters. Range: [-1, 1]. Higher is better.
- **Davies-Bouldin index**: ratio of intra-cluster scatter to inter-cluster distance. Lower is better.
- **Adjusted Rand Index (ARI)**: for comparing with ground truth labels.
- **Inertia**: within-cluster sum of squares (K-Means specific).

### Dimensionality Reduction

**PCA (Principal Component Analysis)**
Linear projection onto directions of maximum variance. Steps: center data → compute covariance matrix → eigendecomposition → project onto top k eigenvectors. Deterministic, fast, interpretable. Cannot capture non-linear structure.

**t-SNE**
Constructs probability distributions over pairs in high-dim and low-dim spaces, minimizes KL divergence between them. Preserves local neighborhood structure beautifully. Hyperparameter: perplexity (controls neighborhood size, typically 5–50). Stochastic — different runs produce different results.

**UMAP**
Based on Riemannian geometry and fuzzy topology. Faster than t-SNE, better global structure preservation, deterministic (with fixed seed). Can be used for general dimensionality reduction (not just visualization). 🐙 [Repo](https://github.com/lmcinnes/umap)

**Autoencoders for Dimensionality Reduction**
Encoder compresses to bottleneck; decoder reconstructs. Non-linear, learned reduction. More flexible than PCA. Bottleneck dimension = reduced dimensionality. → See [Neural Network Fundamentals](#neural-network-fundamentals)

**LDA (Linear Discriminant Analysis)**
Supervised dimensionality reduction: finds directions maximizing between-class variance relative to within-class variance. Requires class labels. Also used as a classifier.

### Density Estimation

**Kernel Density Estimation (KDE)**
Non-parametric method for estimating a PDF by placing a kernel (usually Gaussian) at each data point and summing: `f̂(x) = (1/nh) Σ K((x - xᵢ)/h)`. Bandwidth h controls smoothness. Used in anomaly detection and data visualization.

**Latent Dirichlet Allocation (LDA)**
A probabilistic generative model for text documents. Assumes documents are mixtures of topics, and topics are distributions over words. Inferred via variational EM or collapsed Gibbs sampling. Classic topic modeling algorithm.

---

## Semi-Supervised and Self-Supervised Learning

**Self-Training**
Train a model on labeled data → use it to label unlabeled data → retrain on combined dataset. Simple but effective. Risk: error propagation (wrong pseudo-labels reinforce themselves).

**Label Propagation**
Spreads labels from labeled to unlabeled examples through a similarity graph. Label smoothness assumption: connected nodes in the graph should have similar labels. Works well when the graph structure captures the data manifold.

**Consistency Regularization**
Encourages a model to produce the same prediction for different augmented views of the same unlabeled example. Used in MixMatch, FixMatch, UDA. Key insight: predictions should be robust to realistic perturbations.

**Contrastive Self-Supervised Learning**
Learn representations by contrasting positive pairs (augmentations of the same image) against negative pairs (different images). Key methods:
- 🐙 **SimCLR** (Chen et al., 2020): large batch, projection head, NT-Xent loss. [Paper](https://arxiv.org/abs/2002.05709)
- 🐙 **MoCo** (He et al., 2020): momentum encoder as a memory bank. [Paper](https://arxiv.org/abs/1911.05722)
- 🐙 **BYOL** (Grill et al., 2020): no negative pairs — uses asymmetric architecture. [Paper](https://arxiv.org/abs/2006.07733)
- 🐙 **SimSiam** (Chen & He, 2021): no negatives, no momentum, stop-gradient is key. [Paper](https://arxiv.org/abs/2011.10566)

**Masked Autoencoders (MAE)**
Mask a large fraction (75%) of image patches and reconstruct them from unmasked patches. He et al. (2021). Learns strong visual representations. Vision analog of BERT's MLM. Very compute-efficient because only unmasked tokens are processed by the encoder. 📄 [Paper](https://arxiv.org/abs/2111.06377)

**DINO (Self-DIstillation with NO labels)**
Self-supervised ViT training using self-distillation with a momentum teacher. Emergent segmentation properties: attention maps align with object boundaries without supervision. 📄 [Paper](https://arxiv.org/abs/2104.14294) 🐙 [Repo](https://github.com/facebookresearch/dino)

---

## Evaluation and Metrics

### Classification Metrics

| Metric | Formula | Use Case |
|---|---|---|
| Accuracy | (TP+TN)/(total) | Balanced classes |
| Precision | TP/(TP+FP) | Low FP cost |
| Recall | TP/(TP+FN) | Low FN cost |
| F1 Score | 2×P×R/(P+R) | Imbalanced classes |
| AUC-ROC | Area under ROC curve | Ranking quality |
| AUC-PR | Area under PR curve | Highly imbalanced |
| MCC | Matthews Corr. Coef. | Binary, imbalanced |
| Log Loss | -Σ y log(p) | Probabilistic predictions |
| Cohen's Kappa | (Po-Pe)/(1-Pe) | Agreement beyond chance |

### Regression Metrics

| Metric | Formula | Notes |
|---|---|---|
| MAE | (1/n)Σ|y-ŷ| | Robust to outliers |
| MSE | (1/n)Σ(y-ŷ)² | Penalizes large errors |
| RMSE | √MSE | Same units as y |
| R² | 1 - SS_res/SS_tot | Variance explained |
| MAPE | (1/n)Σ|y-ŷ|/y × 100% | Percentage error |
| Huber Loss | MSE if small, MAE if large | Robust to outliers |

### NLP Metrics

| Metric | Use Case |
|---|---|
| BLEU | Machine translation |
| ROUGE | Summarization |
| METEOR | Translation (synonym-aware) |
| BERTScore | Semantic similarity of generated text |
| Perplexity | Language model quality |
| MMLU | LLM reasoning/knowledge benchmark |
| HumanEval | Code generation benchmark |

### Statistical Significance
Always report confidence intervals, not just point estimates. Use bootstrap resampling or paired t-tests to assess whether differences between models are significant. With large test sets, very small differences can be statistically significant but practically meaningless.

---

## Bias, Variance, and Regularization

**The Decomposition**
`Total Error = Bias² + Variance + Irreducible Noise`

- **Bias**: error from wrong assumptions in the model. High bias = underfitting.
- **Variance**: error from sensitivity to small fluctuations in training data. High variance = overfitting.
- **Irreducible noise**: inherent noise in the data — cannot be eliminated.

**Double Descent**
An empirically observed phenomenon where test error decreases, increases (classical overfitting), then decreases again as model size grows beyond the interpolation threshold. Challenges the classical bias-variance tradeoff. Observed in neural networks and kernel methods with many parameters. 📄 [Paper: Belkin et al., 2019](https://arxiv.org/abs/1812.11118)

**Regularization Techniques Summary**

| Technique | Mechanism | When to Use |
|---|---|---|
| L2 (Weight Decay) | Penalize large weights | Always a safe default |
| L1 (Lasso) | Sparse weights | When feature selection needed |
| Dropout | Randomly zero neurons | Dense layers, not BatchNorm layers |
| Early Stopping | Stop at best validation | When validation curve available |
| Data Augmentation | More training diversity | Limited data, images/text |
| Label Smoothing | Softer targets | Classification, prevent overconfidence |
| Gradient Clipping | Cap gradient norms | RNNs, Transformers |
| Batch Normalization | Normalize activations | CNNs, MLP |
| Layer Normalization | Normalize per sample | Transformers |

---

## Feature Engineering

**Numerical Features**
- Binning/discretization: convert continuous to ordinal categories
- Log transform: handle right-skewed distributions
- Polynomial features: capture non-linear interactions
- Clipping: handle outliers
- Rank transformation: robust to outliers, creates uniform distribution

**Categorical Features**
- One-hot encoding: for low cardinality (< ~20 categories)
- Target encoding: replace category with mean target value (risk: leakage — must do inside CV)
- Frequency encoding: replace with category frequency
- Embedding layers: for high cardinality in neural networks

**Temporal Features**
- Extract: hour, day of week, month, year, quarter
- Cyclical encoding: sin/cos of time variables to preserve cyclical nature
- Lag features: previous values
- Rolling statistics: moving average, standard deviation

**Text Features (Classical)**
- **Bag of Words (BoW)**: count matrix of word occurrences
- **TF-IDF**: term frequency × inverse document frequency — down-weights common words
- **N-grams**: combinations of n consecutive words — captures local context

**Feature Selection Methods**
- Filter methods: correlation, mutual information, variance threshold (fast, model-agnostic)
- Wrapper methods: recursive feature elimination with cross-validation (RFE-CV)
- Embedded methods: L1 regularization, tree feature importance
- SHAP-based selection: use SHAP values from a trained model

---
