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
