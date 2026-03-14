# 🧠 Awesome AI Knowledge Base

> A comprehensive, curated repository of Artificial Intelligence knowledge — concepts, algorithms, architectures, tools, papers, repos, datasets, and communities. Built in the spirit of the **Awesome List** tradition.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Lines](https://img.shields.io/badge/lines-8000%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Last Updated](https://img.shields.io/badge/updated-2025-brightgreen)

> **How to use this file:** Read top to bottom or jump to any section via the Table of Contents. The Glossary comes first — familiarize yourself with the terms before diving into the technical sections. Each section is self-contained but cross-referenced throughout.

---

## Table of Contents

### Meta
- [Legend](#legend)
- [Contributing](#contributing)

### Glossary
- [Glossary A–F](#glossary-af)
- [Glossary G–Z](#glossary-gz)

### Foundations
- [Mathematics for AI](#mathematics-for-ai)
  - [Linear Algebra](#linear-algebra)
  - [Calculus and Optimization](#calculus-and-optimization)
  - [Probability and Statistics](#probability-and-statistics)
  - [Information Theory](#information-theory)
- [Computational Complexity](#computational-complexity)
- [Logic and Symbolic AI](#logic-and-symbolic-ai)

### Machine Learning
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

### Deep Learning
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

### NLP and Large Language Models
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

### Computer Vision
- [CV Fundamentals](#cv-fundamentals)
- [Image Classification](#image-classification)
- [Object Detection](#object-detection)
- [Image Segmentation](#image-segmentation)
- [Image Generation and Editing](#image-generation-and-editing)
- [Video Understanding](#video-understanding)
- [3D Vision and NeRF](#3d-vision-and-nerf)

### Deep Reinforcement Learning
- [RL Fundamentals](#rl-fundamentals)
- [Model-Free RL](#model-free-rl)
- [Model-Based RL](#model-based-rl)
- [Multi-Agent RL](#multi-agent-rl)
- [RL from Human Feedback](#rl-from-human-feedback)
- [Notable RL Environments and Repos](#notable-rl-environments-and-repos)

### Multimodal AI
- [Vision-Language Models](#vision-language-models)
- [Audio and Speech AI](#audio-and-speech-ai)
- [Multimodal Architectures](#multimodal-architectures)

### MLOps and Production AI
- [MLOps Concepts](#mlops-concepts)
- [Experiment Tracking](#experiment-tracking)
- [Model Serving and Deployment](#model-serving-and-deployment)
- [Monitoring and Observability](#monitoring-and-observability)
- [Data Versioning and Pipelines](#data-versioning-and-pipelines)
- [Distributed Training](#distributed-training)

### Frameworks and Libraries
- [Core Frameworks](#core-frameworks)
- [NLP Libraries](#nlp-libraries)
- [CV Libraries](#cv-libraries)
- [RL Libraries](#rl-libraries)
- [Data Processing](#data-processing)
- [Visualization Tools](#visualization-tools)
- [AutoML Tools](#automl-tools)
- [Vector Databases](#vector-databases)

### Landmark Papers
- [Pre-2015 Classics](#pre-2015-classics)
- [2015–2018 Breakthroughs](#20152018-breakthroughs)
- [2019–2021 Scaling Era](#20192021-scaling-era)
- [2022–2025 Modern Era](#20222025-modern-era)

### Datasets
- [Image Datasets](#image-datasets)
- [NLP Datasets](#nlp-datasets)
- [Multimodal Datasets](#multimodal-datasets)
- [RL Environments](#rl-environments)
- [Benchmarks](#benchmarks)

### Communities and Resources
- [Online Communities](#online-communities)
- [Courses and Tutorials](#courses-and-tutorials)
- [Blogs and Newsletters](#blogs-and-newsletters)
- [Conferences and Journals](#conferences-and-journals)
- [Research Labs and Organizations](#research-labs-and-organizations)

### AI Ethics and Safety
- [Fairness and Bias](#fairness-and-bias)
- [Interpretability and Explainability](#interpretability-and-explainability)
- [AI Safety Research](#ai-safety-research)
- [Privacy-Preserving ML](#privacy-preserving-ml)
- [Governance and Policy](#governance-and-policy)

### Index
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

#  Glossary A–F

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

---

# 🧬 Deep Learning

---

## Neural Network Fundamentals

**The Perceptron**
The simplest neural unit (Rosenblatt, 1958): `output = sign(wᵀx + b)`. Can only learn linearly separable problems. Limitation discovered by Minsky & Papert (1969) — led to the first AI winter.

**Multi-Layer Perceptron (MLP)**
Stack of layers with non-linear activations. Universal approximation theorem (Hornik, 1989): an MLP with one hidden layer and enough neurons can approximate any continuous function on a compact domain. Doesn't say how many neurons or how to find them.

**Forward Pass**
```
Input x
→ Layer 1: h₁ = activation(W₁x + b₁)
→ Layer 2: h₂ = activation(W₂h₁ + b₂)
→ ...
→ Output: ŷ = W_n × h_{n-1} + b_n
```

**Backpropagation in Detail**
1. Forward pass: compute activations at each layer, cache them
2. Compute loss: `L = loss(ŷ, y)`
3. Backward pass: compute `∂L/∂W_n`, then propagate backward using chain rule
4. Update: `W_i ← W_i - η × ∂L/∂W_i`

Key identity: `∂L/∂W_i = ∂L/∂h_i × ∂h_i/∂W_i` (chain rule applied recursively)

**Weight Initialization**

| Method | Formula | For |
|---|---|---|
| Xavier/Glorot | `U(-√(6/(nᵢₙ+nₒᵤₜ)), √(6/(nᵢₙ+nₒᵤₜ)))` | Sigmoid, Tanh |
| He/Kaiming | `N(0, √(2/nᵢₙ))` | ReLU, Leaky ReLU |
| Orthogonal | Random orthogonal matrix | RNNs |
| Zero init | 0 | Biases only — never weights |

⚠️ Never initialize all weights to zero — symmetry breaking fails; all neurons learn the same thing.

**Skip / Residual Connections**
`F(x) + x` — the output of a block is added to its input. Enables gradients to flow directly through the identity shortcut, alleviating vanishing gradients in very deep networks. Introduced in ResNet (He et al., 2015). Now standard in virtually all architectures.

**Depth vs. Width**
- **Depth** (more layers): learns hierarchical representations, more computationally efficient for complex functions. Harder to train (vanishing gradients, but mitigated by ResNets).
- **Width** (more neurons per layer): more capacity per layer, easier to optimize, but less efficient parameter usage for hierarchical patterns.
- EfficientNet (Tan & Le, 2019): compound scaling of depth, width, AND resolution for balanced improvement.

**Universal Approximation Theorem (Extended)**
Deep networks can approximate functions exponentially more efficiently (in terms of neurons) than shallow networks for many function classes — justifying the pursuit of depth.

**Autoencoder Architecture**
```
Input → Encoder → Bottleneck (Latent Space) → Decoder → Reconstruction
```
Applications: dimensionality reduction, denoising, anomaly detection (high reconstruction error = anomaly), generative modeling (VAE).

### Resources
- 🎓 [CS231n: CNNs for Visual Recognition (Stanford)](http://cs231n.stanford.edu/) ⭐
- 🎓 [fast.ai Practical Deep Learning](https://course.fast.ai/) ⭐
- 📚 [Deep Learning Book — Goodfellow, Bengio, Courville (free)](https://www.deeplearningbook.org/)
- 🐙 [micrograd — Karpathy's minimal autograd engine](https://github.com/karpathy/micrograd) ⭐

---

## Activation Functions

| Function | Formula | Range | Properties |
|---|---|---|---|
| **Sigmoid** | `1/(1+e⁻ˣ)` | (0,1) | Saturates, vanishing gradient, output not zero-centered |
| **Tanh** | `(eˣ-e⁻ˣ)/(eˣ+e⁻ˣ)` | (-1,1) | Zero-centered, still saturates |
| **ReLU** | `max(0,x)` | [0,∞) | No saturation for x>0, dead neurons possible |
| **Leaky ReLU** | `max(αx,x)` | (-∞,∞) | Prevents dying neurons, α typically 0.01 |
| **ELU** | `x if x>0, α(eˣ-1) if x≤0` | (-α,∞) | Smooth negative region, mean activations near zero |
| **GELU** | `x × Φ(x)` | (-0.17,∞) | Smooth, stochastic interpretation, used in Transformers |
| **Swish** | `x × σ(βx)` | ≈(-0.28,∞) | Google Brain, slightly outperforms ReLU in deep nets |
| **Mish** | `x × tanh(softplus(x))` | ≈(-0.31,∞) | Self-regularizing, used in YOLOv4 |
| **Softmax** | `exp(zᵢ)/Σexp(zⱼ)` | (0,1), sums to 1 | Multi-class output layer |
| **SiLU (Swish-1)** | `x × σ(x)` | Same as Swish β=1 | Used in LLaMA, Mistral |
| **SwiGLU** | `Swish(xW) ⊙ (xV)` | — | Gated variant, used in PaLM, LLaMA |
| **GLU (Gated Linear Unit)** | `(xW) ⊙ σ(xV)` | — | Gating mechanism, used in WaveNet, ConvSeq2Seq |

**Choosing an Activation Function**
- Default for hidden layers: **GELU** (Transformers) or **ReLU** (CNNs/MLPs)
- Output for binary classification: **Sigmoid**
- Output for multiclass: **Softmax**
- Output for regression: **Linear** (no activation)
- When you see dying ReLU issues: try **Leaky ReLU** or **ELU**

**Dying ReLU Problem**
A neuron that always outputs 0 (because its incoming weights produce negative pre-activations for all training inputs) receives zero gradient and can never recover. Prevented by: careful initialization, leaky ReLU, batch normalization, smaller learning rates.

---

## Loss Functions

### Classification Losses

**Binary Cross-Entropy (BCE)**
`L = -[y log(p) + (1-y) log(1-p)]`
For binary classification. p = sigmoid output. Numerically stable implementation: `BCEWithLogitsLoss` in PyTorch (combines sigmoid + BCE for stability).

**Categorical Cross-Entropy**
`L = -Σᵢ yᵢ log(pᵢ)`
For multi-class classification. yᵢ is the one-hot label, pᵢ is the softmax probability.

**Focal Loss**
`FL = -αₜ(1-pₜ)ᵞ log(pₜ)`
γ (focus parameter, typically 2) down-weights easy examples. αₜ handles class imbalance. Proposed for RetinaNet object detection. Excellent for highly imbalanced datasets.

**Hinge Loss**
`L = max(0, 1 - y × ŷ)` (y ∈ {-1, +1})
Used in SVMs. Penalizes predictions on the wrong side of the margin. Squared hinge loss is smoother.

**Label Smoothing Cross-Entropy**
Replace one-hot targets with: `y_smooth = (1-ε) × y + ε/K`
Prevents overconfident predictions. Typically ε = 0.1. Improves calibration and generalization. Standard in image classification (EfficientNet, ViT).

### Regression Losses

**Mean Squared Error (MSE / L2 Loss)**
`L = (1/n) Σ(yᵢ - ŷᵢ)²`
Sensitive to outliers. Squared term amplifies large errors. Penalizes outliers heavily.

**Mean Absolute Error (MAE / L1 Loss)**
`L = (1/n) Σ|yᵢ - ŷᵢ|`
Robust to outliers. Non-differentiable at 0 (use subgradient or smooth approximation). Better when outliers are expected.

**Huber Loss**
`L_δ(a) = 0.5a² if |a|≤δ, δ(|a| - 0.5δ) otherwise`
Combines MSE (small errors) and MAE (large errors). Robust to outliers while remaining differentiable. Common in RL (DQN) and object detection (bounding box regression).

**Log-Cosh Loss**
`L = Σ log(cosh(ŷᵢ - yᵢ))`
Approximately MSE for small errors, MAE for large errors. Doubly differentiable everywhere — can use second-order optimization.

### Generative Losses

**Reconstruction Loss (Autoencoders)**
MSE for continuous data: `||x - x̂||²`
BCE for binary data: `BCE(x, x̂)`
Measures how well the decoder reconstructs the input.

**Adversarial Loss (GANs)**
Original: minimax `min_G max_D [E[log D(x)] + E[log(1-D(G(z)))]]`
Non-saturating: `min_G -E[log D(G(z))]`
WGAN: Wasserstein distance — more stable, requires Lipschitz constraint.

**Triplet Loss**
`L = max(0, ||f(a) - f(p)||² - ||f(a) - f(n)||² + margin)`
For metric learning: anchor a, positive p, negative n. Pulls positive pairs together, pushes negative pairs apart. Used in face recognition (FaceNet), image retrieval.

**Contrastive Loss (NT-Xent)**
InfoNCE / NT-Xent (Normalized Temperature Cross-Entropy): for SimCLR and CLIP.
`L = -log[exp(sim(zᵢ,zⱼ)/τ) / Σ_{k≠i} exp(sim(zᵢ,zₖ)/τ)]`
Temperature τ controls sharpness of distribution.

### Sequence Losses

**CTC Loss (Connectionist Temporal Classification)**
For sequence-to-sequence where alignment is unknown (e.g., speech recognition). Sums over all valid alignments. Enables training without frame-level annotations.

**Sequence-to-Sequence Cross-Entropy**
Standard cross-entropy applied at each output step, summed or averaged over the sequence. Teacher forcing used during training.

---

## Optimizers

**Vanilla SGD**
`θ ← θ - η × ∇L(θ; xᵢ, yᵢ)`
Simple but effective with proper tuning. Requires careful learning rate scheduling.

**SGD with Momentum**
```
v ← βv - η∇L
θ ← θ + v
```
Typical β = 0.9. Accelerates in consistent gradient directions, dampens oscillations. Combined with learning rate schedules, matches or beats Adam for CNNs.

**AdaGrad**
Per-parameter adaptive learning rates: `θᵢ ← θᵢ - (η/√(Gᵢᵢ + ε)) × ∇L_i`
Accumulates squared gradients. Effective for sparse features but learning rate decays to zero (problem for long training).

**RMSprop**
Exponential moving average of squared gradients: `E[g²]_t = ρE[g²]_{t-1} + (1-ρ)g²_t`
Fixes AdaGrad's decaying learning rate. Proposed by Hinton in his Coursera course (not a paper!).

**Adam (Adaptive Moment Estimation)**
Combines momentum (first moment) and RMSprop (second moment):
```
m_t = β₁m_{t-1} + (1-β₁)g_t          (first moment)
v_t = β₂v_{t-1} + (1-β₂)g²_t         (second moment)
m̂_t = m_t/(1-β₁ᵗ)                    (bias correction)
v̂_t = v_t/(1-β₂ᵗ)                    (bias correction)
θ_t = θ_{t-1} - η × m̂_t/(√v̂_t + ε)
```
Defaults: β₁=0.9, β₂=0.999, ε=1e-8. Most widely used optimizer. 📄 [Paper: Kingma & Ba, 2014](https://arxiv.org/abs/1412.6980)

**AdamW**
Adam with decoupled weight decay: weight decay applied directly to parameters, not through the gradient update. Fixes L2 regularization in Adam (which doesn't work correctly). Recommended over Adam for Transformers. 📄 [Paper: Loshchilov & Hutter, 2017](https://arxiv.org/abs/1711.05101)

**LAMB (Layer-wise Adaptive Moments)**
Extends Adam with layer-wise learning rate scaling. Enables training with very large batch sizes (used to train BERT in 77 minutes). 📄 [Paper](https://arxiv.org/abs/1904.00962)

**Sophia**
Second-order optimizer using a diagonal Hessian estimate (Hutchinson estimator). ~2× faster than Adam for LLM pre-training. 📄 [Paper: Liu et al., 2023](https://arxiv.org/abs/2305.14342)

**Lion (EvoLved Sign Momentum)**
Discovered via program search. Uses only the sign of the gradient update. More memory-efficient than Adam (stores only one moving average). 📄 [Paper: Chen et al., 2023](https://arxiv.org/abs/2302.06675)

**Optimizer Selection Guide**
- CNNs, ResNets: SGD with momentum + cosine LR schedule
- Transformers (NLP, ViT): AdamW + linear warmup + cosine decay
- GANs: Adam (separate lr for G and D)
- Fine-tuning LLMs: AdamW with low lr (1e-5 to 5e-5)
- Large batch training: LAMB

---

## Convolutional Neural Networks

**Convolution Operation**
`(f * g)(t) = Σ f(τ) g(t - τ)`
In 2D (images): `(I * K)(i,j) = Σₘ Σₙ I(i+m, j+n) K(m,n)`
Each filter slides over the input and computes dot products. Multiple filters → multiple feature maps → depth of next layer = number of filters.

**Key Hyperparameters**
- **Kernel size**: 3×3 (standard), 5×5, 7×7, 1×1 (channel mixing)
- **Stride**: step size (stride=2 halves spatial dimensions)
- **Padding**: SAME (preserve spatial dims), VALID (no padding)
- **Number of filters**: controls depth of output feature map
- **Groups**: grouped convolution (separates input channels into groups)

**Output Spatial Dimensions**
`H_out = floor((H_in + 2×padding - kernel_size) / stride) + 1`

**1×1 Convolution**
Applies a fully connected layer independently at each spatial position. Used to: change number of channels (increase or decrease), add non-linearity without changing spatial dimensions, in Inception modules and bottleneck blocks.

**Receptive Field Growth**
Each layer has a local receptive field. After k layers with 3×3 kernels and stride 1: receptive field = 2k+1. Dilated convolutions expand the receptive field exponentially without adding parameters.

**Dilated (Atrous) Convolution**
Inserts gaps (dilation rate d) between kernel elements. Effective kernel size: `k + (k-1)(d-1)`. Exponentially growing receptive field with fixed parameters. Used in WaveNet, DeepLab, and semantic segmentation.

**Depthwise Separable Convolution (DSC)**
Factorizes a standard convolution into:
1. Depthwise: apply one filter per input channel
2. Pointwise: 1×1 conv to mix channels
Cost reduction: `1/Nf + 1/Dₖ²` vs. standard convolution (where Nf = num filters, Dₖ = kernel size).
Used in MobileNet, Xception.

### CNN Architectures Timeline

**LeNet-5** (LeCun, 1998)
First practical CNN for digit recognition. Established the conv→pool→fc pattern.
🐙 [Original Paper](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)

**AlexNet** (Krizhevsky, 2012)
Won ImageNet 2012 with 15.3% top-5 error (vs 26.2% runner-up). Used: ReLU, Dropout, data augmentation, multi-GPU. Launched the deep learning era.
📄 [Paper](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)

**VGGNet** (Simonyan, 2014)
Deep, simple architecture using only 3×3 convolutions. VGG-16 and VGG-19. Showed depth matters. Widely used as a feature extractor backbone.
📄 [Paper](https://arxiv.org/abs/1409.1556)

**GoogLeNet / Inception** (Szegedy, 2014)
Inception modules: parallel 1×1, 3×3, 5×5 convolutions + max pooling. 22 layers with fewer parameters than AlexNet. Introduced global average pooling instead of FC layers.
📄 [Paper](https://arxiv.org/abs/1409.4842)

**ResNet** (He, 2015)
Residual connections: `y = F(x) + x`. Trained networks of 50, 101, 152 layers. Won ImageNet 2015. The most influential CNN architecture.
📄 [Paper](https://arxiv.org/abs/1512.03385) 🐙 [Torchvision implementation](https://github.com/pytorch/vision)

**DenseNet** (Huang, 2017)
Each layer connects to all subsequent layers: `xₗ = Hₗ([x₀, x₁, ..., x_{l-1}])`. Maximum gradient flow, feature reuse. More parameter-efficient than ResNet.
📄 [Paper](https://arxiv.org/abs/1608.06993)

**MobileNetV2** (Sandler, 2018)
Depthwise separable convolutions + inverted residuals + linear bottlenecks. Designed for mobile/edge devices. Excellent accuracy/efficiency trade-off.
📄 [Paper](https://arxiv.org/abs/1801.04381)

**EfficientNet** (Tan & Le, 2019)
Neural Architecture Search to find base architecture, then compound scaling (depth × width × resolution). EfficientNetB7 achieved SotA on ImageNet with 8× fewer parameters than previous best.
📄 [Paper](https://arxiv.org/abs/1905.11946)

**ConvNeXt** (Liu, 2022)
A "modernized" ResNet incorporating Transformer design choices: larger kernels (7×7), fewer activations, LayerNorm instead of BatchNorm, inverted bottleneck. Competitive with ViT without self-attention.
📄 [Paper](https://arxiv.org/abs/2201.03545)

### Pooling Operations
- **Max Pooling**: take maximum in each region. Preserves most prominent features. Most common.
- **Average Pooling**: take mean. Smoother, used in classification heads.
- **Global Average Pooling (GAP)**: average across entire spatial dimension to a vector. Replaces FC layers.
- **Adaptive Pooling**: output a fixed size regardless of input size. Used in PyTorch for flexible input sizes.

### Normalization in CNNs
- **BatchNorm**: normalizes over batch dimension and spatial dimensions. Standard for CNNs. Requires reasonably large batches.
- **GroupNorm**: normalizes within groups of channels. Better for small batches (detection, segmentation).
- **LayerNorm**: normalizes over all features of one sample. Standard for Transformers.
- **InstanceNorm**: normalizes per sample per channel. Used in style transfer.

---

## Recurrent Neural Networks

**Vanilla RNN**
`h_t = tanh(W_h × h_{t-1} + W_x × x_t + b)`
`y_t = W_y × h_t + b_y`
Hidden state h_t summarizes all previous inputs. Suffers catastrophically from vanishing gradients for sequences longer than ~20 steps.

**Vanishing Gradient in RNNs**
Gradient at step t: `∂L/∂h₁ = ∏_{t=2}^{T} ∂h_t/∂h_{t-1}`. If `||∂h_t/∂h_{t-1}|| < 1`, this product → 0 exponentially. Means early inputs have essentially no influence on the loss. LSTM/GRU solve this with gating.

**LSTM (Long Short-Term Memory)**
Hochreiter & Schmidhuber (1997). Gates:
```
f_t = σ(W_f [h_{t-1}, x_t] + b_f)          # forget gate
i_t = σ(W_i [h_{t-1}, x_t] + b_i)          # input gate
g_t = tanh(W_g [h_{t-1}, x_t] + b_g)       # candidate cell
o_t = σ(W_o [h_{t-1}, x_t] + b_o)          # output gate
c_t = f_t ⊙ c_{t-1} + i_t ⊙ g_t           # cell state update
h_t = o_t ⊙ tanh(c_t)                       # hidden state
```
Cell state c_t is the "long-term memory" — gradients can flow through it unchanged via the forget gate.

**GRU (Gated Recurrent Unit)**
Cho et al. (2014). Simpler than LSTM (fewer parameters, one fewer gate):
```
z_t = σ(W_z [h_{t-1}, x_t])                # update gate
r_t = σ(W_r [h_{t-1}, x_t])                # reset gate
h̃_t = tanh(W [r_t ⊙ h_{t-1}, x_t])       # candidate hidden
h_t = (1-z_t) ⊙ h_{t-1} + z_t ⊙ h̃_t    # new hidden state
```
Similar performance to LSTM in practice. Often preferred for efficiency.

**Bidirectional RNN**
Processes the sequence in both forward and backward directions, concatenating the hidden states. Captures context from both past and future. Used in BERT-like models (but replaced by bidirectional attention in Transformers).

**Deep RNN**
Stacking multiple RNN layers: output of one layer is input to the next. Learns hierarchical temporal representations. Common in seq2seq models.

**Seq2Seq with Attention**
Encoder RNN encodes source sequence to context vector. Decoder RNN generates target sequence token by token. Original attention (Bahdanau, 2015): decoder attends to all encoder hidden states at each decoding step, computing a context-weighted average. Breakthrough for long sequences. Foundation of the Transformer.
📄 [Bahdanau Attention Paper](https://arxiv.org/abs/1409.0473)

**When to Use RNNs vs. Transformers**
- Transformers are now preferred for most sequence tasks
- RNNs still relevant for: very long sequences (linear vs quadratic memory), streaming/online inference, edge devices with constrained memory
- SSMs (Mamba, S4) are a modern alternative combining aspects of both

---

## Attention and Transformers

**Scaled Dot-Product Attention**
`Attention(Q, K, V) = softmax(QKᵀ/√d_k) V`

- Q (queries), K (keys), V (values): linear projections of input
- Scaling by `√d_k` prevents vanishing gradients from large dot products
- Attention weights: each query attends to all keys, producing a weighted sum of values
- O(n²d) computation, O(n²) memory for sequence length n

**Multi-Head Attention**
```
head_i = Attention(QW_i^Q, KW_i^K, VW_i^V)
MultiHead(Q,K,V) = Concat(head₁, ..., headₕ) W^O
```
Each head learns different attention patterns. Typical: h=8 or h=16 heads with d_k = d_model/h. Different heads: local vs. global attention, syntactic vs. semantic, etc.

**Self-Attention vs. Cross-Attention**
- **Self-attention**: Q, K, V all from the same sequence (encoder or decoder self-attention)
- **Cross-attention**: Q from decoder, K and V from encoder. Allows decoder to attend to encoder representations.

**The Transformer Architecture (Vaswani et al., 2017)**
```
Encoder:
  Input Embeddings + Positional Encoding
  → N × (Multi-Head Self-Attention → Add&Norm → Feed-Forward → Add&Norm)

Decoder:
  Output Embeddings + Positional Encoding
  → N × (Masked Self-Attention → Add&Norm
         → Cross-Attention → Add&Norm
         → Feed-Forward → Add&Norm)

Output: Linear → Softmax
```
📄 [Attention Is All You Need](https://arxiv.org/abs/1706.03762) ⭐

**Position Encoding**
Transformers have no inherent notion of order — position must be injected.
- **Sinusoidal** (original): `PE(pos, 2i) = sin(pos/10000^(2i/d))`, `PE(pos, 2i+1) = cos(...)`. Deterministic, generalizes to longer sequences.
- **Learned absolute**: trainable embeddings for each position. Common in BERT, GPT.
- **Relative position** (Shaw et al.): encode relative distances between positions. Better length generalization.
- **RoPE** (Su et al., 2021): rotate Q and K vectors based on absolute position. Used in LLaMA, Mistral. Excellent length extrapolation.
- **ALiBi** (Press et al., 2021): add position-dependent bias to attention scores. Simple, good length extrapolation.

**Feed-Forward Network in Transformer**
`FFN(x) = max(0, xW₁ + b₁)W₂ + b₂`
Two linear layers with a non-linearity (ReLU or GELU). Applied independently to each position. Often called the "MLP sublayer." Typically d_ff = 4 × d_model. Contains ~2/3 of all Transformer parameters.

**Layer Norm Placement**
- **Post-LN** (original): `LayerNorm(x + Sublayer(x))`. Original paper. Unstable at large scale.
- **Pre-LN**: `x + Sublayer(LayerNorm(x))`. More stable training. Used in GPT-2, GPT-3.
- **RMSNorm**: simplified LayerNorm (no mean subtraction). Used in LLaMA, T5.

**Encoder-Only Transformers (BERT-style)**
- Bidirectional self-attention: each token attends to all others
- Pre-training: Masked Language Modeling + NSP
- Good for: classification, NER, QA, sentence embeddings
- Examples: BERT, RoBERTa, DeBERTa, ALBERT

**Decoder-Only Transformers (GPT-style)**
- Causal (masked) self-attention: each token only attends to previous tokens
- Pre-training: next token prediction (autoregressive language modeling)
- Good for: text generation, instruction following, reasoning
- Examples: GPT-2/3/4, LLaMA, Mistral, Claude, Gemini

**Encoder-Decoder Transformers (T5/BART-style)**
- Encoder: bidirectional processing of input
- Decoder: autoregressive generation, cross-attends to encoder
- Good for: translation, summarization, structured generation
- Examples: T5, BART, mT5, Flan-T5

**Efficient Attention Mechanisms**

| Method | Complexity | Key Idea |
|---|---|---|
| Standard Attention | O(n²) | All pairs |
| Sparse Attention | O(n√n) | Local + global patterns |
| Longformer | O(n) | Sliding window + global tokens |
| BigBird | O(n) | Random + window + global |
| Linformer | O(n) | Low-rank approximation of attention |
| Performer | O(n) | Random feature approximation |
| FlashAttention | O(n²) | Exact, but IO-efficient on GPU |
| FlashAttention-2 | O(n²) | Better parallelism, 2× faster |
| FlashAttention-3 | O(n²) | H100 optimized |

🐙 [FlashAttention](https://github.com/Dao-AILab/flash-attention) ⭐

**Vision Transformer (ViT)**
Split image into 16×16 patches → linearly embed each patch → prepend [CLS] token → standard Transformer encoder. Pre-training on ImageNet-21k or JFT-300M required for good performance (inductive biases of CNNs removed). Strong at scale.
📄 [Paper: Dosovitskiy et al., 2020](https://arxiv.org/abs/2010.11929)

**Swin Transformer**
Shifted window attention: restricts self-attention to local windows, shifts windows between layers for cross-window connections. Linear complexity with image size. State-of-the-art on detection/segmentation.
📄 [Paper](https://arxiv.org/abs/2103.14030) 🐙 [Repo](https://github.com/microsoft/Swin-Transformer)

**Key Transformer Repos**
- 🐙 [Hugging Face Transformers](https://github.com/huggingface/transformers) ⭐ — unified API for 200+ models
- 🐙 [nanoGPT — Karpathy](https://github.com/karpathy/nanoGPT) ⭐ — minimal GPT implementation
- 🐙 [LLaMA — Meta](https://github.com/meta-llama/llama)
- 🐙 [Mistral](https://github.com/mistralai/mistral-src)
- 🐙 [GPT-NeoX — EleutherAI](https://github.com/EleutherAI/gpt-neox)

---

## Graph Neural Networks

**Graph Representation**
A graph G = (V, E) with node features X ∈ ℝ^(|V|×d) and adjacency matrix A ∈ {0,1}^(|V|×|V|). GNNs learn node, edge, or graph-level representations via message passing.

**Message Passing Framework**
```
m_v^(k) = AGGREGATE({h_u^(k-1) : u ∈ N(v)})
h_v^(k) = UPDATE(h_v^(k-1), m_v^(k))
```
After K rounds: h_v^(K) summarizes the K-hop neighborhood of v.

**Graph Convolutional Network (GCN)**
Kipf & Welling (2017): `H^(l+1) = σ(D̂^(-1/2) Â D̂^(-1/2) H^(l) W^(l))`
Where Â = A + I (self-loops), D̂ is the degree matrix. Symmetric normalization. Simple, effective, widely used.
📄 [Paper](https://arxiv.org/abs/1609.02907)

**Graph Attention Network (GAT)**
Uses attention to weight neighbor messages: `h_v = σ(Σ_{u∈N(v)} α_{vu} W h_u)`
α_{vu} = attention coefficients learned by a small neural network. Allows the model to weight important neighbors more.
📄 [Paper: Veličković et al., 2018](https://arxiv.org/abs/1710.10903)

**GraphSAGE**
Hamilton et al. (2017). Inductive learning on graphs (generalizes to unseen nodes). Samples a fixed-size neighborhood and aggregates (mean, LSTM, max).
📄 [Paper](https://arxiv.org/abs/1706.02216)

**Graph Isomorphism Network (GIN)**
Xu et al. (2019). Provably most expressive GNN within the Weisfeiler-Leman framework:
`h_v^(k) = MLP^(k)((1 + ε^(k)) h_v^(k-1) + Σ_{u∈N(v)} h_u^(k-1))`
📄 [Paper](https://arxiv.org/abs/1810.00826)

**Applications**
- Molecular property prediction (drug discovery, materials science)
- Protein structure prediction (AlphaFold uses attention over residue graph)
- Social network analysis
- Knowledge graph completion
- Recommender systems
- Traffic forecasting
- Fraud detection

**GNN Libraries**
-  [PyTorch Geometric (PyG)](https://github.com/pyg-team/pytorch_geometric) ⭐
-  [DGL (Deep Graph Library)](https://github.com/dmlc/dgl)
-  [Spektral (Keras/TF)](https://github.com/danielegrattarola/spektral)

---

---

## Generative Adversarial Networks

**GAN Framework**
Two-player minimax game (Goodfellow et al., 2014):
`min_G max_D E_{x~p_data}[log D(x)] + E_{z~p_z}[log(1 - D(G(z)))]`

- **Generator G**: maps noise z → fake samples. Goal: fool the discriminator.
- **Discriminator D**: distinguishes real from fake. Goal: correctly classify real vs. generated.
- Nash equilibrium: G generates samples indistinguishable from real data.

📄 [Original GAN Paper](https://arxiv.org/abs/1406.2661)

**GAN Training Challenges**
- **Mode collapse**: G produces a limited variety of outputs (collapses to subset of modes)
- **Training instability**: loss oscillates; D and G must be balanced
- **Vanishing gradient**: when D is too good, G receives near-zero gradients
- **Checkerboard artifacts**: from transposed convolutions — use resize+conv instead

**Non-Saturating Loss (Practical)**
Instead of `log(1 - D(G(z)))`, minimize `-log(D(G(z)))`.
Provides stronger gradients early in training when D is confident about rejecting fakes.

**Key GAN Architectures**

| Model | Year | Key Innovation |
|---|---|---|
| DCGAN | 2015 | Convolutional GAN, stable training guidelines |
| Pix2Pix | 2017 | Conditional GAN for image-to-image translation |
| CycleGAN | 2017 | Unpaired image-to-image translation (cycle consistency) |
| ProGAN | 2018 | Progressive growing — start small, add layers |
| StyleGAN | 2019 | Style-based generator, AdaIN, mapping network |
| StyleGAN2/3 | 2020/21 | Fixes artifacts, alias-free generation |
| BigGAN | 2019 | Large-scale class-conditional generation |
| WGAN | 2017 | Wasserstein distance, more stable training |
| WGAN-GP | 2017 | Gradient penalty instead of weight clipping |
| SNGAN | 2018 | Spectral normalization for D stability |

**WGAN (Wasserstein GAN)**
Uses Earth Mover (Wasserstein-1) distance instead of JS divergence.
`min_G max_{D∈1-Lip} E[D(x)] - E[D(G(z))]`
D must be 1-Lipschitz (enforced by weight clipping in WGAN, gradient penalty in WGAN-GP). More stable training, meaningful loss curve (lower = better). 📄 [Paper](https://arxiv.org/abs/1701.07875)

**StyleGAN / StyleGAN2**
Mapping network f: z → w (intermediate latent space W). Synthesis network controlled by w via AdaIN (Adaptive Instance Normalization) at each layer. Per-channel noise for stochastic variation. Style mixing regularization.
📄 [StyleGAN2 Paper](https://arxiv.org/abs/1912.04958) 🐙 [Repo](https://github.com/NVlabs/stylegan2-ada-pytorch)

**Conditional GAN (cGAN)**
Conditioning both G and D on additional information (class label, image, text):
`G(z, c) → fake_x; D(x, c) → real/fake`
Enables controllable generation. Foundation of Pix2Pix, text-to-image GANs.

**GAN Evaluation Metrics**
- **FID (Fréchet Inception Distance)**: compares distribution of real and generated images using Inception features. Lower is better. Standard metric for image generation.
- **IS (Inception Score)**: measures quality (sharp predictions) and diversity. Higher is better. Less reliable than FID.
- **Precision and Recall**: separate measures of sample quality and coverage.
- **LPIPS**: perceptual similarity using VGG features.

**GAN Repos**
- 🐙 [StyleGAN2-ADA (NVIDIA)](https://github.com/NVlabs/stylegan2-ada-pytorch)
- 🐙 [GAN Zoo](https://github.com/hindupuravinash/the-gan-zoo)
- 🐙 [PyTorch-GAN](https://github.com/eriklindernoren/PyTorch-GAN)

---

## Variational Autoencoders

**Motivation**
Regular autoencoders learn a deterministic mapping to latent space. Latent space may have "holes" — sampling random points produces garbage. VAEs learn a structured, continuous latent space suitable for generation.

**VAE Framework (Kingma & Welling, 2013)**
- Encoder: `q_φ(z|x)` — approximates true posterior `p(z|x)`, outputs μ and σ (Gaussian)
- Decoder: `p_θ(x|z)` — generates x from latent code z
- Prior: `p(z) = N(0, I)`

**ELBO (Training Objective)**
`L = E_{q_φ(z|x)}[log p_θ(x|z)] - KL(q_φ(z|x) || p(z))`
= **Reconstruction term** + **KL regularization term**

The KL term forces the approximate posterior to stay close to the prior N(0,I), ensuring the latent space is smooth and well-structured.
📄 [Original Paper](https://arxiv.org/abs/1312.6114)

**Reparameterization Trick**
Sampling `z ~ q_φ(z|x) = N(μ, σ²)` is not differentiable.
Reparameterize: `z = μ + σ ⊙ ε` where `ε ~ N(0,I)`.
Now gradient flows through μ and σ, enabling backpropagation through the sampling operation.

**β-VAE**
`L = E[log p(x|z)] - β × KL(q(z|x)||p(z))`
β > 1 encourages more disentangled representations by imposing stronger independence constraint. Trade-off: higher β → better disentanglement, worse reconstruction quality.
📄 [Paper: Higgins et al., 2017](https://openreview.net/forum?id=Sy2fchEll)

**VQ-VAE (Vector Quantized VAE)**
Discrete latent space: instead of continuous z, latent codes are vectors from a learned codebook.
Encoder output is quantized to nearest codebook vector. Trained with straight-through estimator.
Foundation of DALL-E (v1), AudioCodec, and many modern video/image tokenizers.
📄 [Paper: van den Oord et al., 2017](https://arxiv.org/abs/1711.00937)

**VAE Applications**
- Image generation with interpolation
- Drug/molecule design (molecular VAEs)
- Anomaly detection (high reconstruction error + KL)
- Latent space arithmetic: encode two faces, interpolate z → smooth transition
- Disentangled representation learning

---

## Diffusion Models

**Core Idea**
Learn to reverse a gradual noising process. Training: add Gaussian noise to data in T steps. Inference: start from pure noise and denoise step-by-step to generate samples.

**Forward Process (Fixed)**
`q(x_t | x_{t-1}) = N(x_t; √(1-β_t) x_{t-1}, β_t I)`
`q(x_t | x_0) = N(x_t; √ᾱ_t x_0, (1-ᾱ_t) I)` (closed form!)
where `ᾱ_t = Π_{s=1}^{t} (1-β_s)`.
No parameters — just progressively adds noise until x_T ≈ N(0,I).

**Reverse Process (Learned)**
`p_θ(x_{t-1} | x_t) = N(x_{t-1}; μ_θ(x_t, t), Σ_θ(x_t, t))`
A neural network (typically U-Net) is trained to predict either the noise ε, the denoised x_0, or the score ∇ log p(x_t).

**DDPM (Denoising Diffusion Probabilistic Models)**
Ho et al. (2020). The landmark paper establishing modern diffusion models. Simple noise prediction objective: `L = E[||ε - ε_θ(x_t, t)||²]`. T=1000 steps.
📄 [Paper](https://arxiv.org/abs/2006.11239) 🐙 [Repo](https://github.com/hojonathanho/diffusion)

**DDIM (Denoising Diffusion Implicit Models)**
Song et al. (2020). Deterministic (or semi-deterministic) sampling that allows large step skips. Enables 10–50 step generation (vs. 1000 in DDPM) with minimal quality loss. Key for practical inference speed.
📄 [Paper](https://arxiv.org/abs/2010.02502)

**Score-Based Generative Models**
Song & Ermon (2020). Equivalent view: learn the score function `∇_x log p(x)` via denoising score matching. Generate via Langevin dynamics. Unifies diffusion models and score matching under a continuous-time SDE framework.
📄 [Score SDE Paper](https://arxiv.org/abs/2011.13456)

**Latent Diffusion Models (LDM)**
Rombach et al. (2022). Run the diffusion process in the latent space of a pre-trained VQ-VAE encoder rather than in pixel space. Massive compute reduction. Foundation of Stable Diffusion.
📄 [Paper](https://arxiv.org/abs/2112.10752)

**Classifier-Free Guidance (CFG)**
Ho & Salimans (2022). Train both conditional `p(x|c)` and unconditional `p(x)` models (by randomly dropping conditions during training). At inference, combine: `ε̃ = ε_uncond + w(ε_cond - ε_uncond)`. Higher w → more condition-adherent, less diverse. Standard in all modern text-to-image models.
📄 [Paper](https://arxiv.org/abs/2207.12598)

**Stable Diffusion**
Open-source latent diffusion model by Stability AI. Text encoder: CLIP. Latent space: VQ-VAE. Denoiser: U-Net conditioned on text via cross-attention. Trained on LAION-5B.
🐙 [Stable Diffusion](https://github.com/CompVis/stable-diffusion)
🐙 [Diffusers (Hugging Face)](https://github.com/huggingface/diffusers) ⭐

**DALL-E 2 / DALL-E 3**
OpenAI text-to-image models. DALL-E 2: hierarchical generation via CLIP embeddings. DALL-E 3: tightly integrated with ChatGPT for richer text understanding. Native text rendering improvements.

**Imagen**
Google's text-to-image diffusion model. Frozen large T5 text encoder (key finding: text encoder quality matters more than image encoder). Cascaded diffusion: generate 64×64 then super-resolve.
📄 [Paper](https://arxiv.org/abs/2205.11487)

**DiT (Diffusion Transformer)**
Peebles & Xie (2023). Replaces the U-Net denoiser with a Transformer. Scales better with compute than U-Net. Foundation of Sora's architecture.
📄 [Paper](https://arxiv.org/abs/2212.09748)

**Flow Matching**
Lipman et al. (2022). Simpler training objective than DDPM: directly regress vector fields of probability flow ODEs. Faster training and inference. Used in Stable Diffusion 3, Meta Voicebox, and many recent models.
📄 [Paper](https://arxiv.org/abs/2210.02747)

**Key Diffusion Applications**
- Text-to-image: DALL-E 3, Stable Diffusion, Midjourney, Imagen
- Video generation: Sora, Gen-2, Stable Video Diffusion
- Audio: AudioLDM, Stable Audio, MusicGen
- 3D: DreamFusion, Zero-1-to-3
- Protein structure: RFDiffusion
- Drug discovery: DiffSBDD

---

## Normalizing Flows

**Concept**
Transforms a simple distribution (e.g., Gaussian) into a complex one via a series of invertible, differentiable transformations. Exact likelihood computation possible via change of variables:
`log p_X(x) = log p_Z(f⁻¹(x)) + log|det J_{f⁻¹}(x)|`

**Key Requirement**: transformations must be invertible with tractable Jacobian determinant.

**NICE (Non-linear Independent Components Estimation)**
Dinh et al. (2014). Coupling layers: split x into two halves; one half transformed using a function of the other. Triangular Jacobian → efficient determinant computation.

**RealNVP**
Dinh et al. (2017). Extended NICE with affine coupling layers and multi-scale architecture. Demonstrated high-quality image generation with exact likelihood.
📄 [Paper](https://arxiv.org/abs/1605.08803)

**Glow**
Kingma & Dhariwal (2018). Added 1×1 invertible convolutions for better expressiveness. Enabled photorealistic face generation and smooth latent space interpolation.
📄 [Paper](https://arxiv.org/abs/1807.03039)

**Neural Autoregressive Flows**
Coupling the expressiveness of autoregressive models with invertibility. Slow sampling (one dimension at a time) but fast density evaluation.

**Applications of Flows**
- Exact likelihood estimation (anomaly detection)
- Variational inference (more expressive posteriors)
- Latent variable models
- Molecular conformation generation (Boltzmann generators)

---

## Neural Architecture Search

**Motivation**
Human-designed architectures are time-consuming and may not be optimal. NAS automates architecture design, potentially discovering better structures for given hardware constraints.

**Search Space**
The set of architectures that can be constructed. Defines: operation types (conv, attention, pooling), connectivity patterns (skip connections, dense connections), depth, width.

**Search Strategies**

| Strategy | Method | Examples |
|---|---|---|
| Reinforcement Learning | Controller generates architectures, RL trains controller | NASNet, MnasNet |
| Evolutionary | Mutation + selection of population | AmoebaNet, EfficientDet |
| Gradient-Based (DARTS) | Relax to continuous, optimize with gradient descent | DARTS, PC-DARTS |
| Predictor-Based | Train a surrogate to predict performance | ENAS, BANANAS |

**DARTS (Differentiable Architecture Search)**
Liu et al. (2019). Relaxes the discrete architecture choice to a continuous mixture of operations using softmax weights. Jointly optimizes architecture parameters and weight parameters via bi-level optimization.
📄 [Paper](https://arxiv.org/abs/1806.09055)

**EfficientNet**
Discovered a base architecture via NAS, then applied compound scaling. Consistently Pareto-optimal on accuracy/FLOPS trade-off.

**Once-for-All (OFA)**
Cai et al. (2020). Train one large network that contains many sub-networks. Different sub-networks extracted for different hardware targets without retraining.
📄 [Paper](https://arxiv.org/abs/1908.09791)

---

## Hyperparameter Tuning

**What to Tune (Priority Order)**
1. Learning rate (most impactful)
2. Batch size
3. Model architecture (depth, width)
4. Regularization strength (weight decay, dropout rate)
5. Optimizer parameters (β₁, β₂)
6. Data augmentation parameters

**Grid Search**
Exhaustive search over a manually specified grid of values. Exponentially expensive. Only practical for ≤ 2-3 hyperparameters with few options each.

**Random Search**
Sample hyperparameters randomly from defined distributions. Bergstra & Bengio (2012): random search is more efficient than grid search because it explores more of the effective dimensions.
📄 [Paper](https://www.jmlr.org/papers/v13/bergstra12a.html)

**Bayesian Optimization**
Build a surrogate model (GP or TPE) of the objective function. Use acquisition function (EI, UCB, PI) to select promising next configurations. Efficient for expensive evaluations (< 1000 trials). Tools: Optuna, HyperOpt, BoTorch.

**Hyperband / ASHA**
Multi-fidelity optimization: start many configurations, early-stop poor performers, continue with promising ones. Much more efficient than random search for neural networks. ASHA: asynchronous version for parallel workers.

**Population-Based Training (PBT)**
Jaderberg et al. (2017, DeepMind). Trains a population of models in parallel. Periodically copies weights from better models to worse ones and perturbs their hyperparameters. Jointly optimizes training schedule and hyperparameters.

**Practical Hyperparameter Guidelines**
- Start with: lr=1e-3 (Adam), lr=0.1 (SGD), batch_size=32 or 256
- Use log-scale for lr, weight decay: sample uniformly in log space
- For transformers: lr warmup is critical — use 1000-10000 warmup steps
- Track validation loss curve shape: fast drop then plateau = good, oscillating = unstable
- Cyclical LR (CLR): triangular LR cycles, enables finding good lr range efficiently

**Tools for HPO**
- 🐙 [Optuna](https://github.com/optuna/optuna) — Bayesian + Hyperband, great API ⭐
- 🐙 [Ray Tune](https://github.com/ray-project/ray/tree/master/python/ray/tune) — distributed HPO
- 🐙 [W&B Sweeps](https://docs.wandb.ai/guides/sweeps) — integrated with experiment tracking
- 🐙 [HyperOpt](https://github.com/hyperopt/hyperopt) — TPE algorithm
- 🐙 [NNI (Microsoft)](https://github.com/microsoft/nni) — comprehensive AutoML toolkit

---

# 💬 NLP and Large Language Models

---

## NLP Fundamentals

**The NLP Pipeline**
```
Raw Text
→ Preprocessing (lowercasing, punctuation, unicode)
→ Tokenization
→ [Optional: Stemming/Lemmatization, POS tagging, NER]
→ Feature Extraction (embeddings, TF-IDF)
→ Model (classification, generation, QA, etc.)
→ Post-processing (decoding, filtering)
```

**Core NLP Tasks**

| Task | Description | Example Models |
|---|---|---|
| Text Classification | Assign label(s) to text | BERT, RoBERTa |
| Named Entity Recognition (NER) | Identify entities (person, org, location) | BERT-CRF, spaCy |
| Part-of-Speech (POS) Tagging | Assign grammatical role to each word | spaCy, Flair |
| Dependency Parsing | Parse grammatical structure | spaCy, Stanza |
| Coreference Resolution | Link pronouns to entities | AllenNLP, SpanBERT |
| Machine Translation | Translate between languages | M2M-100, NLLB, mBART |
| Summarization | Compress text to key points | BART, T5, Pegasus |
| Question Answering | Answer questions from a passage | RoBERTa-SQuAD, UnifiedQA |
| Text Generation | Generate coherent text | GPT-4, LLaMA |
| Sentiment Analysis | Classify sentiment | BERT, RoBERTa |
| Natural Language Inference (NLI) | Entailment / contradiction / neutral | DeBERTa, T5 |
| Semantic Textual Similarity | Score text similarity | SentenceBERT, SimCSE |

**Challenges in NLP**
- **Ambiguity**: "I saw the man with the telescope" (who has the telescope?)
- **Context-dependence**: pronoun resolution, discourse coherence
- **World knowledge**: understanding implies vast background knowledge
- **Pragmatics**: what's implied vs. what's said ("Can you pass the salt?")
- **Low-resource languages**: most languages have minimal training data
- **Long-tail and OOV**: rare words and domain-specific jargon

---

## Tokenization

**Why Tokenization Matters**
Vocabulary design directly impacts: model vocabulary size, representation of rare words, compute efficiency, handling of multiple languages.

**Character-Level Tokenization**
Tokenizes every character individually. Tiny vocabulary (~200 tokens), no OOV problem. Very long sequences for the same text — models must learn to compose characters into words.

**Word-Level Tokenization**
Split on whitespace and punctuation. Large vocabulary (50k-500k), OOV problem for rare words. Simple but inflexible.

**Subword Tokenization (Modern Standard)**
Balance between character and word level. Handles OOV by decomposing into subwords. Standard for all modern LLMs.

**Byte Pair Encoding (BPE)**
1. Start with character-level vocabulary
2. Iteratively merge the most frequent pair of consecutive tokens
3. Repeat until vocabulary reaches desired size
Used in: GPT-2, GPT-3/4, RoBERTa, BART. Deterministic.
🐙 [tiktoken (OpenAI)](https://github.com/openai/tiktoken)

**WordPiece**
Similar to BPE but merges based on likelihood improvement rather than raw frequency.
`score = freq(AB) / (freq(A) × freq(B))`
Used in: BERT, DistilBERT. Marks sub-tokens with ## prefix.

**SentencePiece**
Trains tokenizer directly on raw text without pre-tokenization (language-agnostic).
Supports BPE and Unigram Language Model.
Used in: T5, LLaMA, Gemini, mT5. Handles any language including those without spaces.
🐙 [SentencePiece](https://github.com/google/sentencepiece)

**Unigram Language Model Tokenizer**
Start with a large vocabulary, iteratively remove tokens that least hurt likelihood. Probabilistic — allows the same text to have multiple tokenizations (useful for regularization during training).

**Byte-Level BPE**
BPE applied at the byte level rather than character level. Handles any Unicode text with a compact 256-byte base vocabulary. Used in GPT-2, RoBERTa, BLOOM. Never produces unknown tokens.

**Tokenization Artifacts and Pitfalls**
- Numbers: "100" may tokenize differently than "1", "0", "0"
- Spaces: leading space often part of token ("▁word" in SentencePiece)
- Case: "Hello" ≠ "hello" in many tokenizers
- Languages: languages with non-Latin scripts often require more tokens per concept (under-representation)
- Code: identifiers, indentation, symbols tokenized inconsistently

---

## Word Embeddings

**Word2Vec (Mikolov et al., 2013)**
Two architectures:
- **CBOW**: predict center word from context words
- **Skip-gram**: predict context words from center word
Skip-gram with negative sampling (SGNS) is most commonly used. Learns syntactic and semantic relationships: `vec(king) - vec(man) + vec(woman) ≈ vec(queen)`.
📄 [Paper](https://arxiv.org/abs/1301.3781) 🐙 [gensim](https://github.com/RaRe-Technologies/gensim)

**GloVe (Global Vectors)**
Pennington et al. (2014). Trains on global word-word co-occurrence statistics. Loss function: `Σ f(X_ij)(wᵢᵀw̃_j + bᵢ + b̃_j - log X_ij)²`. Combines count-based and prediction-based approaches.
📄 [Paper](https://nlp.stanford.edu/pubs/glove.pdf) 🐙 [GloVe](https://github.com/stanfordnlp/GloVe)

**FastText**
Bojanowski et al. (2017). Extends word2vec by representing each word as a bag of character n-grams. Handles morphologically rich languages, represents OOV words via subword components.
🐙 [fastText](https://github.com/facebookresearch/fastText)

**ELMo (Embeddings from Language Models)**
Peters et al. (2018). Contextual embeddings: representation of a word depends on its context (unlike word2vec which produces one vector per word regardless of context). Uses bidirectional LSTM language models.
📄 [Paper](https://arxiv.org/abs/1802.05365)

**Sentence Embeddings**
- **Sentence-BERT (SBERT)**: fine-tunes BERT using siamese network on sentence pairs. Enables semantic similarity search.
  🐙 [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) ⭐
- **SimCSE**: contrastive learning for sentence embeddings, using dropout as data augmentation.
- **E5, BGE, GTE**: modern strong embedding models, trained with contrastive learning on large corpora.
- **OpenAI text-embedding-3**: strong proprietary embeddings.

**Properties of Good Embeddings**
- Similar words have high cosine similarity
- Analogical reasoning: `a - b + c ≈ d` (king - man + woman ≈ queen)
- Semantic clustering: related words cluster together
- Minimal anisotropy: embeddings should use the full vector space, not be concentrated in a small cone

---

## Language Model Architectures

**Statistical Language Models**
N-gram models: estimate `P(w_t | w_{t-1}, ..., w_{t-n+1})` from corpus counts.
Smoothing required for unseen n-grams (Laplace, Kneser-Ney).
Limited to short contexts. Now only used as baselines or in hybrid systems.

**Neural Language Models**
Bengio et al. (2003): first neural LM — concatenate word embeddings of previous words, feed to MLP. Generalizes better than n-gram models.

**RNN Language Models**
Process sequence left-to-right, maintain hidden state. Better long-range dependencies than n-grams. Still limited by vanishing gradients. ELMo used bidirectional LSTM LMs for contextual embeddings.

**Transformer Language Models (GPT-style)**
Decoder-only Transformer with causal (masked) self-attention. Pre-trained on next-token prediction. Scales dramatically with data and compute. The dominant paradigm for generative AI.

**BERT-Style Masked LMs**
Encoder-only Transformer with bidirectional attention. Pre-trained with MLM (predict masked tokens) and NSP. Strong for understanding tasks, not directly generative. Fine-tuned for downstream tasks.

**Key Transformer LM Papers**

| Year | Model | Org | Params | Key Contribution |
|---|---|---|---|---|
| 2018 | GPT | OpenAI | 117M | Generative pre-training, left-to-right |
| 2018 | BERT | Google | 340M | Bidirectional masked LM |
| 2019 | GPT-2 | OpenAI | 1.5B | Zero-shot capabilities, BPE, larger scale |
| 2019 | XLNet | CMU/Google | 340M | Permutation LM, better than BERT |
| 2019 | RoBERTa | Meta | 355M | Better BERT training recipe, no NSP |
| 2019 | ALBERT | Google | 18M | Parameter sharing, SOP instead of NSP |
| 2019 | DistilBERT | HF | 66M | Knowledge distillation of BERT |
| 2020 | GPT-3 | OpenAI | 175B | Few-shot in-context learning emerges |
| 2020 | T5 | Google | 11B | Unified text-to-text framework |
| 2021 | CLIP | OpenAI | — | Vision-language contrastive |
| 2022 | InstructGPT | OpenAI | 175B | RLHF alignment |
| 2022 | Chinchilla | DeepMind | 70B | Optimal scaling (more data per param) |
| 2022 | PaLM | Google | 540B | Chain-of-thought, few-shot mastery |
| 2023 | LLaMA | Meta | 7-65B | Open weights, efficient training |
| 2023 | LLaMA 2 | Meta | 7-70B | Open weights + RLHF chat models |
| 2023 | Mistral 7B | Mistral AI | 7B | Sliding window attention, GQA, strong 7B |
| 2023 | Mixtral 8×7B | Mistral AI | 46B | Sparse MoE, 2 experts per token |
| 2024 | LLaMA 3 | Meta | 8-70B | Strong open model, multilingual |
| 2024 | Gemini 1.5 | Google | — | 1M context window, multimodal |
| 2024 | Claude 3 | Anthropic | — | 200k context, top-tier reasoning |

---

## Pre-training and Fine-tuning

**Why Pre-training Works**
Large unlabeled corpora contain vast knowledge. Pre-training learns: word meanings, grammar, world knowledge, common sense, reasoning patterns. Fine-tuning adapts these representations to specific tasks with small labeled datasets.

**Pre-training Objectives**

| Objective | Model Type | Masking | Example Models |
|---|---|---|---|
| Causal LM (CLM) | Decoder-only | Left-to-right | GPT, LLaMA |
| Masked LM (MLM) | Encoder-only | Random 15% | BERT, RoBERTa |
| Span Corruption | Encoder-Decoder | Random spans | T5, mT5 |
| Prefix LM | Encoder-Decoder | Prefix visible | PaLM, GLM |
| Contrastive | Encoder | — | CLIP, ALIGN |
| Masked Image + Text | Multimodal | Image patches + text | MAE + BERT |

**Full Fine-Tuning**
Update all model parameters on task-specific data. Most effective but expensive (stores a full copy of model per task). Learning rate typically 1e-5 to 5e-5 for Transformers.

**Parameter-Efficient Fine-Tuning (PEFT)**
Fine-tune a small fraction of parameters while keeping most of the model frozen.

| Method | Trainable Params | Mechanism |
|---|---|---|
| LoRA | < 1% | Low-rank weight updates |
| QLoRA | < 1% | LoRA on quantized (4-bit) base model |
| Adapters | ~2-5% | Small MLP modules inserted between layers |
| Prefix Tuning | ~0.1% | Learned prefix tokens prepended to each layer |
| Prompt Tuning | ~0.01% | Learned soft prompt tokens at input |
| IA³ | ~0.01% | Scale activations with learned vectors |

**LoRA in Detail**
For a weight matrix W ∈ ℝᵈˣᵏ, instead of updating W, add a low-rank decomposition:
`W' = W + ΔW = W + BA` where B ∈ ℝᵈˣʳ, A ∈ ℝʳˣᵏ, rank r << min(d,k).
During training, W is frozen, only A and B are updated.
Reduces trainable parameters from d×k to r×(d+k).
At inference, merge: `W' = W + BA` — no additional latency.
📄 [LoRA Paper](https://arxiv.org/abs/2106.09685)

**QLoRA (Quantized LoRA)**
Dettmers et al. (2023). 4-bit quantized base model + LoRA fine-tuning. Enables fine-tuning 65B+ parameter models on a single GPU. Uses NF4 (Normal Float 4) quantization and double quantization.
📄 [Paper](https://arxiv.org/abs/2305.14314)

**Instruction Fine-Tuning (IFT)**
Fine-tuning on (instruction, response) pairs to make models follow natural language instructions. Key datasets: FLAN (chain-of-thought + instructions across 1800 tasks), OpenAssistant, Alpaca (GPT-4 distilled), LIMA (only 1000 high-quality examples).

**Catastrophic Forgetting in Fine-Tuning**
Fine-tuning can overwrite pre-trained knowledge. Mitigations:
- Lower learning rate
- PEFT (LoRA, adapters)
- Continual pre-training with replay
- Elastic Weight Consolidation (EWC)

---

## Prompt Engineering

**Zero-Shot Prompting**
Direct task statement without examples:
`"Classify the sentiment of this review: 'The food was amazing!' Answer: Positive or Negative."`
Works well for common tasks on large models.

**Few-Shot Prompting**
Provide k examples in the prompt:
```
Sentence: "The movie was terrible." → Sentiment: Negative
Sentence: "I loved every minute." → Sentiment: Positive
Sentence: "It was okay I guess." → Sentiment:
```
Dramatically improves performance on novel or specific tasks. Example quality matters more than quantity.

**Chain-of-Thought (CoT)**
Prompt the model to reason step-by-step before giving the final answer.
`"Let's think step by step."`
Wei et al. (2022): CoT dramatically improves performance on math and reasoning tasks. Only emerges at ~100B+ parameters. 📄 [Paper](https://arxiv.org/abs/2201.11903)

**Zero-Shot CoT**
Just add: `"Let's think step by step."` — no examples needed. Kojimaet al. (2022). Simpler but slightly less powerful than few-shot CoT.

**Self-Consistency**
Sample multiple CoT reasoning paths, take majority vote for the final answer. Wang et al. (2022). Improves accuracy by ~5-10% on math/reasoning benchmarks.

**Tree of Thoughts (ToT)**
Yao et al. (2023). Explore multiple reasoning paths simultaneously, backtrack from dead ends, use search algorithms (BFS, DFS) over a tree of thoughts. Strong on complex reasoning tasks.
📄 [Paper](https://arxiv.org/abs/2305.10601)

**ReAct (Reasoning + Acting)**
Interleave reasoning traces with action calls to tools (search, calculator, code execution). Foundation of modern AI agents.
📄 [Paper](https://arxiv.org/abs/2210.03629)

**Retrieval-Augmented Prompting**
Provide retrieved relevant documents as context before the question. Reduces hallucination and extends the effective knowledge horizon beyond pre-training data. → See [Retrieval-Augmented Generation](#retrieval-augmented-generation)

**Prompt Design Best Practices**
- Be specific and explicit about the task
- Use delimiters (""", ###, <tags>) to structure the prompt
- Specify output format (JSON, bullet points, length)
- Provide role context: "You are an expert in..."
- For classification: provide label definitions and examples
- For generation: provide style, tone, and audience information
- For reasoning: explicitly request step-by-step thinking

**System Prompts**
In instruction-tuned models, a system prompt sets the model's persona, capabilities, and constraints. Processed before user messages. Critical for: constraining behavior, setting tone, providing context.

**Prompt Injection**
A security vulnerability where malicious text in the input overrides the intended system prompt. Mitigation: input sanitization, delimiters, separate processing pipelines, constitutional constraints.

**Soft Prompts (Prompt Tuning)**
Learnable continuous vectors prepended to the input at the embedding level. Trained by gradient descent while the model is frozen. More expressive than discrete prompts. Lester et al. (2021).

**Prompt Engineering Resources**
- 🎓 [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- 🎓 [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- 🐙 [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering)
- 📰 [Lilian Weng: Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)

---

## RLHF and Alignment

**The Alignment Problem**
How do we ensure AI systems reliably do what humans actually want? Challenges:
- **Value specification**: hard to fully specify human values mathematically
- **Reward hacking**: models optimize the metric, not the underlying goal
- **Goal misgeneralization**: model learns spurious correlations that fail out-of-distribution
- **Scalable oversight**: how to supervise systems smarter than humans?

**RLHF Pipeline (InstructGPT, ChatGPT)**
1. **Supervised Fine-Tuning (SFT)**: fine-tune base LLM on high-quality demonstrations
2. **Reward Model Training**: collect human preference data (pairs of responses rated A vs B), train a reward model to predict human preferences
3. **PPO Optimization**: fine-tune the SFT model using PPO to maximize reward model score, with KL penalty to prevent the model from deviating too far from SFT
📄 [InstructGPT Paper](https://arxiv.org/abs/2203.02155)

**PPO (Proximal Policy Optimization)**
`L_CLIP(θ) = E[min(r_t(θ)Â_t, clip(r_t(θ), 1-ε, 1+ε)Â_t)]`
Clips the policy ratio to prevent large updates. Stable and effective for RLHF. The standard RL algorithm for LLM alignment.
📄 [PPO Paper](https://arxiv.org/abs/1707.06347)

**DPO (Direct Preference Optimization)**
Rafailov et al. (2023). Bypasses the reward model entirely — directly optimizes a policy from preference data. Equivalent to RLHF under certain conditions but simpler: no RL loop required.
`L_DPO(θ) = -E[log σ(β log π_θ(y_w|x)/π_ref(y_w|x) - β log π_θ(y_l|x)/π_ref(y_l|x))]`
Widely adopted for open-source model alignment.
📄 [Paper](https://arxiv.org/abs/2305.18290)

**Constitutional AI (CAI)**
Anthropic (2022). Uses a set of principles (a "constitution") to guide model behavior. The model critiques and revises its own outputs using the principles. Reduces reliance on human labelers for harmful content.
📄 [Paper](https://arxiv.org/abs/2212.08073)

**RLAIF (RL from AI Feedback)**
Use a strong AI model (e.g., GPT-4) to generate preference labels instead of humans. Scalable but inherits biases of the labeling model. Used in Claude's training.

**Reward Hacking / Goodhart's Law**
"When a measure becomes a target, it ceases to be a good measure." Models find unexpected ways to maximize reward signals that don't correspond to true human preferences. Example: summarization model that produces very short summaries that score well on reward model but miss key information.

**Scalable Oversight Techniques**
- **Debate**: two AI agents argue, human judges the debate (easier to verify than generate)
- **Amplification**: human + AI assistant team to supervise AI systems
- **Recursive reward modeling**: train reward models on AI-assisted human judgments
- **Process supervision**: reward individual reasoning steps, not just final answer (Let's Verify Step by Step)

**AI Safety Research Areas**
- Interpretability and mechanistic understanding
- Robustness to distribution shift and adversarial inputs
- Value learning from human behavior
- Corrigibility and shutdown problem
- Mesa-optimization and inner alignment
- Deceptive alignment

---

---

## Retrieval-Augmented Generation

**Motivation**
LLMs have fixed knowledge from pre-training. RAG augments generation by retrieving relevant information at inference time, enabling: access to up-to-date information, reduced hallucination, attribution to sources, domain-specific knowledge without fine-tuning.

**RAG Pipeline**
```
User Query
→ Query Encoder (embed query)
→ Retrieve (ANN search over document store)
→ Retrieved Documents (top-k chunks)
→ Augment (prepend documents to LLM prompt)
→ Generate (LLM conditioned on retrieved context)
→ Response
```

**Document Indexing**
1. Load documents (PDF, web, databases)
2. Chunk documents (fixed size, semantic, by section)
3. Embed chunks (embedding model)
4. Store in vector database (FAISS, Pinecone, Weaviate, Chroma)

**Retrieval Methods**

| Method | Mechanism | Pros | Cons |
|---|---|---|---|
| BM25 (sparse) | TF-IDF term matching | Fast, no training, exact term match | No semantic understanding |
| Dense retrieval | ANN over embeddings | Semantic matching | Requires good embeddings |
| Hybrid | BM25 + dense, reranked | Best of both | More complex |
| Multi-vector | ColBERT: token-level matching | High quality | Expensive storage |

**Chunking Strategies**
- Fixed-size: simple, may break sentences
- Sentence/paragraph: semantic boundaries
- Recursive character splitting: tries multiple separators
- Semantic chunking: split when topic changes (embed and cluster)
- Small-to-big / parent-child: retrieve small chunks, return larger context

**Re-ranking**
After initial retrieval, re-rank top-k results with a cross-encoder (slower but more accurate than bi-encoder). Models: Cohere Rerank, BGE Reranker, ms-marco-MiniLM.

**Advanced RAG Techniques**

| Technique | Description |
|---|---|
| HyDE (Hypothetical Document Embeddings) | Generate hypothetical answer, embed it, use as query |
| Query expansion | Generate multiple query variants, retrieve for all |
| Multi-hop retrieval | Retrieve → answer intermediate question → retrieve again |
| RAG-Fusion | Multiple queries → multiple retrieval lists → RRF fusion |
| FLARE | Retrieve only when model is uncertain |
| Self-RAG | Model decides when to retrieve, critiques retrieved docs |
| Corrective RAG (CRAG) | Evaluate retrieved docs, discard irrelevant ones |

**Evaluation Metrics for RAG**
- **Context Recall**: fraction of ground truth answer contained in retrieved docs
- **Context Precision**: fraction of retrieved docs that are relevant
- **Answer Faithfulness**: is the answer grounded in the retrieved context?
- **Answer Relevance**: does the answer address the question?
- Framework: 🐙 [RAGAS](https://github.com/explodinggradients/ragas)

**RAG Frameworks**
- 🐙 [LangChain](https://github.com/langchain-ai/langchain) ⭐ — most popular, comprehensive
- 🐙 [LlamaIndex](https://github.com/run-llama/llama_index) ⭐ — data framework for LLMs
- 🐙 [Haystack](https://github.com/deepset-ai/haystack) — production-focused pipelines

**Vector Databases**

| Database | Open Source | Cloud | Best For |
|---|---|---|---|
| FAISS | ✅ (Meta) | ❌ | In-memory, research |
| Chroma | ✅ | ✅ | Simple RAG, local dev |
| Qdrant | ✅ | ✅ | Production, filtering |
| Weaviate | ✅ | ✅ | Hybrid search |
| Pinecone | ❌ | ✅ | Managed, scalable |
| Milvus | ✅ | ✅ | Large scale |
| pgvector | ✅ | ✅ | PostgreSQL extension |

📄 [RAG Survey Paper](https://arxiv.org/abs/2312.10997)

---

## Agents and Tool Use

**What is an AI Agent?**
An LLM-based system that can: perceive inputs (text, images, tool outputs), reason about them, plan multi-step actions, execute tools (web search, code, APIs), and iterate based on feedback.

**ReAct Framework**
Yao et al. (2022). Interleaves reasoning traces and actions:
```
Thought: I need to find the current population of France.
Action: web_search("France population 2024")
Observation: France has a population of approximately 68 million.
Thought: I have the information needed.
Action: Finish("France has ~68 million people")
```
📄 [Paper](https://arxiv.org/abs/2210.03629)

**Tool Use in LLMs (Function Calling)**
Models trained to output structured tool invocations:
```json
{
  "tool": "web_search",
  "arguments": {"query": "current Bitcoin price"}
}
```
Widely supported: OpenAI Function Calling, Anthropic Tool Use, Gemini Function Calling. Foundation of AI assistants and chatbots with capabilities.

**Common Agent Tools**
- Web search (Bing API, Google Search, Tavily)
- Code interpreter / execution sandbox
- Web browser / page fetching
- File system operations
- Database queries
- API calls (email, calendar, CRM, etc.)
- Image generation
- Calculator / Python REPL
- Memory (vector store of past interactions)

**Memory Types in Agents**

| Memory Type | Where Stored | Lifetime |
|---|---|---|
| In-context (short-term) | Context window | Current session |
| External (long-term) | Vector DB | Persistent |
| Parametric | Model weights | Permanent (via fine-tuning) |
| Cache (working memory) | KV cache | Inference session |

**Multi-Agent Systems**
Multiple agents collaborating:
- **AutoGen** (Microsoft): conversable agents that chat to complete tasks
- **CrewAI**: role-based agents with specific responsibilities
- **LangGraph**: graph-based agent workflows with cycles and state

**Agent Frameworks**
- 🐙 [LangChain Agents](https://github.com/langchain-ai/langchain) ⭐
- 🐙 [AutoGen (Microsoft)](https://github.com/microsoft/autogen)
- 🐙 [CrewAI](https://github.com/joaomdmoura/crewAI)
- 🐙 [LangGraph](https://github.com/langchain-ai/langgraph)
- 🐙 [OpenAI Assistants API](https://platform.openai.com/docs/assistants/overview)

**Challenges with Agents**
- Compounding errors: errors in early steps cascade
- Tool reliability: real-world tools fail
- Infinite loops: agents can get stuck
- Context length: long trajectories exceed context window
- Latency: multi-hop tool use is slow
- Safety: agents can take harmful real-world actions

**Agent Benchmarks**
- WebArena: web navigation tasks
- SWE-Bench: real GitHub issues (code generation)
- GAIA: general AI assistant tasks
- AgentBench: multi-domain agent evaluation

---

## Notable LLMs and Repos

### Proprietary Models

**GPT-4 / GPT-4o (OpenAI)**
Multimodal (text + images). Exceptional reasoning, coding, instruction following. GPT-4o: faster, supports voice/image natively.
🌐 [OpenAI Platform](https://platform.openai.com)

**Claude 3 / Claude 3.5 / Claude 4 (Anthropic)**
Strong reasoning, 200k context window, low hallucination rate. Constitutional AI alignment. Available via API.
🌐 [Anthropic API](https://www.anthropic.com/api)

**Gemini 1.5 Pro (Google)**
1M token context window. Natively multimodal (text, image, audio, video). Excellent at long-document tasks.
🌐 [Google AI Studio](https://aistudio.google.com)

**Mistral Large (Mistral AI)**
Competitive with GPT-4 class. Fast, efficient. Strong multilingual.
🌐 [Mistral AI](https://mistral.ai)

### Open-Weight Models

**LLaMA 3 (Meta)**
8B and 70B parameter models. State-of-the-art open weights. Apache 2.0 or custom license. Foundation for most open-source fine-tuning.
🐙 [LLaMA 3](https://github.com/meta-llama/llama3)

**Mistral 7B / Mixtral 8×7B**
- Mistral 7B: outperforms LLaMA 2 13B. Grouped Query Attention (GQA), Sliding Window Attention.
- Mixtral 8×7B: Sparse MoE — 8 experts, 2 active per token. 46B total, 12B active. Matches GPT-3.5.
🐙 [Mistral](https://github.com/mistralai/mistral-src)

**Qwen 2.5 (Alibaba)**
Strong multilingual (especially Chinese), coding, and math capabilities. Available in many sizes.
🐙 [Qwen](https://github.com/QwenLM/Qwen)

**Phi-3 / Phi-4 (Microsoft)**
Small but surprisingly powerful models (3.8B-14B params). Trained on high-quality synthetic data. Excellent for on-device deployment.
🐙 [Phi-3](https://huggingface.co/microsoft/Phi-3-medium-4k-instruct)

**DeepSeek V3 / R1 (DeepSeek)**
Chinese open-source lab. R1: strong reasoning via RL training (chain-of-thought). Competitive with top proprietary models on benchmarks.
🐙 [DeepSeek](https://github.com/deepseek-ai/DeepSeek-V3)

**Falcon (TII UAE)**
Strong early open model. RefinedWeb training data.
🐙 [Falcon](https://huggingface.co/tiiuae/falcon-40b)

**Code-Specific Models**

| Model | Org | Specialty |
|---|---|---|
| CodeLlama | Meta | Code (Python, C++, Java, many more) |
| Starcoder2 | BigCode | 600+ programming languages |
| DeepSeek-Coder | DeepSeek | Strong code generation and infilling |
| Codestral | Mistral | Code completion, 32k context |
| WizardCoder | WizardLM | Fine-tuned for instruction-based coding |

**Embedding Models**

| Model | Notes |
|---|---|
| text-embedding-3-large (OpenAI) | Strong, 3072 dims, Matryoshka embeddings |
| voyage-large-2 (Voyage AI) | Top retrieval performance |
| E5-large-v2 (Microsoft) | Strong open-source |
| BGE-M3 (BAAI) | Multilingual, multi-granularity |
| nomic-embed-text | Open, context-length 8192 |

**Model Hubs**
- 🌐 [Hugging Face Hub](https://huggingface.co/models) ⭐ — central repository for open models
- 🌐 [Ollama](https://ollama.ai) — run LLMs locally
- 🌐 [LM Studio](https://lmstudio.ai) — local model GUI

---

# 👁️ Computer Vision

---

## CV Fundamentals

**Image Representation**
Digital images: H × W × C tensor (height, width, channels). Color: RGB (3 channels). Grayscale: 1 channel. Pixel values: uint8 [0, 255] or float32 [0, 1] or [-1, 1] (normalized).

**Basic Image Operations**
- Convolution: edge detection (Sobel, Laplacian), blurring (Gaussian)
- Morphological operations: erosion, dilation, opening, closing
- Histogram equalization: improve contrast
- Color space conversions: RGB ↔ HSV ↔ LAB ↔ YCbCr

**Image Preprocessing (Deep Learning)**
- Resize to fixed input dimensions (224×224, 256×256, 512×512)
- Normalize: subtract ImageNet mean [0.485, 0.456, 0.406], divide by std [0.229, 0.224, 0.225]
- Data augmentation: random crop, horizontal flip, color jitter, rotation, cutout, mixup, cutmix

**OpenCV**
The most widely used library for classical CV operations: image I/O, filtering, feature detection, calibration, optical flow.
🐙 [OpenCV](https://github.com/opencv/opencv) 🐙 [Python bindings](https://github.com/opencv/opencv-python)

**Albumentations**
Fast, flexible data augmentation library for images. 70+ transforms. Works with segmentation masks and bounding boxes simultaneously.
🐙 [Albumentations](https://github.com/albumentations-team/albumentations) ⭐

---

## Image Classification

**ImageNet Challenge (ILSVRC)**
1000-class classification benchmark. Catalyzed deep learning breakthroughs. Top-5 error rate history:
- 2011: 25.7% (pre-deep learning)
- 2012: 15.3% (AlexNet) — massive drop
- 2015: 3.57% (ResNet) — surpasses human (~5%)
- 2017: 2.25% (Squeeze-Excitation Networks)

**Standard Training Recipe (Modern)**
- Architecture: ResNet-50 / ViT-B/16 / EfficientNetB4
- Augmentation: RandAugment, Mixup, CutMix, Random Erasing
- Regularization: label smoothing, weight decay
- Optimizer: AdamW or SGD + momentum
- LR schedule: cosine warmup
- Training: ~300 epochs

**Transfer Learning for Classification**
Load pretrained weights (ImageNet) → replace final FC layer → fine-tune:
- Linear probe: freeze backbone, train only head (fast, baseline)
- Full fine-tune: update all layers (best performance)
- Gradual unfreezing: unfreeze layers from top to bottom

---

## Object Detection

**The Two-Stage vs. One-Stage Divide**

**Two-Stage Detectors** (propose regions, then classify)
- Slower but more accurate on small objects
- R-CNN → Fast R-CNN → Faster R-CNN → Mask R-CNN

**Faster R-CNN** (Ren et al., 2015)
Region Proposal Network (RPN) shares convolutional features with detection head. End-to-end trainable. 5 fps. Foundation of many detection systems.
📄 [Paper](https://arxiv.org/abs/1506.01497)

**One-Stage Detectors** (predict directly from feature map)
- Faster inference, better for real-time applications

**YOLO (You Only Look Once) Family**
- YOLOv1 (2016): first real-time detector
- YOLOv3: multi-scale predictions
- YOLOv5: PyTorch, easy to use
- YOLOv8 (Ultralytics): current standard, supports detection/segmentation/pose
- YOLO-NAS: NAS-designed YOLO
🐙 [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) ⭐

**SSD (Single Shot MultiBox Detector)**
Liu et al. (2016). Multi-scale feature maps for detecting objects at different sizes. Fast and efficient.
📄 [Paper](https://arxiv.org/abs/1512.02325)

**RetinaNet + Focal Loss**
Lin et al. (2017). One-stage detector that matches two-stage accuracy via focal loss. FPN backbone for multi-scale features.
📄 [Paper](https://arxiv.org/abs/1708.02002)

**DETR (Detection Transformer)**
Carion et al. (2020). Removes hand-crafted components (NMS, anchor generation). Frames detection as set prediction using bipartite matching loss. Slow to train but elegant.
📄 [Paper](https://arxiv.org/abs/2005.12872)

**Deformable DETR / DINO-DETR**
Improves DETR convergence via deformable attention (attends to sparse reference points). State-of-the-art on COCO.

**Key Detection Metrics**
- **mAP (mean Average Precision)**: average AP across all classes
- **AP@50**: IoU threshold 0.5
- **AP@50:95**: average over IoU thresholds 0.5 to 0.95 (COCO metric)
- **FPS**: frames per second (inference speed)

**COCO Dataset**
The standard benchmark for detection and segmentation. 118k train images, 80 object categories, 5 annotations per image.
🌐 [COCO](https://cocodataset.org)

---

## Image Segmentation

**Semantic Segmentation**
Label every pixel with a class. No distinction between instances.

**U-Net** (Ronneberger, 2015)
Encoder-decoder with skip connections between corresponding encoder/decoder layers. Designed for biomedical images. Works well with limited data.
📄 [Paper](https://arxiv.org/abs/1505.04597)

**DeepLab Series**
Google's semantic segmentation: atrous (dilated) convolutions for large receptive fields, ASPP (Atrous Spatial Pyramid Pooling) for multi-scale context.
- DeepLabV3+: encoder-decoder with ASPP. State-of-the-art for years.
📄 [DeepLabV3+ Paper](https://arxiv.org/abs/1802.02611)

**SegFormer**
Xie et al. (2021). Efficient hierarchical Transformer encoder (Mix Transformer) + lightweight all-MLP decoder. Fast, accurate, no positional encoding needed.
📄 [Paper](https://arxiv.org/abs/2105.15203)

**Instance Segmentation**
Label every pixel AND distinguish individual instances.

**Mask R-CNN** (He et al., 2017)
Extends Faster R-CNN with a mask prediction branch. Predicts binary masks for each detected object. Standard baseline for instance segmentation.
📄 [Paper](https://arxiv.org/abs/1703.06870)

**Panoptic Segmentation**
Unified: semantic (stuff: sky, road) + instance (things: cars, people). Single model produces both.

**Segment Anything Model (SAM)**
Kirillov et al. (2023). Foundation model for image segmentation. Trained on SA-1B (1B+ masks). Accepts point, box, or mask prompts. Generalizes to unseen objects and domains. SAM 2 extends to video.
📄 [Paper](https://arxiv.org/abs/2304.02643) 🐙 [Repo](https://github.com/facebookresearch/segment-anything)

**Key Segmentation Metrics**
- **mIoU**: mean Intersection over Union across classes
- **Pixel accuracy**: fraction of correctly labeled pixels
- **PQ (Panoptic Quality)**: for panoptic segmentation

---

## Image Generation and Editing

**Text-to-Image Generation (Summary)**

| Model | Organization | Architecture | Notes |
|---|---|---|---|
| DALL-E 3 | OpenAI | Diffusion + GPT-4 | Best prompt adherence |
| Midjourney v6 | Midjourney | Diffusion | Most aesthetic |
| Stable Diffusion 3 | Stability AI | Diffusion Transformer | Open-source |
| Imagen 3 | Google | Diffusion | Photorealistic |
| FLUX.1 | Black Forest Labs | Flow Matching DiT | Open-source SotA |

**Stable Diffusion Ecosystem**
- 🐙 [AUTOMATIC1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) — most popular UI
- 🐙 [ComfyUI](https://github.com/comfyanonymous/ComfyUI) — node-based workflow
- 🐙 [Diffusers](https://github.com/huggingface/diffusers) ⭐ — Hugging Face library
- 🐙 [InvokeAI](https://github.com/invoke-ai/InvokeAI)

**ControlNet**
Zhang et al. (2023). Adds spatial conditioning to Stable Diffusion via trainable copies of the encoder. Enables: depth-to-image, canny edge, pose, segmentation map conditioning. Powerful for controlled generation.
📄 [Paper](https://arxiv.org/abs/2302.05543) 🐙 [Repo](https://github.com/lllyasviel/ControlNet)

**Image Editing with Diffusion**
- **InstructPix2Pix**: follow edit instructions (e.g., "make it snowy")
- **SDEdit**: add noise then denoise conditioned on edit prompt
- **Null-text Inversion**: invert real image into diffusion latent for precise editing
- **DreamBooth**: fine-tune model on 3-5 photos of a subject for personalized generation

**Image Super-Resolution**
- ESRGAN / Real-ESRGAN: 4× super-resolution via adversarial training
- StableSR: diffusion-based super-resolution
- SwinIR: Swin Transformer for image restoration

---

## Video Understanding

**Video Representation**
Video = sequence of frames. 3D CNNs process spatiotemporal volumes. Transformers process flattened space-time patches. Key challenge: efficient modeling of temporal information.

**Video Classification**
- **I3D** (Carreira & Zisserman, 2017): inflate 2D ImageNet weights to 3D. Two-stream (RGB + optical flow).
- **SlowFast** (Feichtenhofer, 2019): slow pathway (low frame rate, rich spatial) + fast pathway (high frame rate, coarse spatial).
- **Video Swin Transformer**: 3D shifted windows for efficient video attention.

**Video Object Detection and Tracking**
- **SORT / DeepSORT**: Kalman filter + ReID embeddings for multi-object tracking
- **ByteTrack**: use all detections (including low-confidence) for tracking

**Video Generation**
- **Sora** (OpenAI, 2024): video generation via diffusion on space-time patches (DiT). Up to 1 minute of 1080p video.
- **Stable Video Diffusion**: open-source image-to-video
- **CogVideoX**: open-source text-to-video

**Optical Flow**
Estimation of pixel motion between frames. Classical: Lucas-Kanade, Farneback. Deep: RAFT, FlowNet.

---

## 3D Vision and NeRF

**3D Representations**
- Point clouds: irregular, direct sensor output (LiDAR)
- Voxel grids: 3D discrete grid (memory-intensive)
- Meshes: triangulated surfaces (graphics standard)
- Implicit surfaces: SDF (Signed Distance Field), occupancy networks
- NeRF: neural radiance field (view synthesis)

**NeRF (Neural Radiance Fields)**
Mildenhall et al. (2020). Represent a scene as a continuous function: given (x, y, z, θ, φ) → (RGB, density σ). Render views via differentiable volumetric ray marching. Trained on posed images, renders novel views photo-realistically.
📄 [Paper](https://arxiv.org/abs/2003.08934) 🐙 [NeRF-pytorch](https://github.com/yenchenlin/nerf-pytorch)

**Instant-NGP (NVIDIA)**
Müller et al. (2022). Multi-resolution hash encoding makes NeRF training ~1000× faster (seconds vs hours). Foundation of many real-time NeRF systems.
📄 [Paper](https://arxiv.org/abs/2201.05989) 🐙 [Repo](https://github.com/NVlabs/instant-ngp)

**3D Gaussian Splatting**
Kerbl et al. (2023). Represent scenes as 3D Gaussians (position, covariance, opacity, color). Real-time rendering via tile-based differentiable rasterization. Faster training and rendering than NeRF.
📄 [Paper](https://arxiv.org/abs/2308.04079) 🐙 [Repo](https://github.com/graphdeco-inria/gaussian-splatting)

**PointNet / PointNet++**
Deep learning directly on point clouds. PointNet: per-point MLP + max pooling (permutation invariant). PointNet++: hierarchical with local neighborhood grouping.
📄 [PointNet Paper](https://arxiv.org/abs/1612.00593)

**3D Object Detection (Autonomous Driving)**
- PointPillars: efficient 3D object detection from LiDAR
- CenterPoint: center-based 3D detection
- BEVFusion: fuse LiDAR and camera in bird's-eye view

---

# 🎮 Deep Reinforcement Learning

---

## RL Fundamentals

**Markov Decision Process (MDP)**
Tuple (S, A, P, R, γ):
- S: state space
- A: action space
- P(s'|s,a): transition probability
- R(s,a,s'): reward function
- γ ∈ [0,1): discount factor

**Key Equations**

Bellman Expectation Equation:
`V^π(s) = Σ_a π(a|s) Σ_{s'} P(s'|s,a)[R(s,a,s') + γV^π(s')]`

Bellman Optimality Equation:
`V*(s) = max_a Σ_{s'} P(s'|s,a)[R(s,a,s') + γV*(s')]`

Policy from Q-function:
`π*(s) = argmax_a Q*(s,a)`

**Policy vs. Value Methods**

| Type | What it Learns | Examples |
|---|---|---|
| Value-based | Q(s,a) or V(s), derive policy | DQN, C51, Rainbow |
| Policy-based | π(a|s) directly | REINFORCE, TRPO |
| Actor-Critic | Both policy + value | A3C, PPO, SAC |
| Model-based | World model P(s'|s,a) | Dyna, MuZero, World Models |

**Exploration vs. Exploitation**
Agent must balance: exploiting known good actions vs. exploring to discover better ones.
- ε-greedy: take random action with probability ε
- Boltzmann/Softmax: sample from softmax(Q(s,a)/T)
- UCB (Upper Confidence Bound): prefer actions with high uncertainty
- Curiosity-driven: intrinsic reward for novel states (ICM, RND)
- Noisy Networks: add learnable noise to network weights

**Reward Shaping**
Modifying the reward function to provide more signal without changing the optimal policy. Potential-based reward shaping: `F(s,a,s') = γΦ(s') - Φ(s)` guarantees policy invariance.

---

## Model-Free RL

### Value-Based Methods

**Q-Learning**
Off-policy TD learning:
`Q(s,a) ← Q(s,a) + α[r + γ max_{a'} Q(s',a') - Q(s,a)]`
Converges to Q* in tabular settings. Model-free, off-policy.

**DQN (Deep Q-Network)**
Mnih et al. (2014, 2015). Key innovations for stable learning with neural Q-networks:
1. **Experience Replay**: store transitions in buffer, sample randomly → breaks temporal correlations
2. **Target Network**: separate network for computing TD targets, updated periodically → stabilizes training
3. Played 49 Atari games at human level.
📄 [Nature Paper](https://www.nature.com/articles/nature14236) 🐙 [Repo](https://github.com/google-deepmind/dqn_zoo)

**DQN Improvements**
- **Double DQN**: use online network to select action, target network to evaluate → reduces overestimation bias
- **Dueling DQN**: separate streams for V(s) and A(s,a), combined: `Q = V + A - mean(A)` → better generalization
- **Prioritized Experience Replay (PER)**: sample transitions proportional to TD error → focuses on surprising transitions
- **Multi-step Returns**: use n-step returns instead of 1-step → faster credit assignment
- **Distributional RL (C51)**: predict distribution over returns, not just expected value
- **NoisyNets**: replace ε-greedy with network weight noise for efficient exploration
- **Rainbow**: combines all of the above → SotA on Atari

**C51 / Distributional RL**
Bellemare et al. (2017). Model full distribution of returns `Z(s,a)` using categorical distribution over fixed atoms. Better performance than expected value alone.
📄 [Paper](https://arxiv.org/abs/1707.06887)

### Policy Gradient Methods

**REINFORCE**
Williams (1992). Monte Carlo policy gradient:
`∇J(θ) = E_τ[Σ_t ∇ log π_θ(a_t|s_t) G_t]`
High variance, no bias. Practical: subtract a baseline (value function) to reduce variance.

**TRPO (Trust Region Policy Optimization)**
Schulman et al. (2015). Constrains policy update size via KL divergence constraint:
`max E[π_θ(a|s)/π_old(a|s) × A(s,a)] subject to KL(π_old || π_θ) ≤ δ`
Monotonic improvement guarantees. Computationally expensive (conjugate gradient).
📄 [Paper](https://arxiv.org/abs/1502.05477)

**PPO (Proximal Policy Optimization)**
Schulman et al. (2017). Simplifies TRPO with a clipped surrogate objective:
`L_CLIP = E[min(r_t × A_t, clip(r_t, 1-ε, 1+ε) × A_t)]`
r_t = π_θ(a_t|s_t) / π_old(a_t|s_t). Simple to implement, widely used.
The standard RL algorithm for robotics and LLM alignment (RLHF).
📄 [Paper](https://arxiv.org/abs/1707.06347)

### Actor-Critic Methods

**A3C / A2C**
Asynchronous / synchronous advantage actor-critic. Multiple workers explore in parallel, update shared model asynchronously (A3C) or synchronously (A2C).

**SAC (Soft Actor-Critic)**
Haarnoja et al. (2018). Off-policy actor-critic with maximum entropy objective:
`J(π) = E[Σ_t R(s_t,a_t) + α H(π(·|s_t))]`
Entropy bonus encourages exploration. More sample-efficient than PPO. Standard for continuous control (robotics).
📄 [Paper](https://arxiv.org/abs/1801.01290)

**TD3 (Twin Delayed Deep Deterministic)**
Fujimoto et al. (2018). Addresses overestimation bias in actor-critic:
- Twin critics: take minimum of two Q estimates
- Delayed policy updates
- Target policy smoothing

---

## Model-Based RL

**World Models**
Ha & Schmidhuber (2018). Train a compressed world model (V: visual encoder, M: memory RNN, C: controller). Train the controller entirely inside the dream (model). Demonstrates imagination-based RL.
📄 [Paper](https://arxiv.org/abs/1803.10122)

**Dyna Architecture**
Sutton (1991). Plan using a learned model: use real experience for learning + simulated experience from model for planning. Efficiently combines both.

**MuZero (DeepMind)**
Schrittwieser et al. (2020). Plans with a learned latent world model without needing a true simulator. Masters chess, shogi, Go, and Atari from pixels. Achieves superhuman performance.
📄 [Paper](https://www.nature.com/articles/s41586-020-03051-4)

**DreamerV3**
Hafner et al. (2023). Learns a world model in a discrete latent space, trains purely from imagination. Mastered Minecraft diamond collection from scratch without prior knowledge.
📄 [Paper](https://arxiv.org/abs/2301.04104)

---

## Multi-Agent RL

**Cooperative MARL**
Multiple agents share a reward signal and must learn to cooperate. Challenge: credit assignment (who deserves credit?). Methods: QMIX, MADDPG, MAPPO.

**Competitive / Mixed**
Agents have conflicting objectives. Self-play is key: agents improve by playing against themselves. Used in AlphaGo/Zero, OpenAI Five (Dota 2), Capture The Flag.

**Independent Q-Learning (IQL)**
Treat each agent independently — simplest approach. Non-stationary from each agent's perspective (other agents are part of the "environment").

**QMIX**
Rashid et al. (2018). Monotonic mixing of individual Q-values into a joint Q-value. Enables centralized training with decentralized execution (CTDE).
📄 [Paper](https://arxiv.org/abs/1803.11605)

---

## RL from Human Feedback

(→ Detailed coverage in [RLHF and Alignment](#rlhf-and-alignment) section)

**Key Papers**
- 📄 [Learning to summarize with human feedback (OpenAI, 2020)](https://arxiv.org/abs/2009.01325)
- 📄 [InstructGPT (OpenAI, 2022)](https://arxiv.org/abs/2203.02155)
- 📄 [Constitutional AI (Anthropic, 2022)](https://arxiv.org/abs/2212.08073)

---

## Notable RL Environments and Repos

**Environments**

| Environment | Domain | Notes |
|---|---|---|
| OpenAI Gym / Gymnasium | Classic control, Atari | Standard interface |
| MuJoCo | Continuous control (robotics) | Physics simulation |
| DMControl | Continuous control | DeepMind, MuJoCo-based |
| Atari 100K | Discrete control | Sample efficiency benchmark |
| Brax | Robotics | JAX-based, fast |
| Isaac Gym/Lab | Robotics | NVIDIA GPU-accelerated |
| PettingZoo | Multi-agent | 50+ multi-agent envs |
| MiniGrid | Grid world, sparse rewards | Curriculum learning research |
| NetHack | Roguelike, complex | Extreme long-horizon tasks |
| OpenAI Procgen | Procedural generation | Generalization benchmark |

**RL Libraries**
- 🐙 [Stable Baselines 3](https://github.com/DLR-RM/stable-baselines3) ⭐ — production-quality RL implementations
- 🐙 [RLlib (Ray)](https://github.com/ray-project/ray/tree/master/rllib) — scalable distributed RL
- 🐙 [CleanRL](https://github.com/vwxyzjn/cleanrl) — single-file implementations, readable
- 🐙 [Sample Factory](https://github.com/alex-petrenko/sample-factory) — high-throughput RL
- 🐙 [Acme (DeepMind)](https://github.com/google-deepmind/acme)
- 🐙 [TorchRL](https://github.com/pytorch/rl)
- 🐙 [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) ⭐

---

---

# 🔀 Multimodal AI

---

## Vision-Language Models

**CLIP (Contrastive Language-Image Pretraining)**
Radford et al. (OpenAI, 2021). Trained on 400M image-text pairs with contrastive learning. Learns a shared embedding space where images and their descriptions are close. Enables zero-shot image classification by comparing image embeddings to text label embeddings.
📄 [Paper](https://arxiv.org/abs/2103.00020) 🐙 [Repo](https://github.com/openai/CLIP)

**ALIGN (Google)**
Jia et al. (2021). Similar to CLIP but trained on 1.8B noisy image-text pairs without heavy filtering. Shows scale can compensate for data noise.
📄 [Paper](https://arxiv.org/abs/2102.05918)

**DALL-E Series (OpenAI)**
- DALL-E (v1, 2021): VQ-VAE + autoregressive Transformer
- DALL-E 2 (2022): CLIP + Diffusion via CLIP image embeddings
- DALL-E 3 (2023): tightly integrated with ChatGPT for richer text understanding, native text rendering

**LLaVA (Large Language and Vision Assistant)**
Liu et al. (2023). Connect a CLIP visual encoder to an LLM (LLaMA/Vicuna) via a linear projection layer. Visual instruction tuning with GPT-4 generated data.
📄 [Paper](https://arxiv.org/abs/2304.08485) 🐙 [Repo](https://github.com/haotian-liu/LLaVA)

**GPT-4V / GPT-4o**
GPT-4 with vision capabilities. Accepts images in the prompt. GPT-4o: natively multimodal (text + image + audio) with low latency.

**Gemini (Google)**
Natively multimodal from the ground up (not retrofitted). Processes text, images, audio, video in a unified architecture. Gemini 1.5: 1M context, can process 1 hour of video, 1500 pages.

**Claude 3/4 Vision**
Accepts images in prompts. Strong at: document analysis, chart reading, detailed image description, visual reasoning.

**CogVLM / CogVLM2 (Tsinghua)**
Open-source strong visual language model. Deep fusion of visual features into the LLM.

**InternVL**
Strong open-source visual language model family. Competitive with proprietary models.

**Flamingo (DeepMind)**
Alayrac et al. (2022). Few-shot visual language model. Interleaves cross-attention layers with frozen language model to process arbitrarily interleaved image+text sequences.
📄 [Paper](https://arxiv.org/abs/2204.14198)

**BLIP / BLIP-2 (Salesforce)**
- BLIP (2022): bootstrapping vision-language pre-training
- BLIP-2 (2023): lightweight Q-Former bridges frozen image encoder and frozen LLM. Very parameter-efficient.
📄 [BLIP-2 Paper](https://arxiv.org/abs/2301.12597) 🐙 [Repo](https://github.com/salesforce/LAVIS)

**MiniGPT-4**
Connects frozen ViT and Vicuna with a single linear projection layer. Shows that minimal training can produce capable VLMs.

**Image-Text Understanding Tasks**
- Visual Question Answering (VQA): answer questions about images
- Image Captioning: generate description of an image
- Visual Grounding: locate referred objects
- Chart/Document Understanding: extract structured information
- OCR in the wild: recognize text in natural images

**Key Vision-Language Benchmarks**

| Benchmark | Task |
|---|---|
| VQAv2 | Visual question answering |
| GQA | Compositional visual reasoning |
| TextVQA | VQA with text in images |
| MMBench | Comprehensive multi-modal |
| MMMU | College-level multi-discipline |
| ScienceQA | Science questions with images |
| DocVQA | Document understanding |

---

## Audio and Speech AI

**Speech Recognition (ASR)**

**Whisper (OpenAI)**
Radford et al. (2022). Encoder-decoder Transformer trained on 680k hours of labeled audio. Multitask: transcription, translation, language identification. Robust to noise and accents.
📄 [Paper](https://arxiv.org/abs/2212.04356) 🐙 [Repo](https://github.com/openai/whisper) ⭐

**Wav2Vec 2.0 (Meta)**
Baevski et al. (2020). Self-supervised pre-training on raw audio using contrastive learning in latent space. Fine-tuned with CTC for ASR. Low-resource state-of-the-art.
📄 [Paper](https://arxiv.org/abs/2006.11477)

**HuBERT (Meta)**
Hsu et al. (2021). Self-supervised audio representation via masked prediction of discrete cluster assignments. Strong foundation for speech understanding.

**Text-to-Speech (TTS)**

**WaveNet (DeepMind)**
van den Oord et al. (2016). Autoregressive raw waveform generation using dilated causal convolutions. First high-quality neural TTS. Very slow inference.
📄 [Paper](https://arxiv.org/abs/1609.03499)

**Tacotron 2**
Text → mel spectrogram (seq2seq attention model), then mel → waveform (WaveNet/WaveGlow vocoder). Google's production TTS.

**VITS (Variational Inference TTS)**
Kim et al. (2021). End-to-end TTS combining VAE, normalizing flows, and GAN. High quality, fast inference.
📄 [Paper](https://arxiv.org/abs/2106.06103)

**XTTS / TorToise / Bark**
Modern open-source TTS systems with voice cloning, emotional synthesis, and non-verbal sounds.

**ElevenLabs**
State-of-the-art commercial TTS and voice cloning. Ultra-realistic, multi-language.

**Music Generation**

**AudioCraft (Meta)**
- **MusicGen**: text-to-music generation via language model over Encodec tokens
- **AudioGen**: text-to-audio effects
🐙 [AudioCraft](https://github.com/facebookresearch/audiocraft)

**Stable Audio (Stability AI)**
Long-form music generation conditioned on text prompts and duration via latent diffusion.

**Suno / Udio**
Commercial AI music generation — full song generation with lyrics and vocals.

**Key Audio Representations**
- Raw waveform: time-domain signal, 16kHz or 44.1kHz
- Mel spectrogram: frequency × time representation, most common for neural models
- MFCCs: Mel Frequency Cepstral Coefficients, classical ASR features
- Codec tokens (EnCodec, DAC): neural audio compression to discrete tokens — enables language model training on audio

**EnCodec (Meta)**
Neural audio codec that compresses audio to discrete tokens at multiple bitrates. Enables treating audio as a token sequence for language models.
🐙 [EnCodec](https://github.com/facebookresearch/encodec)

---

## Multimodal Architectures

**Unified Sequence Models**
Treat all modalities as tokens in a single sequence. Early fusion. Examples: Gato (DeepMind), UnifiedIO, 4M.

**Gato (DeepMind)**
Reed et al. (2022). Single Transformer that plays games, captions images, chats, and controls robot arms — all from the same weights. Different modalities tokenized differently, but same model processes all.
📄 [Paper](https://arxiv.org/abs/2205.06175)

**Cross-Modal Attention**
Flamingo-style: frozen language model + cross-attention layers that inject visual features at multiple levels. Efficient — only cross-attention layers are trained for vision tasks.

**Projection-Based Fusion (LLaVA-style)**
Encode image with frozen CLIP → project to language model's embedding space via MLP → prepend as prefix tokens. Minimal architecture change. Most popular approach for VLMs.

**Late Fusion**
Encode modalities separately → combine final representations. Simple but limited cross-modal interaction.

**MMIT Benchmarks and Leaderboards**
- 🌐 [Open VLM Leaderboard (Hugging Face)](https://huggingface.co/spaces/opencompass/open_vlm_leaderboard)
- 🌐 [LMSYS Chatbot Arena](https://chat.lmsys.org)

---

# ⚙️ MLOps and Production AI

---

## MLOps Concepts

**What is MLOps?**
The practice of applying DevOps principles to ML systems. Addresses the unique challenges of ML in production: data drift, model degradation, retraining pipelines, reproducibility, and serving.

**MLOps Maturity Levels**
- **Level 0**: manual, ad-hoc ML training and deployment
- **Level 1**: automated ML pipeline, CT (continuous training)
- **Level 2**: full CI/CD for ML pipelines — automated building, testing, deploying pipelines

**Key MLOps Components**

```
Data Management → Experiment Tracking → Model Registry
→ CI/CD Pipeline → Model Serving → Monitoring → Feedback Loop → Retrain
```

**Feature Store**
A centralized repository for computed features, enabling: feature reuse across teams, online+offline feature access, feature versioning, and preventing train/serve skew. Tools: Feast, Hopsworks, Vertex AI Feature Store.

**ML Metadata Store**
Tracks artifacts and lineage: which data was used to train which model, what transformations were applied. Essential for debugging and reproducibility.

**CI/CD for ML**
- CI: test data schemas, model training on sample, unit tests for feature pipelines
- CD: deploy new model if evaluation exceeds threshold, blue/green deployment, canary releases
- CT: automatically retrain when data drift detected or on schedule

---

## Experiment Tracking

**Why Track Experiments?**
ML experiments involve hundreds of runs with different hyperparameters. Tracking: parameters, metrics, artifacts (model weights, plots), code version, environment. Essential for reproducibility and debugging.

**Weights & Biases (W&B)**
Industry standard for experiment tracking. Features: dashboards, hyperparameter sweeps, artifact versioning, model registry, reports.
🌐 [wandb.ai](https://wandb.ai) 🐙 [wandb](https://github.com/wandb/wandb) ⭐

**MLflow**
Open-source platform: tracking, projects, models, registry. Self-hostable. Integrates with most frameworks.
🐙 [MLflow](https://github.com/mlflow/mlflow) ⭐

**Neptune.ai**
Collaborative experiment tracking and model registry. Strong metadata management.
🌐 [neptune.ai](https://neptune.ai)

**Comet ML**
Experiment tracking + model production monitoring.
🌐 [comet.ml](https://www.comet.ml)

**DVC (Data Version Control)**
Git for data and models. Tracks large files in remote storage (S3, GCS), versions experiments, defines ML pipelines as DAGs.
🐙 [DVC](https://github.com/iterative/dvc) ⭐

**Best Practices for Experiment Tracking**
- Log everything: hyperparameters, metrics, system info, git commit
- Use tags/groups to organize runs
- Log model artifacts with the run that produced them
- Write descriptive run names (not "run_42")
- Compare baseline vs. experiment side-by-side

---

## Model Serving and Deployment

**Serving Frameworks**

| Tool | Notes | Best For |
|---|---|---|
| TorchServe | PyTorch native, production-ready | PyTorch models |
| TF Serving | TensorFlow Serving, gRPC + REST | TF models |
| Triton Inference Server (NVIDIA) | Multi-framework, GPU-optimized | High throughput |
| BentoML | Framework-agnostic, packaging | Mid-scale |
| Ray Serve | Scalable, composable | Complex pipelines |
| vLLM | LLM serving with PagedAttention | LLMs ⭐ |
| TGI (HF) | Text Generation Inference | LLMs |
| Ollama | Local LLM serving | Development |

**vLLM**
Kwon et al. (2023). PagedAttention: manages KV cache like OS virtual memory pages → near-zero KV cache waste, 24× throughput improvement over naive serving.
📄 [Paper](https://arxiv.org/abs/2309.06180) 🐙 [Repo](https://github.com/vllm-project/vllm) ⭐

**ONNX (Open Neural Network Exchange)**
Standard format for representing ML models. Export from PyTorch/TF, run with ONNX Runtime (cross-platform, optimized). Key for deployment on diverse hardware.
🐙 [ONNX](https://github.com/onnx/onnx) 🐙 [ONNX Runtime](https://github.com/microsoft/onnxruntime)

**Model Optimization for Deployment**

| Technique | Effect | Tools |
|---|---|---|
| Quantization (INT8) | 4× memory reduction, ~2× speedup | bitsandbytes, TensorRT, GPTQ |
| Quantization (INT4) | 8× memory reduction | AWQ, GPTQ, llama.cpp |
| Pruning | Reduces parameters | torch.nn.utils.prune |
| Knowledge Distillation | Smaller, faster student | Custom training |
| Flash Attention | 2–4× faster attention | flash-attn library |
| Speculative Decoding | 2–3× faster LLM inference | Custom/built-in |
| Continuous Batching | Better GPU utilization for LLMs | vLLM, TGI |
| KV Cache | Avoids recomputing prefix | Standard in all serving |

**Speculative Decoding**
Use a small draft model to propose k tokens, verify them in parallel with the large model. Achieves 2-3× speedup with identical outputs (mathematically equivalent to greedy/sampling).

**Batch Inference**
Group multiple requests together to amortize overhead and improve GPU utilization. Continuous batching (vLLM): dynamically insert new requests into in-progress batches — far more efficient than static batching.

**Edge and Mobile Deployment**
- llama.cpp: C++ CPU/GPU inference for LLMs, quantized
- MLC LLM: deploy LLMs on any device (browser, mobile, GPU)
- ExecuTorch: PyTorch for on-device inference (Apple, Android)
- CoreML: Apple's framework for iOS/macOS inference
- TFLite: TensorFlow for mobile and edge

---

## Monitoring and Observability

**Why Monitor?**
Models in production degrade over time due to: data drift, concept drift, upstream data changes, infrastructure issues. Monitoring catches these before they cause harm.

**Types of Drift**

| Drift Type | Description | Detection |
|---|---|---|
| Data drift (covariate) | Input distribution changes | Statistical tests (KS, PSI) |
| Concept drift | Input-output relationship changes | Track prediction distribution |
| Label drift | Output distribution changes | Monitor prediction histogram |
| Feature drift | Individual feature distributions shift | Per-feature statistics |

**Key Metrics to Monitor**
- Model performance metrics (if labels available): accuracy, AUC
- Prediction distribution: mean, variance, class balance
- Input feature statistics: mean, std, nulls per feature
- Latency: P50, P95, P99 inference time
- Throughput: requests per second
- Error rate: HTTP 5xx, model exceptions

**Statistical Tests for Drift**
- Kolmogorov-Smirnov test: compare distributions
- Population Stability Index (PSI): common in finance
- Chi-squared test: for categorical distributions
- MMD (Maximum Mean Discrepancy): kernel-based, more powerful

**Monitoring Tools**

| Tool | Focus |
|---|---|
| Evidently AI | Open-source, beautiful reports |
| WhyLogs / WhyLabs | Streaming data monitoring |
| Arize AI | ML observability platform |
| Fiddler AI | Explainability + monitoring |
| Grafana + Prometheus | General metrics (latency, throughput) |
| DataDog | APM + custom ML metrics |

🐙 [Evidently AI](https://github.com/evidentlyai/evidently) ⭐
🐙 [Alibi Detect](https://github.com/SeldonIO/alibi-detect)

**LLM-Specific Monitoring**
- Hallucination rate
- Response length distribution
- Toxicity/safety violations
- Groundedness (for RAG)
- User feedback (thumbs up/down)
- Latency (TTFT: time to first token, TBT: time between tokens)
Tools: Langfuse, Langsmith, Arize Phoenix

---

## Data Versioning and Pipelines

**Data Version Control**
Treat data like code — version it, track lineage, reproduce experiments.
- 🐙 [DVC](https://github.com/iterative/dvc) — Git for data, remote storage
- 🐙 [LakeFS](https://github.com/treeverse/lakeFS) — Git-like interface for object storage
- 🐙 [Pachyderm](https://github.com/pachyderm/pachyderm) — data versioning + pipelines

**Data Pipelines and Orchestration**

| Tool | Type | Notes |
|---|---|---|
| Apache Airflow | Workflow orchestrator | DAG-based, widely used |
| Prefect | Workflow orchestrator | Modern Python, cloud + self-hosted |
| Metaflow (Netflix) | ML workflow | Excellent Python, AWS integration |
| ZenML | ML-specific pipelines | Portable across stacks |
| Kedro | ML project structure | Best practices framework |
| dbt | SQL transformation | Data warehouses |
| Apache Spark | Distributed processing | Large-scale data |
| Apache Kafka | Stream processing | Real-time feature computation |

**Feature Engineering at Scale**
- Offline features: batch computed, stored in feature store, used for training
- Online features: computed on-the-fly at inference time (low latency)
- Feature materialization: pre-compute and cache features for serving
- Backfilling: compute historical features for training data

**Data Quality**

Key checks to automate:
- Schema validation (correct types, required fields present)
- Distribution checks (no unexpected spikes or drops)
- Completeness (null rates below threshold)
- Uniqueness (no duplicate rows)
- Consistency (business rule validation)

Tools: Great Expectations, Soda, Deequ (PySpark)
🐙 [Great Expectations](https://github.com/great-expectations/great_expectations) ⭐

---

## Distributed Training

**Why Distributed?**
Large models don't fit on a single GPU. Training on billion-token datasets takes weeks on a single GPU. Distributed training is required for modern deep learning.

**Data Parallelism (DP)**
Same model on each device, different data. Gradients averaged across devices.
`PyTorch: torch.nn.DataParallel` (deprecated) or `DistributedDataParallel (DDP)`.
DDP is faster and preferred — each GPU has identical model copy, all-reduce for gradient synchronization.

**Model Parallelism (MP)**
Split model across devices. Required when model doesn't fit on one GPU.
- **Pipeline parallelism**: different layers on different GPUs (Gpipe, PipeDream)
- **Tensor parallelism**: split individual matrices (Megatron-LM splits attention heads across GPUs)

**3D Parallelism (Megatron + DeepSpeed)**
Combine data + pipeline + tensor parallelism. Used to train GPT-3, Megatron-Turing NLG (530B params).

**ZeRO (Zero Redundancy Optimizer)**
DeepSpeed ZeRO partitions optimizer states, gradients, and parameters across data-parallel workers. Dramatically reduces memory per GPU.
- ZeRO-1: partition optimizer states
- ZeRO-2: + partition gradients
- ZeRO-3: + partition parameters (full sharding)
🐙 [DeepSpeed](https://github.com/microsoft/DeepSpeed) ⭐

**FSDP (Fully Sharded Data Parallel)**
PyTorch native equivalent to ZeRO-3. Shards model parameters, gradients, and optimizer states across GPUs.
🌐 [PyTorch FSDP docs](https://pytorch.org/docs/stable/fsdp.html)

**Mixed Precision Training**
Store weights in FP32, compute in FP16 (or BF16). Dynamic loss scaling to prevent underflow.
BF16 (brain float): same exponent range as FP32, less precision — preferred over FP16 for training stability.
`PyTorch: torch.cuda.amp.autocast()`

**Gradient Accumulation**
Simulate larger batch sizes by accumulating gradients over multiple forward passes before one optimizer step. Useful for limited GPU memory.

**Distributed Training Frameworks**

| Framework | Notes |
|---|---|
| PyTorch DDP | Standard PyTorch distributed |
| DeepSpeed | ZeRO memory optimization, pipeline parallelism |
| Megatron-LM | Tensor/pipeline parallelism for giant LMs |
| FSDP | Native PyTorch full sharding |
| Horovod | Uber's multi-framework distributed training |
| JAX + pmap/jit | Google, functional, excellent TPU support |
| Accelerate (HF) | Wrapper for DDP/FSDP/DeepSpeed |

🐙 [Hugging Face Accelerate](https://github.com/huggingface/accelerate) ⭐ — simplifies multi-GPU/TPU training

---

# 🛠️ Frameworks and Libraries

---

## Core Frameworks

**PyTorch**
Facebook AI Research. Dynamic computation graphs (define-by-run). Pythonic, flexible, dominant in research and increasingly in production. Strong GPU/TPU support.
🐙 [PyTorch](https://github.com/pytorch/pytorch) ⭐
Key features: autograd, `nn.Module`, `torch.optim`, DataLoader, `torch.compile` (compiler), CUDA extensions.

```python
import torch
import torch.nn as nn

class MLP(nn.Module):
    def __init__(self, input_dim, hidden_dim, output_dim):
        super().__init__()
        self.layers = nn.Sequential(
            nn.Linear(input_dim, hidden_dim),
            nn.GELU(),
            nn.Linear(hidden_dim, output_dim)
        )
    
    def forward(self, x):
        return self.layers(x)

model = MLP(784, 256, 10)
optimizer = torch.optim.AdamW(model.parameters(), lr=1e-3)
criterion = nn.CrossEntropyLoss()
```

**TensorFlow / Keras**
Google Brain. Static graph (TF1) and eager mode (TF2). Keras high-level API for rapid prototyping. Strong production ecosystem (TF Serving, TFLite, TF.js). Dominant in industry.
🐙 [TensorFlow](https://github.com/tensorflow/tensorflow) ⭐
🐙 [Keras](https://github.com/keras-team/keras)

**JAX**
Google. NumPy API + composable function transformations: `grad`, `jit`, `vmap`, `pmap`. XLA compilation for hardware acceleration. Excellent for custom gradient computations and research. Growing rapidly in LLM training.
🐙 [JAX](https://github.com/google/jax) ⭐
🐙 [Flax](https://github.com/google/flax) — neural networks in JAX
🐙 [Optax](https://github.com/google-deepmind/optax) — optimizers in JAX

**PyTorch Lightning**
High-level wrapper for PyTorch. Removes boilerplate, handles multi-GPU training, logging, checkpointing. Code becomes more organized and reproducible.
🐙 [PyTorch Lightning](https://github.com/Lightning-AI/pytorch-lightning) ⭐

**Hugging Face Transformers**
Unified API for 200+ pre-trained Transformer models. Handles tokenization, model loading, fine-tuning, inference for NLP, vision, and multimodal models.
🐙 [Transformers](https://github.com/huggingface/transformers) ⭐

```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification
import torch

tokenizer = AutoTokenizer.from_pretrained("bert-base-uncased")
model = AutoModelForSequenceClassification.from_pretrained("bert-base-uncased")

inputs = tokenizer("Hello, this is great!", return_tensors="pt")
outputs = model(**inputs)
logits = outputs.logits
```

---

## NLP Libraries

**Hugging Face Ecosystem**
- 🐙 [Transformers](https://github.com/huggingface/transformers) — models
- 🐙 [Datasets](https://github.com/huggingface/datasets) — data loading
- 🐙 [Tokenizers](https://github.com/huggingface/tokenizers) — fast tokenization
- 🐙 [Diffusers](https://github.com/huggingface/diffusers) — diffusion models
- 🐙 [PEFT](https://github.com/huggingface/peft) — parameter-efficient fine-tuning
- 🐙 [TRL](https://github.com/huggingface/trl) — RLHF training
- 🐙 [Accelerate](https://github.com/huggingface/accelerate) — distributed training

**spaCy**
Industrial-strength NLP: tokenization, POS tagging, NER, dependency parsing, entity linking. Fast, production-ready. Supports 60+ languages.
🐙 [spaCy](https://github.com/explosion/spaCy) ⭐

**NLTK (Natural Language Toolkit)**
Classic Python NLP library. Tokenization, stemming, lemmatization, corpora access. Good for learning and classical NLP.
🐙 [NLTK](https://github.com/nltk/nltk)

**Gensim**
Topic modeling and word embeddings: Word2Vec, FastText, Doc2Vec, LDA.
🐙 [Gensim](https://github.com/RaRe-Technologies/gensim)

**AllenNLP**
Research-focused NLP framework from AI2. State-of-the-art implementations of NLU models.
🐙 [AllenNLP](https://github.com/allenai/allennlp)

**LangChain**
Framework for building LLM-powered applications: chains, agents, RAG pipelines, memory management.
🐙 [LangChain](https://github.com/langchain-ai/langchain) ⭐

**LlamaIndex**
Data framework for LLM applications: document ingestion, indexing, querying, RAG.
🐙 [LlamaIndex](https://github.com/run-llama/llama_index) ⭐

**Sentence Transformers**
Framework for sentence/text embeddings using BERT-like models. Essential for semantic search and RAG.
🐙 [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) ⭐

---

## CV Libraries

**torchvision**
PyTorch vision library: datasets (ImageNet, CIFAR), transforms (augmentation), pre-trained models (ResNet, ViT, EfficientNet).
🐙 [torchvision](https://github.com/pytorch/vision)

**timm (PyTorch Image Models)**
Ross Wightman's collection of 700+ image models with pre-trained weights. The go-to library for image classification models.
🐙 [timm](https://github.com/huggingface/pytorch-image-models) ⭐

**OpenCV**
Computer vision operations: I/O, filtering, feature detection, optical flow, camera calibration.
🐙 [OpenCV](https://github.com/opencv/opencv) ⭐

**Albumentations**
Fast, flexible image augmentation. 70+ transforms, works with bounding boxes and masks.
🐙 [Albumentations](https://github.com/albumentations-team/albumentations) ⭐

**Detectron2 (Meta)**
Object detection and segmentation platform: Faster R-CNN, Mask R-CNN, Panoptic FPN.
🐙 [Detectron2](https://github.com/facebookresearch/detectron2)

**MMDetection (OpenMMLab)**
Comprehensive detection toolbox: 40+ models, strong benchmarking.
🐙 [MMDetection](https://github.com/open-mmlab/mmdetection)

**YOLOv8 (Ultralytics)**
State-of-the-art, easy to use, supports detection/segmentation/classification/pose.
🐙 [Ultralytics](https://github.com/ultralytics/ultralytics) ⭐

**Kornia**
Differentiable computer vision for PyTorch: spatial transformations, image processing, augmentation as neural layers.
🐙 [Kornia](https://github.com/kornia/kornia)

**Hugging Face Transformers (Vision)**
ViT, Swin, DINO, SAM, CLIP, and more vision models via unified API.

---

## RL Libraries

(→ Covered in [Notable RL Environments and Repos](#notable-rl-environments-and-repos))

Additional tools:
- 🐙 [OpenAI Gym / Gymnasium](https://github.com/Farama-Foundation/Gymnasium) ⭐
- 🐙 [Stable Baselines 3](https://github.com/DLR-RM/stable-baselines3) ⭐
- 🐙 [RLlib](https://github.com/ray-project/ray)

---

## Data Processing

**NumPy**
Foundation of Python scientific computing. N-dimensional arrays, broadcasting, linear algebra, FFT.
🐙 [NumPy](https://github.com/numpy/numpy) ⭐

**pandas**
DataFrames for tabular data. Reading/writing (CSV, Parquet, SQL, Excel), cleaning, merging, groupby, time-series.
🐙 [pandas](https://github.com/pandas-dev/pandas) ⭐

**Polars**
Modern DataFrame library in Rust. Faster than pandas for many operations, lazy evaluation, query optimization.
🐙 [Polars](https://github.com/pola-rs/polars)

**scikit-learn**
Classical ML library: preprocessing, algorithms, model selection, metrics. Consistent API. Essential for tabular ML.
🐙 [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐

**Apache Spark / PySpark**
Distributed data processing. MLlib for distributed ML. Standard for big data pipelines.
🐙 [PySpark](https://github.com/apache/spark)

**Ray**
Distributed Python framework. Ray Data (distributed preprocessing), Ray Train (distributed training), Ray Serve, Ray Tune.
🐙 [Ray](https://github.com/ray-project/ray) ⭐

**Dask**
Parallel computing that scales pandas/NumPy to clusters. Lazy evaluation, familiar API.
🐙 [Dask](https://github.com/dask/dask)

---

## Visualization Tools

**matplotlib**
The foundation of Python visualization. Static, highly customizable plots.
🐙 [matplotlib](https://github.com/matplotlib/matplotlib)

**seaborn**
Statistical visualization built on matplotlib. Beautiful defaults, built-in statistical summaries.
🐙 [seaborn](https://github.com/mwaskom/seaborn)

**plotly**
Interactive plots for web applications. Dash for full dashboards.
🐙 [plotly](https://github.com/plotly/plotly.py) ⭐

**TensorBoard**
TensorFlow's visualization tool. Scalars, images, histograms, computation graphs, projector (embedding visualization). Also supported by PyTorch.
🐙 [TensorBoard](https://github.com/tensorflow/tensorboard)

**Weights & Biases**
Full experiment tracking with interactive dashboards, model comparison, hyperparameter importance.
🌐 [wandb.ai](https://wandb.ai) ⭐

---

## AutoML Tools

**AutoGluon**
Amazon's AutoML: state-of-the-art on tabular, image, text, and multimodal tasks with one `fit()` call.
🐙 [AutoGluon](https://github.com/awslabs/autogluon) ⭐

**H2O AutoML**
Automatic model training and ensemble. Strong tabular AutoML.
🐙 [H2O](https://github.com/h2oai/h2o-3)

**TPOT**
Tree-based pipeline optimization using genetic algorithms.
🐙 [TPOT](https://github.com/EpistasisLab/tpot)

**Optuna**
Hyperparameter optimization framework with Bayesian and TPE samplers.
🐙 [Optuna](https://github.com/optuna/optuna) ⭐

**Ray Tune**
Scalable distributed HPO, integrates with all major frameworks.
🐙 [Ray Tune](https://docs.ray.io/en/latest/tune/index.html)

---

## Vector Databases

(→ See [Vector Databases table](#vector-databases) in the RAG section)

**FAISS (Facebook AI Similarity Search)**
Efficient similarity search and clustering of dense vectors. CPU and GPU support. Exact and approximate search. The baseline for vector search.
🐙 [FAISS](https://github.com/facebookresearch/faiss) ⭐

**Qdrant**
Production-ready vector search engine. Advanced filtering, payload storage, scalar and product quantization.
🐙 [Qdrant](https://github.com/qdrant/qdrant) ⭐

**Chroma**
The simplest vector DB for RAG development. In-memory or persistent. Python and JavaScript.
🐙 [Chroma](https://github.com/chroma-core/chroma)

**Weaviate**
Vector search + hybrid (BM25 + semantic) + generative search. Schema-based data model.
🐙 [Weaviate](https://github.com/weaviate/weaviate)

**pgvector**
Vector similarity search extension for PostgreSQL. Perfect if you already use Postgres.
🐙 [pgvector](https://github.com/pgvector/pgvector)

**Milvus**
Highly scalable, designed for billion-scale vector search. Multiple index types (HNSW, IVF, DiskANN).
🐙 [Milvus](https://github.com/milvus-io/milvus)

---

**Fundamentals**
- 🎓 [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) ⭐ — best starting point, top-down approach
- 🎓 [CS229 — Machine Learning (Stanford, Andrew Ng)](https://cs229.stanford.edu/) ⭐ — rigorous ML foundations
- 🎓 [CS231n — CNNs for Visual Recognition (Stanford)](http://cs231n.stanford.edu/) ⭐ — best CV course
- 🎓 [CS224n — NLP with Deep Learning (Stanford)](http://web.stanford.edu/class/cs224n/) ⭐ — best NLP course
- 🎓 [CS285 — Deep RL (UC Berkeley)](https://rail.eecs.berkeley.edu/deeprlcourse/) ⭐ — best RL course
- 🎓 [Deep Learning Specialization (Coursera, Andrew Ng)](https://www.coursera.org/specializations/deep-learning) — beginner-friendly
- 🎓 [MIT 6.S191 — Introduction to Deep Learning](http://introtodeeplearning.com/)
- 🎓 [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — MLOps focus ⭐
- 🎓 [Practical RL (HSE)](https://github.com/yandexdataschool/Practical_RL)
- 🎓 [Neural Networks: Zero to Hero — Karpathy](https://karpathy.ai/zero-to-hero.html) ⭐ — build from scratch
- 🎓 [Made With ML](https://madewithml.com/) — MLOps + production ML
- 🎓 [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) ⭐ — practical Transformers
- 🎓 [Weights & Biases Courses](https://www.wandb.courses/) — MLOps, LLMs
- 🎓 [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) — LLMs, diffusion, agents

**Mathematics for ML**
- 🎓 [3Blue1Brown — Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) ⭐
- 🎓 [3Blue1Brown — Essence of Calculus](https://www.3blue1brown.com/topics/calculus) ⭐
- 🎓 [3Blue1Brown — Neural Networks](https://www.3blue1brown.com/topics/neural-networks) ⭐
- 🎓 [Gilbert Strang — MIT 18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- 🎓 [Mathematics for Machine Learning (book, free PDF)](https://mml-book.github.io/) ⭐
- 🎓 [Probability Theory — Joe Blitzstein (Harvard Stat 110)](https://projects.iq.harvard.edu/stat110)
- 🎓 [The Matrix Calculus You Need for Deep Learning](https://explained.ai/matrix-calculus/) ⭐

**Specialized**
- 🎓 [Stanford CS324 — Large Language Models](https://stanford-cs324.github.io/winter2022/)
- 🎓 [CMU 11-711 — Advanced NLP](https://phontron.com/class/anlp2024/)
- 🎓 [Spinning Up in Deep RL — OpenAI](https://spinningup.openai.com/) ⭐ — RL fundamentals with code
- 🎓 [Distill.pub](https://distill.pub/) ⭐ — beautiful interactive explanations (archived but timeless)
- 🎓 [The Annotated Transformer](https://nlp.seas.harvard.edu/annotated-transformer/) ⭐ — Transformer line-by-line
- 🎓 [Illustrated BERT (Jay Alammar)](https://jalammar.github.io/illustrated-bert/) ⭐
- 🎓 [Illustrated Transformer (Jay Alammar)](https://jalammar.github.io/illustrated-transformer/) ⭐
- 🎓 [Applied LLMs (Chip Huyen)](https://applied-llms.org/) ⭐ — production LLM systems
- 🎓 [LLM University (Cohere)](https://docs.cohere.com/docs/llmu)
- 🎓 [Reinforcement Learning Course (David Silver, DeepMind)](https://www.davidsilver.uk/teaching/) ⭐

**Books (Free Online)**
- 📚 [Deep Learning — Goodfellow, Bengio, Courville](https://www.deeplearningbook.org/) ⭐
- 📚 [Pattern Recognition and Machine Learning — Bishop](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)
- 📚 [Dive into Deep Learning (d2l.ai)](https://d2l.ai/) ⭐ — interactive, code-first
- 📚 [The Elements of Statistical Learning — Hastie, Tibshirani, Friedman](https://hastie.su.domains/ElemStatLearn/)
- 📚 [An Introduction to Statistical Learning](https://www.statlearning.com/) ⭐ — gentler ESL
- 📚 [Reinforcement Learning: An Introduction — Sutton & Barto](http://incompleteideas.net/book/the-book-2nd.html) ⭐
- 📚 [Convex Optimization — Boyd & Vandenberghe](https://web.stanford.edu/~boyd/cvxbook/)
- 📚 [Information Theory, Inference, and Learning Algorithms — MacKay](https://www.inference.org.uk/itila/book.html)
- 📚 [Probabilistic Machine Learning — Kevin Murphy](https://probml.github.io/pml-book/) ⭐
- 📚 [Mathematics for Machine Learning — Deisenroth](https://mml-book.github.io/)
- 📚 [Understanding Deep Learning — Simon Prince](https://udlbook.github.io/udlbook/) ⭐ — modern, comprehensive
- 📚 [Build a Large Language Model From Scratch — Raschka](https://github.com/rasbt/LLMs-from-scratch) ⭐

---

## Blogs and Newsletters

**Research Blogs (from Labs)**
- 📰 [OpenAI Blog](https://openai.com/blog) — GPT, DALL-E, safety research
- 📰 [Anthropic Blog](https://www.anthropic.com/research) — Claude, interpretability, safety ⭐
- 📰 [Google DeepMind Blog](https://deepmind.google/discover/blog/) — AlphaGo, AlphaFold, Gemini
- 📰 [Meta AI Blog](https://ai.meta.com/blog/) — LLaMA, ImageBind, PyTorch
- 📰 [Microsoft Research Blog](https://www.microsoft.com/en-us/research/blog/)
- 📰 [Hugging Face Blog](https://huggingface.co/blog) ⭐ — practical ML, open models
- 📰 [Stability AI Blog](https://stability.ai/news) — Stable Diffusion
- 📰 [Mistral AI Blog](https://mistral.ai/news/stories)

**Individual Researcher Blogs**
- 📰 [Lilian Weng — lilianweng.github.io](https://lilianweng.github.io/) ⭐ — deeply technical, comprehensive
- 📰 [Andrej Karpathy — karpathy.github.io](https://karpathy.github.io/) ⭐ — insightful, accessible
- 📰 [Sebastian Ruder — ruder.io](https://ruder.io/) — NLP transfer learning
- 📰 [Jay Alammar — jalammar.github.io](https://jalammar.github.io/) ⭐ — illustrated explanations
- 📰 [Chip Huyen — huyenchip.com](https://huyenchip.com/blog/) ⭐ — production ML, MLOps
- 📰 [Sebastian Raschka — sebastianraschka.com](https://sebastianraschka.com/) — practical deep learning
- 📰 [Colah's Blog — colah.github.io](https://colah.github.io/) ⭐ — beautiful visual explanations
- 📰 [Ferenc Huszár — inference.vc](https://www.inference.vc/) — probabilistic ML
- 📰 [Eugene Yan — eugeneyan.com](https://eugeneyan.com/) — applied ML, RecSys
- 📰 [Ahead of AI (Sebastian Raschka)](https://magazine.sebastianraschka.com/) — newsletter ⭐

**Newsletters**
- 📰 [The Batch (DeepLearning.AI)](https://www.deeplearning.ai/the-batch/) ⭐ — weekly AI news
- 📰 [Import AI (Jack Clark)](https://jack-clark.net/) ⭐ — research highlights, policy
- 📰 [The Gradient](https://thegradient.pub/) — longer-form technical articles
- 📰 [ML News (Yannic Kilcher)](https://www.youtube.com/@YannicKilcher) — YouTube + newsletter
- 📰 [Last Week in AI](https://lastweekin.ai/) — curated AI news roundup
- 📰 [TLDR AI](https://tldr.tech/ai) — daily short summaries
- 📰 [Ahead of AI](https://magazine.sebastianraschka.com/) — LLMs, research
- 📰 [Davis Summarizes Papers](https://twitter.com/davisblalock) — quick paper summaries
- 📰 [AlphaSignal](https://alphasignal.ai/) — top ML papers weekly

**Paper Discovery**
- 🌐 [ArXiv — cs.AI, cs.LG, cs.CL, cs.CV](https://arxiv.org/) ⭐ — preprint server
- 🌐 [Papers With Code](https://paperswithcode.com/) ⭐ — papers + code + benchmarks
- 🌐 [Semantic Scholar](https://www.semanticscholar.org/) — AI-powered paper search
- 🌐 [Connected Papers](https://www.connectedpapers.com/) — visual paper graph
- 🌐 [AlphaXiv](https://alphaxiv.org/) — ArXiv with annotations
- 🌐 [Hugging Face Papers](https://huggingface.co/papers) — daily highlighted papers

**Video Content / YouTube Channels**
- 📺 [Yannic Kilcher](https://www.youtube.com/@YannicKilcher) ⭐ — paper deep dives
- 📺 [Two Minute Papers](https://www.youtube.com/@TwoMinutePapers) — accessible paper summaries
- 📺 [3Blue1Brown](https://www.youtube.com/@3blue1brown) ⭐ — math intuitions
- 📺 [Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy) ⭐ — building LLMs from scratch
- 📺 [Lex Fridman](https://www.youtube.com/@lexfridman) — long-form AI interviews
- 📺 [StatQuest with Josh Starmer](https://www.youtube.com/@statquest) ⭐ — intuitive stats/ML
- 📺 [Sentdex](https://www.youtube.com/@sentdex) — practical Python/ML
- 📺 [Sebastian Raschka](https://www.youtube.com/@SebastianRaschka) — LLMs, deep learning
- 📺 [AI Explained](https://www.youtube.com/@aiexplained-official) — accessible AI news

---

## Conferences and Journals

**Top ML / AI Conferences**

| Conference | Full Name | Focus | Venue |
|---|---|---|---|
| **NeurIPS** | Neural Information Processing Systems | General ML/DL | Dec |
| **ICML** | International Conference on Machine Learning | General ML | Jul |
| **ICLR** | International Conference on Learning Representations | Deep learning | Apr/May |
| **AAAI** | Association for the Advancement of AI | General AI | Feb |
| **IJCAI** | International Joint Conference on AI | General AI | Aug |
| **UAI** | Uncertainty in Artificial Intelligence | Probabilistic ML | Jul/Aug |
| **AISTATS** | AI and Statistics | Probabilistic ML | Apr/May |

**Top Vision Conferences**

| Conference | Full Name | Focus |
|---|---|---|
| **CVPR** | Computer Vision and Pattern Recognition | Top CV venue |
| **ICCV** | International Conference on Computer Vision | Top CV (odd years) |
| **ECCV** | European Conference on Computer Vision | Top CV (even years) |

**Top NLP Conferences**

| Conference | Full Name | Focus |
|---|---|---|
| **ACL** | Association for Computational Linguistics | Main NLP venue |
| **EMNLP** | Empirical Methods in NLP | Empirical NLP |
| **NAACL** | North American Chapter of ACL | North American NLP |
| **EACL** | European Chapter of ACL | European NLP |
| **CoNLL** | Computational Natural Language Learning | NLP learning |

**Top Journals**

| Journal | Publisher | Focus |
|---|---|---|
| **Nature** | Nature Publishing | High-impact (AlphaFold, DQN published here) |
| **Nature Machine Intelligence** | Nature | ML/AI |
| **Science** | AAAS | High-impact science |
| **JMLR** | JMLR | Machine learning (free, open access) |
| **TPAMI** | IEEE | Pattern analysis, CV |
| **Artificial Intelligence** | Elsevier | General AI |
| **Transactions of ACL (TACL)** | MIT Press | NLP |

**How to Follow Conference Papers**
- 🌐 [Proceedings of ML Research (PMLR)](https://proceedings.mlr.press/) — ICML, ICLR, AISTATS
- 🌐 [NeurIPS Proceedings](https://papers.nips.cc/)
- 🌐 [ACL Anthology](https://aclanthology.org/) ⭐ — all NLP conference papers
- 🌐 [OpenReview](https://openreview.net/) — ICLR reviews and papers (public peer review)
- 🌐 [Papers With Code](https://paperswithcode.com/) ⭐ — conference papers + code

**Conference Deadlines Tracker**
- 🌐 [aideadlin.es](https://aideadlin.es/) ⭐
- 🌐 [AI Conference Deadlines](https://jackietseng.github.io/conference_call_for_paper/conferences.html)

---

## Research Labs and Organizations

**Academic Labs**

| Lab | Institution | Known For |
|---|---|---|
| **SAIL** | Stanford AI Lab | Foundational research across all AI |
| **CSAIL** | MIT | Robotics, NLP, vision |
| **CMU ML** | Carnegie Mellon | NLP (many BERT authors), robotics |
| **Berkeley AI Research (BAIR)** | UC Berkeley | RL, robotics, vision |
| **Allen Institute for AI (AI2)** | Independent | NLP (AllenNLP, MMLU), OLMo |
| **MILA** | Montréal | Deep learning (Bengio group) |
| **Vector Institute** | Toronto | Canadian AI research |
| **IDSIA** | Swiss | LSTM (Schmidhuber) |
| **Oxford Future of Humanity Institute** | Oxford | AI safety |
| **Leverhulme Centre for the Future of Intelligence** | Cambridge | AI ethics/policy |

**Industry Research Labs**

| Lab | Organization | Known For |
|---|---|---|
| **OpenAI** | OpenAI | GPT series, DALL-E, CLIP, Sora |
| **Anthropic** | Anthropic | Claude, Constitutional AI, interpretability |
| **Google DeepMind** | Google | AlphaGo, AlphaFold, Gemini, WaveNet |
| **Meta FAIR** | Meta | LLaMA, PyTorch, DINO, SAM |
| **Microsoft Research** | Microsoft | Phi, ORCA, ZeRO, LoRA |
| **NVIDIA Research** | NVIDIA | StyleGAN, Instant-NGP, 3DGS |
| **Apple ML Research** | Apple | MLX, on-device ML |
| **Amazon Science** | Amazon | AutoGluon, Alexa AI |
| **Samsung Research** | Samsung | On-device AI |
| **Huawei Noah's Ark** | Huawei | PanGu, various CV papers |

**Open Source / Non-Profit AI Organizations**

| Organization | Focus |
|---|---|
| **Hugging Face** | Open-source ML hub, models, datasets, spaces |
| **EleutherAI** | Open-source LLMs (GPT-NeoX, Pile, Pythia) |
| **LAION** | Open datasets (LAION-5B), open research |
| **BigCode** | Open code models (StarCoder) |
| **Together AI** | Open models, efficient inference |
| **Mistral AI** | Open-weight frontier models |
| **Stability AI** | Open image/video/audio generation |
| **Mozilla AI** | Open, trustworthy AI |
| **Allen Institute for AI (AI2)** | Open NLP research and tools |

**AI Safety Organizations**

| Organization | Focus |
|---|---|
| **Anthropic** | AI safety + capabilities (Constitutional AI, interpretability) |
| **OpenAI Safety Team** | Superalignment, interpretability |
| **DeepMind Safety** | Specification, robustness, interpretability |
| **Center for Human-Compatible AI (CHAI)** | Value alignment (Stuart Russell) |
| **Machine Intelligence Research Institute (MIRI)** | Formal AI safety |
| **Center for AI Safety (CAIS)** | Reducing catastrophic AI risks |
| **Future of Life Institute (FLI)** | Existential risk from AI |
| **Alignment Research Center (ARC)** | Evaluating dangerous capabilities |

---

# ⚖️ AI Ethics and Safety

---

## Fairness and Bias

**Types of Bias in ML**

| Bias Type | Description | Example |
|---|---|---|
| Historical bias | Training data reflects past inequalities | Criminal justice recidivism models |
| Representation bias | Some groups underrepresented in data | Facial recognition worse on dark skin |
| Measurement bias | Proxy variables measure different things for different groups | Using zip code as income proxy |
| Aggregation bias | One model for a heterogeneous population | Diabetes model ignoring gender differences |
| Deployment bias | Model used for different purpose than designed | Using sentiment for hiring |
| Evaluation bias | Benchmarks don't represent all populations | COMPAS recidivism dataset |

**Fairness Metrics**

| Metric | Definition | Trade-off |
|---|---|---|
| Demographic parity | Equal positive prediction rates across groups | May hurt accuracy |
| Equalized odds | Equal TPR and FPR across groups | Harder to achieve simultaneously |
| Equal opportunity | Equal TPR across groups | Relaxed equalized odds |
| Individual fairness | Similar individuals treated similarly | Hard to define similarity |
| Calibration | Predicted probabilities match true rates | Often in tension with other metrics |

**Impossibility Results**
Chouldechova (2017) and Kleinberg et al. (2016): when base rates differ between groups, it is mathematically impossible to simultaneously satisfy calibration AND equalized odds. Fairness is inherently multi-dimensional — there is no single perfect metric.

**Bias Mitigation Approaches**
- **Pre-processing**: reweighting, resampling, data augmentation for underrepresented groups
- **In-processing**: adversarial debiasing, fairness constraints in loss function
- **Post-processing**: threshold optimization per group, output calibration

**Tools**
- 🐙 [Fairlearn (Microsoft)](https://github.com/fairlearn/fairlearn)
- 🐙 [AI Fairness 360 (IBM)](https://github.com/Trusted-AI/AIF360)
- 🐙 [What-If Tool (Google)](https://pair-code.github.io/what-if-tool/)
- 📰 [FAccT Conference Proceedings](https://facctconference.org/)

---

## Interpretability and Explainability

**Intrinsic vs. Post-hoc Interpretability**
- **Intrinsic**: model is interpretable by design (linear regression, decision trees, rule lists)
- **Post-hoc**: explain a black-box model after training (LIME, SHAP, attention visualization)

**Local vs. Global Explanations**
- **Local**: explain a single prediction ("why did this loan get rejected?")
- **Global**: understand the model's overall behavior ("what features matter most?")

**LIME (Local Interpretable Model-agnostic Explanations)**
Ribeiro et al. (2016). Perturb the input around a specific example, fit a simple linear model to the perturbations, use that as a local explanation. Model-agnostic, works for text, image, tabular data.
📄 [Paper](https://arxiv.org/abs/1602.04938) 🐙 [Repo](https://github.com/marcotcr/lime)

**SHAP (SHapley Additive exPlanations)**
Lundberg & Lee (2017). Game-theoretic approach using Shapley values to attribute each feature's contribution to the prediction. Consistent, locally accurate, satisfies desirable axioms. Fast variants for trees (TreeSHAP).
📄 [Paper](https://arxiv.org/abs/1705.07874) 🐙 [Repo](https://github.com/shap/shap) ⭐

**Attention Visualization**
Visualizing attention weights in Transformers to understand what the model "looks at." Caveat: attention ≠ explanation (Jain & Wallace, 2019) — attention weights don't always correspond to feature importance.

**Saliency Maps (Gradients)**
Compute gradient of output with respect to input pixels. Highlights which pixels most affect the prediction. Variants: vanilla gradients, integrated gradients, Grad-CAM.

**Grad-CAM**
Selvaraju et al. (2017). Uses gradients of the target class w.r.t. the last convolutional layer to produce a coarse localization map. Visual, intuitive, no architecture changes needed.
📄 [Paper](https://arxiv.org/abs/1610.02391)

**Mechanistic Interpretability**
Understand the internal computations of neural networks at the level of circuits and features. Key work: Circuits (Olah et al.), Superposition (Elhage et al.), Monosemanticity (Anthropic). Going beyond "what does it look at" to "how does it compute."
📰 [Anthropic Interpretability Research](https://www.anthropic.com/research#interpretability)
📄 [Toy Models of Superposition (Anthropic)](https://transformer-circuits.pub/2022/toy_model/index.html) ⭐

**Probing**
Train small classifiers on top of frozen model representations to test what information is encoded. Example: probe BERT's hidden states for part-of-speech tags — does BERT encode syntactic structure? Reveals what models "know."

**Tools for Explainability**
- 🐙 [SHAP](https://github.com/shap/shap) ⭐
- 🐙 [LIME](https://github.com/marcotcr/lime)
- 🐙 [Captum (PyTorch)](https://github.com/pytorch/captum)
- 🐙 [TransformerLens](https://github.com/TransformerLensOrg/TransformerLens) ⭐ — mechanistic interpretability
- 🐙 [BertViz](https://github.com/jessevig/bertviz) — attention visualization

---

## AI Safety Research

**Key Safety Concerns**

| Concern | Description |
|---|---|
| **Misalignment** | Model optimizes a proxy metric, not true human values |
| **Reward hacking** | Model finds unexpected ways to maximize reward |
| **Deceptive alignment** | Model appears aligned during training but pursues different goals in deployment |
| **Goal misgeneralization** | Correct behavior in training distribution, wrong behavior out-of-distribution |
| **Power-seeking** | Advanced agents may seek resources/influence to pursue goals |
| **Catastrophic actions** | Actions with large, irreversible negative consequences |

**Technical Safety Research Areas**

**Robustness**
Ensuring models perform reliably under distribution shift, adversarial inputs, and edge cases. Methods: adversarial training, data augmentation, certified defenses, ensemble methods.

**Uncertainty Quantification**
Models should know what they don't know. Well-calibrated uncertainty enables safe deployment. Methods: Bayesian NNs, MC Dropout, Deep Ensembles, conformal prediction.

**Scalable Oversight**
How do humans supervise AI systems that are more capable than humans at specific tasks? Approaches: debate, amplification, recursive reward modeling, process supervision (OpenAI Let's Verify Step by Step).
📄 [AI Safety via Debate (Irving et al., 2018)](https://arxiv.org/abs/1805.00899)
📄 [Let's Verify Step by Step (Lightman et al., 2023)](https://arxiv.org/abs/2305.20050)

**Interpretability / Mechanistic Understanding**
Understanding the internal computations of neural networks to verify they are doing what we want. Anthropic's circuits work, superposition hypothesis, sparse autoencoders for feature extraction.
🌐 [Transformer Circuits Thread](https://transformer-circuits.pub/) ⭐

**Formal Verification**
Proving mathematical properties about neural network behavior. Can guarantee no adversarial examples within a ball, or that a control system never enters unsafe states. Tools: α,β-CROWN, Marabou.

**Constitutional AI**
Anthropic's approach: train models to follow a set of principles by self-critique and revision, reducing reliance on human feedback for safety. 📄 [Paper](https://arxiv.org/abs/2212.08073)

**Key Safety Reading**
- 📚 [Concrete Problems in AI Safety (Amodei et al., 2016)](https://arxiv.org/abs/1606.06565) ⭐
- 📚 [Superintelligence — Nick Bostrom](https://www.amazon.com/Superintelligence-Dangers-Strategies-Nick-Bostrom/dp/1501227742) (book)
- 📚 [Human Compatible — Stuart Russell](https://www.amazon.com/Human-Compatible-Artificial-Intelligence-Problem/dp/0525558616) ⭐ (book)
- 📰 [AI Alignment Forum](https://www.alignmentforum.org/) ⭐ — key alignment discussion
- 📰 [LessWrong](https://www.lesswrong.com/) — rationality + AI risk
- 🐙 [Anthropic Alignment Science](https://www.anthropic.com/research)

---

## Privacy-Preserving ML

**Differential Privacy (DP)**
A mathematical framework providing formal privacy guarantees. Training with DP-SGD: add calibrated Gaussian noise to gradients. ε-DP: the probability of any output changes by at most eᵉ when any single training example is removed.
📄 [Deep Learning with DP (Abadi et al., 2016)](https://arxiv.org/abs/1607.00133)
🐙 [TensorFlow Privacy](https://github.com/tensorflow/privacy)
🐙 [Opacus (PyTorch DP)](https://github.com/pytorch/opacus)

**Federated Learning**
Train a model across multiple decentralized devices without sharing raw data. Each device trains locally, only model updates (gradients) are shared and aggregated. Used by Google for keyboard prediction on Android.
📄 [Communication-Efficient Learning (McMahan et al., 2017)](https://arxiv.org/abs/1602.05629)
🐙 [Flower (FL framework)](https://github.com/adap/flower)
🐙 [PySyft](https://github.com/OpenMined/PySyft)

**Secure Multi-Party Computation (SMPC)**
Multiple parties compute a function on their private inputs without revealing those inputs to each other. Enables private inference: client sends encrypted input, server runs model, returns encrypted output.

**Homomorphic Encryption (HE)**
Perform computations on encrypted data without decrypting. Result when decrypted equals computation on plaintext. Very slow but provides strongest privacy guarantees. Research phase for ML.

**Machine Unlearning**
The ability to remove the influence of specific training examples from a trained model, without full retraining. Important for "right to be forgotten" (GDPR). Active research area.

---

## Governance and Policy

**Key Regulatory Frameworks**

| Framework | Region | Status | Key Points |
|---|---|---|---|
| **EU AI Act** | European Union | Enacted 2024 | Risk-based regulation, bans some uses |
| **NIST AI Risk Management Framework** | USA | Published 2023 | Voluntary, comprehensive framework |
| **Executive Order on AI (Biden)** | USA | 2023 | Safety, security, civil rights |
| **GDPR** | European Union | Active | Data privacy, impacts AI training |
| **China AI Regulations** | China | Active | Algorithmic recommendations, generative AI |
| **UK AI Safety Institute** | UK | Active | Frontier model evaluations |

**Key Policy Issues**
- Copyright and training data ownership
- Deepfakes and synthetic media attribution
- Autonomous weapons and lethal AI
- AI in high-stakes decisions (hiring, lending, bail, medical)
- Monopolization of AI capabilities
- Labor displacement and economic impact
- AI in elections and disinformation

**AI Ethics Organizations**
- 🌐 [Partnership on AI](https://partnershiponai.org/) — multi-stakeholder
- 🌐 [AI Now Institute](https://ainowinstitute.org/) — social implications
- 🌐 [Algorithm Watch](https://algorithmwatch.org/) — algorithmic accountability
- 🌐 [Electronic Frontier Foundation](https://www.eff.org/) — digital rights
- 🌐 [Center for AI Safety](https://www.safe.ai/) — catastrophic risk

**Model Cards and Datasheets**
- **Model Cards** (Mitchell et al., 2019): standardized documentation for ML models — intended use, limitations, performance across groups.
- **Datasheets for Datasets** (Gebru et al., 2018): standardized documentation for datasets — motivation, composition, collection process, biases.

---


---

# 🗂️ Full Alphabetical Index

> Every major term, concept, model, paper, tool, and framework mentioned in this document. Use Ctrl+F / Cmd+F to search.

---

## A

- A3C / A2C → [Actor-Critic Methods](#actor-critic-methods)
- ADALINE → [Pre-2015 Classics](#pre-2015-classics)
- AdaBoost → [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- AdaGrad → [Optimizers](#optimizers)
- Adam → [Optimizers](#optimizers)
- AdamW → [Optimizers](#optimizers)
- Adaptive Moment Estimation → see Adam
- Adversarial Attack → [Glossary A–F](#glossary-af)
- Adversarial Training → [Glossary A–F](#glossary-af)
- Agent (LLM) → [Agents and Tool Use](#agents-and-tool-use)
- Agent (RL) → [RL Fundamentals](#rl-fundamentals)
- AI Act (EU) → [Governance and Policy](#governance-and-policy)
- AI Safety → [AI Safety Research](#ai-safety-research)
- AI Winter → [Glossary A–F](#glossary-af)
- Albumentations → [CV Libraries](#cv-libraries)
- AlexNet → [CNN Architectures Timeline](#cnn-architectures-timeline)
- Alignment → [RLHF and Alignment](#rlhf-and-alignment)
- Aleatoric Uncertainty → [Glossary A–F](#glossary-af)
- ALIGN (Google) → [Vision-Language Models](#vision-language-models)
- AlphaFold 2 → [2019–2021 Scaling Era](#20192021-scaling-era)
- AlphaGo / AlphaStar / AlphaZero → [2019–2021 Scaling Era](#20192021-scaling-era)
- ALBERT → [Language Model Architectures](#language-model-architectures)
- ALiBi → [Attention and Transformers](#attention-and-transformers)
- Attention Mechanism → [Attention and Transformers](#attention-and-transformers)
- Attention Is All You Need → [2015–2018 Breakthroughs](#20152018-breakthroughs)
- AudioCraft → [Audio and Speech AI](#audio-and-speech-ai)
- AutoEncoder → [Neural Network Fundamentals](#neural-network-fundamentals)
- AutoGen → [Agents and Tool Use](#agents-and-tool-use)
- AutoGluon → [AutoML Tools](#automl-tools)
- Automatic Differentiation → [Calculus and Optimization](#calculus-and-optimization)
- AutoML → [Glossary A–F](#glossary-af) | [AutoML Tools](#automl-tools)
- Autoregressive Model → [Glossary A–F](#glossary-af)
- AWQ → [Model Serving and Deployment](#model-serving-and-deployment)

---

## B

- Backpropagation → [Glossary A–F](#glossary-af) | [Neural Network Fundamentals](#neural-network-fundamentals)
- Bagging → [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- Bahdanau Attention → [Recurrent Neural Networks](#recurrent-neural-networks)
- BART → [Language Model Architectures](#language-model-architectures)
- Batch Normalization → [Glossary A–F](#glossary-af) | [2015–2018 Breakthroughs](#20152018-breakthroughs)
- Batch Size → [Glossary A–F](#glossary-af)
- Bayesian Inference → [Glossary A–F](#glossary-af) | [Probability and Statistics](#probability-and-statistics)
- Bayesian Optimization → [Glossary A–F](#glossary-af) | [Hyperparameter Tuning](#hyperparameter-tuning)
- BentoML → [Model Serving and Deployment](#model-serving-and-deployment)
- BERT → [Glossary A–F](#glossary-af) | [Language Model Architectures](#language-model-architectures)
- Beta-VAE → [Variational Autoencoders](#variational-autoencoders)
- BGE (embeddings) → [Word Embeddings](#word-embeddings)
- Bias (statistical) → [Glossary A–F](#glossary-af)
- Bias (societal) → [Fairness and Bias](#fairness-and-bias)
- Bias-Variance Tradeoff → [Bias, Variance, and Regularization](#bias-variance-and-regularization)
- BigBird → [Attention and Transformers](#attention-and-transformers)
- BLIP / BLIP-2 → [Vision-Language Models](#vision-language-models)
- BM25 → [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- Bootstrapping → [Glossary A–F](#glossary-af)
- Bounding Box → [Glossary A–F](#glossary-af)
- ByteTrack → [Video Understanding](#video-understanding)
- Byte Pair Encoding (BPE) → [Glossary A–F](#glossary-af) | [Tokenization](#tokenization)
- BYOL → [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)

---

## C

- C51 (Distributional RL) → [Model-Free RL](#model-free-rl)
- CAI (Constitutional AI) → [RLHF and Alignment](#rlhf-and-alignment)
- CBOW → [Word Embeddings](#word-embeddings)
- Chain-of-Thought → [Glossary A–F](#glossary-af) | [Prompt Engineering](#prompt-engineering)
- Checkpoint → [Glossary A–F](#glossary-af)
- Chinchilla Scaling Laws → [2022–2025 Modern Era](#20222025-modern-era)
- Chroma → [Vector Databases](#vector-databases)
- CIFAR-10/100 → [Image Datasets](#image-datasets)
- CLIP → [Glossary A–F](#glossary-af) | [Vision-Language Models](#vision-language-models)
- CatBoost → [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- Catastrophic Forgetting → [Glossary A–F](#glossary-af)
- Central Limit Theorem → [Probability and Statistics](#probability-and-statistics)
- Chain Rule → [Calculus and Optimization](#calculus-and-optimization)
- Class Imbalance → [Core ML Concepts](#core-ml-concepts)
- Claude (Anthropic) → [Notable LLMs and Repos](#notable-llms-and-repos)
- Clustering → [Clustering](#clustering)
- CNN → [Convolutional Neural Networks](#convolutional-neural-networks)
- COCO Dataset → [Object Detection](#object-detection) | [Multimodal Datasets](#multimodal-datasets)
- CogVLM → [Vision-Language Models](#vision-language-models)
- CoT → see Chain-of-Thought
- Confusion Matrix → [Glossary A–F](#glossary-af)
- Context Window → [Glossary A–F](#glossary-af)
- Contrastive Learning → [Glossary A–F](#glossary-af) | [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- ControlNet → [Image Generation and Editing](#image-generation-and-editing)
- ConvNeXt → [CNN Architectures Timeline](#cnn-architectures-timeline)
- Convolution → [Convolutional Neural Networks](#convolutional-neural-networks)
- Cosine Similarity → [Glossary A–F](#glossary-af)
- CrewAI → [Agents and Tool Use](#agents-and-tool-use)
- Cross-Attention → [Attention and Transformers](#attention-and-transformers)
- Cross-Entropy Loss → [Glossary A–F](#glossary-af) | [Loss Functions](#loss-functions)
- Cross-Validation → [Glossary A–F](#glossary-af)
- CTC Loss → [Loss Functions](#loss-functions)
- Curriculum Learning → [Glossary A–F](#glossary-af)
- Curse of Dimensionality → [k-Nearest Neighbors](#k-nearest-neighbors)

---

## D

- DALL-E → [Vision-Language Models](#vision-language-models) | [Image Generation and Editing](#image-generation-and-editing)
- DARTS → [Neural Architecture Search](#neural-architecture-search)
- Data Augmentation → [Glossary A–F](#glossary-af)
- Data Leakage → [Glossary A–F](#glossary-af) | [Core ML Concepts](#core-ml-concepts)
- Data Parallelism → [Distributed Training](#distributed-training)
- DBSCAN → [Clustering](#clustering)
- DDPM → [Diffusion Models](#diffusion-models)
- DDIM → [Diffusion Models](#diffusion-models)
- DeepSeek R1/V3 → [Notable LLMs and Repos](#notable-llms-and-repos)
- DeepSpeed → [Distributed Training](#distributed-training)
- Decision Tree → [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- DenseNet → [CNN Architectures Timeline](#cnn-architectures-timeline)
- Dense Retrieval → [Glossary A–F](#glossary-af) | [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- Depthwise Separable Convolution → [Convolutional Neural Networks](#convolutional-neural-networks)
- DETR → [Object Detection](#object-detection)
- Differential Privacy → [Privacy-Preserving ML](#privacy-preserving-ml)
- Diffusion Models → [Diffusion Models](#diffusion-models)
- Dimensionality Reduction → [Dimensionality Reduction](#dimensionality-reduction)
- DiT (Diffusion Transformer) → [Diffusion Models](#diffusion-models)
- DINO → [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- Distributional RL → [Model-Free RL](#model-free-rl)
- DistilBERT → [Language Model Architectures](#language-model-architectures)
- DPO → [RLHF and Alignment](#rlhf-and-alignment)
- DQN → [Model-Free RL](#model-free-rl)
- DreamerV3 → [Model-Based RL](#model-based-rl)
- Dropout → [Glossary A–F](#glossary-af) | [Bias, Variance, and Regularization](#bias-variance-and-regularization)
- DVC (Data Version Control) → [Data Versioning and Pipelines](#data-versioning-and-pipelines)
- Dynamic Computation Graph → [Glossary A–F](#glossary-af)

---

## E

- Early Stopping → [Glossary A–F](#glossary-af)
- EfficientNet → [CNN Architectures Timeline](#cnn-architectures-timeline) | [Neural Architecture Search](#neural-architecture-search)
- Eigenvalues / Eigenvectors → [Linear Algebra](#linear-algebra)
- ELBO → [Variational Autoencoders](#variational-autoencoders) | [Probability and Statistics](#probability-and-statistics)
- ELMo → [Word Embeddings](#word-embeddings)
- Embedding → [Glossary A–F](#glossary-af) | [Word Embeddings](#word-embeddings)
- Emergent Capabilities → [Language Model Architectures](#language-model-architectures)
- EnCodec → [Audio and Speech AI](#audio-and-speech-ai)
- Encoder-Decoder → [Glossary A–F](#glossary-af) | [Attention and Transformers](#attention-and-transformers)
- Ensemble Methods → [Glossary A–F](#glossary-af) | [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- Entropy → [Glossary A–F](#glossary-af) | [Information Theory](#information-theory)
- Epistemic Uncertainty → [Glossary A–F](#glossary-af)
- Equivariance → [Glossary A–F](#glossary-af)
- ESRGAN → [Image Generation and Editing](#image-generation-and-editing)
- Evidently AI → [Monitoring and Observability](#monitoring-and-observability)
- Explainability → [Interpretability and Explainability](#interpretability-and-explainability)
- Exponential Moving Average → [Glossary A–F](#glossary-af)

---

## F

- F1 Score → [Glossary A–F](#glossary-af) | [Evaluation and Metrics](#evaluation-and-metrics)
- FAISS → [Vector Databases](#vector-databases)
- Faster R-CNN → [Object Detection](#object-detection)
- FastText → [Word Embeddings](#word-embeddings)
- Feature Engineering → [Feature Engineering](#feature-engineering)
- Feature Importance → [Glossary A–F](#glossary-af)
- Feature Map → [Glossary A–F](#glossary-af)
- Feature Store → [MLOps Concepts](#mlops-concepts)
- Federated Learning → [Privacy-Preserving ML](#privacy-preserving-ml)
- Few-Shot Learning → [Glossary A–F](#glossary-af) | [Prompt Engineering](#prompt-engineering)
- FID (Fréchet Inception Distance) → [Generative Adversarial Networks](#generative-adversarial-networks)
- Fine-tuning → [Glossary A–F](#glossary-af) | [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- FlashAttention → [Attention and Transformers](#attention-and-transformers)
- Flamingo → [Vision-Language Models](#vision-language-models)
- FLUX.1 → [Image Generation and Editing](#image-generation-and-editing) | [2022–2025 Modern Era](#20222025-modern-era)
- Flow Matching → [Diffusion Models](#diffusion-models)
- Focal Loss → [Glossary A–F](#glossary-af) | [Loss Functions](#loss-functions)
- Foundation Model → [Glossary A–F](#glossary-af)
- FSDP → [Distributed Training](#distributed-training)
- Function Approximation → [Glossary A–F](#glossary-af)

---

## G

- GANs → [Generative Adversarial Networks](#generative-adversarial-networks)
- GAT → [Graph Neural Networks](#graph-neural-networks)
- Gato → [Multimodal Architectures](#multimodal-architectures)
- Gaussian Mixture Model → [Clustering](#clustering)
- Gaussian Process → [Glossary G–Z](#glossary-gz)
- GCN → [Graph Neural Networks](#graph-neural-networks)
- GDPR → [Governance and Policy](#governance-and-policy)
- GELU → [Glossary G–Z](#glossary-gz) | [Activation Functions](#activation-functions)
- Gemini → [Notable LLMs and Repos](#notable-llms-and-repos) | [Vision-Language Models](#vision-language-models)
- Generative Models → [Glossary G–Z](#glossary-gz)
- GIN (Graph Isomorphism Network) → [Graph Neural Networks](#graph-neural-networks)
- GloVe → [Word Embeddings](#word-embeddings)
- GNN → [Graph Neural Networks](#graph-neural-networks)
- GoogLeNet / Inception → [CNN Architectures Timeline](#cnn-architectures-timeline)
- GPT series → [Language Model Architectures](#language-model-architectures) | [Notable LLMs and Repos](#notable-llms-and-repos)
- Grad-CAM → [Interpretability and Explainability](#interpretability-and-explainability)
- Gradient → [Glossary G–Z](#glossary-gz) | [Calculus and Optimization](#calculus-and-optimization)
- Gradient Checkpointing → [Glossary G–Z](#glossary-gz)
- Gradient Clipping → [Glossary G–Z](#glossary-gz)
- Gradient Descent → [Glossary G–Z](#glossary-gz) | [Optimizers](#optimizers)
- GraphSAGE → [Graph Neural Networks](#graph-neural-networks)
- Great Expectations → [Data Versioning and Pipelines](#data-versioning-and-pipelines)
- GroupNorm → [Glossary G–Z](#glossary-gz)
- GRU → [Recurrent Neural Networks](#recurrent-neural-networks)

---

## H

- Hallucination → [Glossary G–Z](#glossary-gz)
- Haystack → [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- He Initialization → [Neural Network Fundamentals](#neural-network-fundamentals)
- Hessian → [Calculus and Optimization](#calculus-and-optimization)
- Hierarchical Clustering → [Clustering](#clustering)
- HuBERT → [Audio and Speech AI](#audio-and-speech-ai)
- Hugging Face → [NLP Libraries](#nlp-libraries) | [Research Labs and Organizations](#research-labs-and-organizations)
- Hyperband → [Hyperparameter Tuning](#hyperparameter-tuning)
- Hyperparameter → [Glossary G–Z](#glossary-gz) | [Hyperparameter Tuning](#hyperparameter-tuning)
- HyDE → [Retrieval-Augmented Generation](#retrieval-augmented-generation)

---

## I

- I3D → [Video Understanding](#video-understanding)
- ImageNet → [Image Datasets](#image-datasets) | [Image Classification](#image-classification)
- In-Context Learning → [Glossary G–Z](#glossary-gz) | [Prompt Engineering](#prompt-engineering)
- Inception / GoogLeNet → [CNN Architectures Timeline](#cnn-architectures-timeline)
- Information Theory → [Information Theory](#information-theory)
- Instant-NGP → [3D Vision and NeRF](#3d-vision-and-nerf)
- Instance Normalization → [Glossary G–Z](#glossary-gz)
- InstructGPT → [RLHF and Alignment](#rlhf-and-alignment)
- Interpretability → [Interpretability and Explainability](#interpretability-and-explainability)
- IoU → [Glossary G–Z](#glossary-gz)

---

## J

- JAX → [Glossary G–Z](#glossary-gz) | [Core Frameworks](#core-frameworks)
- Jacobian → [Glossary G–Z](#glossary-gz)

---

## K

- KDE → [Density Estimation](#density-estimation)
- Kernel (CNN) → [Convolutional Neural Networks](#convolutional-neural-networks)
- Kernel (SVM/GP) → [Support Vector Machines](#support-vector-machines)
- KL Divergence → [Glossary G–Z](#glossary-gz) | [Information Theory](#information-theory)
- k-NN → [k-Nearest Neighbors](#k-nearest-neighbors)
- K-Means → [Clustering](#clustering)
- Knowledge Distillation → [Glossary A–F](#glossary-af) (under Distillation)
- Knowledge Graph → [Glossary G–Z](#glossary-gz)
- Kornia → [CV Libraries](#cv-libraries)

---

## L

- L1/L2 Regularization → [Bias, Variance, and Regularization](#bias-variance-and-regularization)
- Label Smoothing → [Glossary G–Z](#glossary-gz) | [Loss Functions](#loss-functions)
- LAMB → [Optimizers](#optimizers)
- LangChain → [NLP Libraries](#nlp-libraries) | [RAG Frameworks](#rag-frameworks)
- LangGraph → [Agents and Tool Use](#agents-and-tool-use)
- Latent Diffusion → [Diffusion Models](#diffusion-models)
- Latent Space → [Glossary G–Z](#glossary-gz)
- Layer Normalization → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)
- LDA (Latent Dirichlet Allocation) → [Density Estimation](#density-estimation)
- LDA (Linear Discriminant Analysis) → [Dimensionality Reduction](#dimensionality-reduction)
- LeakyReLU → [Activation Functions](#activation-functions)
- Learning Rate → [Glossary G–Z](#glossary-gz) | [Optimizers](#optimizers)
- LeNet → [CNN Architectures Timeline](#cnn-architectures-timeline)
- LightGBM → [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- LIME → [Interpretability and Explainability](#interpretability-and-explainability)
- Linear Regression → [Linear Models](#linear-models)
- Lion Optimizer → [Optimizers](#optimizers)
- LlamaIndex → [NLP Libraries](#nlp-libraries)
- LLaMA → [Notable LLMs and Repos](#notable-llms-and-repos)
- LLM → [Glossary G–Z](#glossary-gz) | [Notable LLMs and Repos](#notable-llms-and-repos)
- LLaVA → [Vision-Language Models](#vision-language-models)
- Logistic Regression → [Linear Models](#linear-models)
- Longformer → [Attention and Transformers](#attention-and-transformers)
- LoRA → [Glossary G–Z](#glossary-gz) | [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- Loss Function → [Glossary G–Z](#glossary-gz) | [Loss Functions](#loss-functions)
- LSTM → [Glossary G–Z](#glossary-gz) | [Recurrent Neural Networks](#recurrent-neural-networks)

---

## M

- MAE (Masked Autoencoders) → [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- MAML → [Glossary G–Z](#glossary-gz)
- Mamba → [2022–2025 Modern Era](#20222025-modern-era)
- MAP → [Glossary G–Z](#glossary-gz)
- Mask R-CNN → [Image Segmentation](#image-segmentation)
- Masked Language Modeling → [Glossary G–Z](#glossary-gz)
- matplotlib → [Visualization Tools](#visualization-tools)
- MDP → [RL Fundamentals](#rl-fundamentals)
- Mechanistic Interpretability → [Interpretability and Explainability](#interpretability-and-explainability)
- Megatron-LM → [Distributed Training](#distributed-training)
- Message Passing → [Glossary G–Z](#glossary-gz) | [Graph Neural Networks](#graph-neural-networks)
- Meta-Learning → [Glossary G–Z](#glossary-gz)
- Milvus → [Vector Databases](#vector-databases)
- MiniGPT-4 → [Vision-Language Models](#vision-language-models)
- Mistral → [Notable LLMs and Repos](#notable-llms-and-repos)
- Mixed Precision → [Distributed Training](#distributed-training)
- MLflow → [Experiment Tracking](#experiment-tracking)
- MLOps → [MLOps Concepts](#mlops-concepts)
- MLP → [Glossary G–Z](#glossary-gz) | [Neural Network Fundamentals](#neural-network-fundamentals)
- MobileNet → [CNN Architectures Timeline](#cnn-architectures-timeline)
- MoCo → [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- Model Card → [Governance and Policy](#governance-and-policy)
- Model Parallelism → [Distributed Training](#distributed-training)
- Momentum → [Glossary G–Z](#glossary-gz) | [Optimizers](#optimizers)
- MSE → [Loss Functions](#loss-functions)
- Multi-Head Attention → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)
- MuJoCo → [Notable RL Environments and Repos](#notable-rl-environments-and-repos)
- MusicGen → [Audio and Speech AI](#audio-and-speech-ai)
- MuZero → [Model-Based RL](#model-based-rl)
- Mixtral → [Notable LLMs and Repos](#notable-llms-and-repos)

---

## N

- Naive Bayes → [Naive Bayes](#naive-bayes)
- NAS → [Neural Architecture Search](#neural-architecture-search)
- NeRF → [3D Vision and NeRF](#3d-vision-and-nerf)
- Neural ODE → [Glossary G–Z](#glossary-gz)
- NMS → [Glossary G–Z](#glossary-gz)
- Normalizing Flows → [Normalizing Flows](#normalizing-flows)
- NumPy → [Data Processing](#data-processing)

---

## O

- Object Detection → [Object Detection](#object-detection)
- ONNX → [Model Serving and Deployment](#model-serving-and-deployment)
- OpenCV → [CV Libraries](#cv-libraries)
- Optuna → [Hyperparameter Tuning](#hyperparameter-tuning) | [AutoML Tools](#automl-tools)
- Out-of-Distribution → [Glossary G–Z](#glossary-gz)
- Overfitting → [Glossary G–Z](#glossary-gz) | [Bias, Variance, and Regularization](#bias-variance-and-regularization)

---

## P

- PCA → [Linear Algebra](#linear-algebra) | [Dimensionality Reduction](#dimensionality-reduction)
- pandas → [Data Processing](#data-processing)
- Panoptic Segmentation → [Image Segmentation](#image-segmentation)
- PEFT → [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- Perplexity → [Glossary G–Z](#glossary-gz)
- Phi-3/4 (Microsoft) → [Notable LLMs and Repos](#notable-llms-and-repos)
- pgvector → [Vector Databases](#vector-databases)
- PointNet → [3D Vision and NeRF](#3d-vision-and-nerf)
- Polars → [Data Processing](#data-processing)
- Pooling → [Glossary G–Z](#glossary-gz) | [Convolutional Neural Networks](#convolutional-neural-networks)
- PPO → [Policy Gradient Methods](#policy-gradient-methods) | [RLHF and Alignment](#rlhf-and-alignment)
- Precision → [Glossary G–Z](#glossary-gz)
- Prefix Tuning → [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- Pre-training → [Glossary G–Z](#glossary-gz) | [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- Prior → [Glossary G–Z](#glossary-gz)
- Prompt Engineering → [Prompt Engineering](#prompt-engineering)
- Prompt Injection → [Prompt Engineering](#prompt-engineering)
- Pruning → [Glossary G–Z](#glossary-gz) | [Model Serving and Deployment](#model-serving-and-deployment)
- PyTorch → [Core Frameworks](#core-frameworks)
- PyTorch Lightning → [Core Frameworks](#core-frameworks)

---

## Q

- Q-Learning → [Glossary G–Z](#glossary-gz) | [Model-Free RL](#model-free-rl)
- QKV → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)
- QLoRA → [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- Qdrant → [Vector Databases](#vector-databases)
- Qwen → [Notable LLMs and Repos](#notable-llms-and-repos)
- Quantization → [Glossary G–Z](#glossary-gz) | [Model Serving and Deployment](#model-serving-and-deployment)
- QMIX → [Multi-Agent RL](#multi-agent-rl)

---

## R

- RAG → [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- RAGAS → [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- Rainbow DQN → [Model-Free RL](#model-free-rl)
- Random Forest → [Glossary G–Z](#glossary-gz) | [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- Ray / Ray Tune → [Data Processing](#data-processing) | [Hyperparameter Tuning](#hyperparameter-tuning)
- ReAct → [Agents and Tool Use](#agents-and-tool-use)
- Recall → [Glossary G–Z](#glossary-gz) | [Evaluation and Metrics](#evaluation-and-metrics)
- Receptive Field → [Glossary G–Z](#glossary-gz) | [Convolutional Neural Networks](#convolutional-neural-networks)
- Rectified Linear Unit → see ReLU
- Recurrent Neural Network → [Recurrent Neural Networks](#recurrent-neural-networks)
- Regularization → [Bias, Variance, and Regularization](#bias-variance-and-regularization)
- REINFORCE → [Policy Gradient Methods](#policy-gradient-methods)
- ReLU → [Activation Functions](#activation-functions)
- Reparameterization Trick → [Variational Autoencoders](#variational-autoencoders)
- Representation Learning → [Glossary G–Z](#glossary-gz)
- ResNet → [Glossary G–Z](#glossary-gz) | [CNN Architectures Timeline](#cnn-architectures-timeline)
- Retrieval-Augmented Generation → [Retrieval-Augmented Generation](#retrieval-augmented-generation)
- Reward Function → [Glossary G–Z](#glossary-gz) | [RL Fundamentals](#rl-fundamentals)
- RLAIF → [RLHF and Alignment](#rlhf-and-alignment)
- RLHF → [Glossary G–Z](#glossary-gz) | [RLHF and Alignment](#rlhf-and-alignment)
- RMSNorm → [Glossary G–Z](#glossary-gz)
- RoBERTa → [Language Model Architectures](#language-model-architectures)
- ROC Curve / AUC → [Glossary G–Z](#glossary-gz) | [Evaluation and Metrics](#evaluation-and-metrics)
- RoPE → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)

---

## S

- SAC → [Model-Free RL](#model-free-rl)
- SAM (Segment Anything) → [Image Segmentation](#image-segmentation)
- SBERT (Sentence-BERT) → [Word Embeddings](#word-embeddings)
- Scaled Dot-Product Attention → [Attention and Transformers](#attention-and-transformers)
- scikit-learn → [Data Processing](#data-processing)
- Score-Based Models → [Diffusion Models](#diffusion-models)
- SegFormer → [Image Segmentation](#image-segmentation)
- Self-Attention → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)
- Self-Consistency → [Prompt Engineering](#prompt-engineering)
- Self-Supervised Learning → [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- Semantic Segmentation → [Glossary G–Z](#glossary-gz) | [Image Segmentation](#image-segmentation)
- Sentence Transformers → [NLP Libraries](#nlp-libraries) | [Word Embeddings](#word-embeddings)
- SentencePiece → [Tokenization](#tokenization)
- SHAP → [Interpretability and Explainability](#interpretability-and-explainability)
- Sigmoid → [Activation Functions](#activation-functions)
- SimCLR → [Semi-Supervised and Self-Supervised Learning](#semi-supervised-and-self-supervised-learning)
- SimCSE → [Word Embeddings](#word-embeddings)
- Skip Connections → [Neural Network Fundamentals](#neural-network-fundamentals)
- SlowFast → [Video Understanding](#video-understanding)
- Softmax → [Glossary G–Z](#glossary-gz) | [Activation Functions](#activation-functions)
- Sophia → [Optimizers](#optimizers) | [2022–2025 Modern Era](#20222025-modern-era)
- spaCy → [NLP Libraries](#nlp-libraries)
- Sparse Attention → [Glossary G–Z](#glossary-gz)
- Speculative Decoding → [Model Serving and Deployment](#model-serving-and-deployment)
- Stable Baselines 3 → [RL Libraries](#rl-libraries)
- Stable Diffusion → [Glossary G–Z](#glossary-gz) | [Diffusion Models](#diffusion-models)
- Stable Video Diffusion → [Video Understanding](#video-understanding)
- Stacking → [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- State Space Models (SSM/Mamba) → [2022–2025 Modern Era](#20222025-modern-era)
- StyleGAN → [Generative Adversarial Networks](#generative-adversarial-networks)
- SVD → [Linear Algebra](#linear-algebra)
- SVM → [Support Vector Machines](#support-vector-machines)
- Swish/SiLU → [Activation Functions](#activation-functions)
- SwinTransformer → [Attention and Transformers](#attention-and-transformers) | [Image Segmentation](#image-segmentation)

---

## T

- T5 → [Language Model Architectures](#language-model-architectures)
- Tacotron → [Audio and Speech AI](#audio-and-speech-ai)
- Teacher Forcing → [Glossary G–Z](#glossary-gz)
- Temperature → [Glossary G–Z](#glossary-gz)
- TensorFlow → [Core Frameworks](#core-frameworks)
- TensorBoard → [Visualization Tools](#visualization-tools)
- Tensor → [Glossary G–Z](#glossary-gz)
- TGI (Text Generation Inference) → [Model Serving and Deployment](#model-serving-and-deployment)
- timm → [CV Libraries](#cv-libraries)
- Tokenization → [Tokenization](#tokenization)
- torchvision → [CV Libraries](#cv-libraries)
- Transfer Learning → [Glossary G–Z](#glossary-gz) | [Pre-training and Fine-tuning](#pre-training-and-fine-tuning)
- Transformer → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)
- TransformerLens → [Interpretability and Explainability](#interpretability-and-explainability)
- Tree of Thoughts → [Prompt Engineering](#prompt-engineering)
- Triton Inference Server → [Model Serving and Deployment](#model-serving-and-deployment)
- TRL (Hugging Face) → [NLP Libraries](#nlp-libraries)
- TRPO → [Policy Gradient Methods](#policy-gradient-methods)
- t-SNE → [Glossary G–Z](#glossary-gz) | [Dimensionality Reduction](#dimensionality-reduction)

---

## U

- U-Net → [Glossary G–Z](#glossary-gz) | [Image Segmentation](#image-segmentation) | [Diffusion Models](#diffusion-models)
- UMAP → [Glossary G–Z](#glossary-gz) | [Dimensionality Reduction](#dimensionality-reduction)
- Uncertainty Quantification → [AI Safety Research](#ai-safety-research)
- Underfitting → [Glossary G–Z](#glossary-gz)

---

## V

- VAE → [Glossary G–Z](#glossary-gz) | [Variational Autoencoders](#variational-autoencoders)
- Validation Set → [Glossary G–Z](#glossary-gz) | [Core ML Concepts](#core-ml-concepts)
- Value Function → [Glossary G–Z](#glossary-gz) | [RL Fundamentals](#rl-fundamentals)
- Vanishing Gradient → [Glossary G–Z](#glossary-gz) | [Recurrent Neural Networks](#recurrent-neural-networks)
- Vector Database → [Vector Databases](#vector-databases)
- VGGNet → [CNN Architectures Timeline](#cnn-architectures-timeline)
- Vision Transformer (ViT) → [Glossary G–Z](#glossary-gz) | [Attention and Transformers](#attention-and-transformers)
- VITS → [Audio and Speech AI](#audio-and-speech-ai)
- vLLM → [Model Serving and Deployment](#model-serving-and-deployment)
- VQ-VAE → [Variational Autoencoders](#variational-autoencoders)

---

## W

- W&B (Weights & Biases) → [Experiment Tracking](#experiment-tracking)
- WaveNet → [Audio and Speech AI](#audio-and-speech-ai)
- Wav2Vec 2.0 → [Audio and Speech AI](#audio-and-speech-ai)
- Weaviate → [Vector Databases](#vector-databases)
- Weight Decay → see L2 Regularization
- Weight Initialization → [Neural Network Fundamentals](#neural-network-fundamentals)
- Whisper → [Audio and Speech AI](#audio-and-speech-ai)
- Word2Vec → [Glossary G–Z](#glossary-gz) | [Word Embeddings](#word-embeddings)
- WordPiece → [Tokenization](#tokenization)
- World Models → [Model-Based RL](#model-based-rl)

---

## X

- Xavier/Glorot Init → [Neural Network Fundamentals](#neural-network-fundamentals)
- XGBoost → [Glossary G–Z](#glossary-gz) | [Decision Trees and Ensembles](#decision-trees-and-ensembles)
- XLNet → [Language Model Architectures](#language-model-architectures)

---

## Y

- YOLO (all versions) → [Object Detection](#object-detection)

---

## Z

- ZeRO (DeepSpeed) → [Distributed Training](#distributed-training)
- Zero-Shot Learning → [Glossary G–Z](#glossary-gz) | [Prompt Engineering](#prompt-engineering)
- Z-Score Normalization → [Glossary G–Z](#glossary-gz)
- 3D Gaussian Splatting → [3D Vision and NeRF](#3d-vision-and-nerf)

---

---

# 🙌 Final Notes

This document is a living knowledge base. The field of AI moves fast — new architectures, training techniques, and capabilities emerge constantly. Use this as a foundation to build from, not a ceiling.

**The best way to learn AI:**
1. Understand the math (linear algebra, calculus, probability)
2. Implement from scratch (follow Karpathy's Zero to Hero)
3. Read primary sources (ArXiv, not just blog summaries)
4. Build something real (Kaggle, personal projects, research)
5. Stay current (Papers With Code, Twitter/X, newsletters)

**Golden resources to bookmark:**
- 🌐 [ArXiv cs.LG](https://arxiv.org/list/cs.LG/recent)
- 🌐 [Papers With Code](https://paperswithcode.com/)
- 🌐 [Hugging Face Hub](https://huggingface.co/)
- 🎓 [Karpathy Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html)
- 📚 [Dive into Deep Learning (d2l.ai)](https://d2l.ai/)
- 📰 [Lilian Weng's Blog](https://lilianweng.github.io/)

---

*Built with ❤️ in the spirit of the Awesome List community. PRs welcome.*

*Total: ~8000+ lines of pure AI knowledge.*
