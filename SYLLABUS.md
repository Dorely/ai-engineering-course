# AI Engineering — Syllabus

## Course model

This is a mastery-based course for an experienced software engineer transitioning into deeper AI/ML engineering and research-engineering work.

### Grading

- Labs: 40%
- Problem sets: 20%
- Module exam: 30%
- Explanation / oral defense: 10%

Mastery threshold: **85%**.

A module below mastery is remediated and reassessed. Progress is based on demonstrated understanding, not elapsed time.

## Modules

### 0. What does it mean for a machine to learn?
Model vs algorithm, parameters, hyperparameters, examples, features, labels, predictions, loss, optimization, training, inference, epochs, validation, and the training loop.

### 1. Numerical computing for ML
Python/NumPy, arrays, tensor shapes, axes, indexing, broadcasting, vectorization, element-wise operations, matrix operations, numerical precision, and memory layout intuition.

### 2. Linear algebra for AI
Scalars, vectors, matrices, tensors, dot products, matrix multiplication, linear transformations, norms, projections, rank, basis, dimensionality, eigenvectors/eigenvalues where useful, and SVD intuition.

### 3. Calculus, gradients, and autodiff
Functions, derivatives, partial derivatives, gradients, chain rule, computational graphs, Jacobians conceptually, numerical differentiation, automatic differentiation, and backpropagation.

### 4. Probability, statistics, and information theory
Random variables, probability distributions, expectation, variance, conditional probability, likelihood, maximum likelihood, sampling, entropy, cross-entropy, and KL divergence.

### 5. Machine learning fundamentals
Linear regression, logistic regression, classification, loss functions, gradient descent, data splits, generalization, bias/variance, overfitting, regularization, metrics, and leakage.

### 6. Neural networks from scratch
Neurons, MLPs, activations, layers, initialization, forward propagation, backpropagation, SGD, momentum, Adam, batching, and normalization.

### 7. PyTorch
Tensors, autograd, nn.Module, optimizers, datasets/data loaders, device placement, GPUs, checkpoints, mixed precision, reproducibility, profiling, and training-loop design.

### 8. Sequence modeling and attention
Embeddings, sequence representations, recurrence conceptually, context, attention, self-attention, Q/K/V, scaled dot-product attention, causal masking, and multi-head attention.

### 9. Transformers
Transformer blocks, residual connections, normalization, feed-forward networks, positional representations, causal transformers, and encoder/decoder distinctions.

### 10. Language models and pretraining
Tokenization, vocabularies, BPE-style tokenization, next-token prediction, logits, softmax, cross-entropy, context windows, generation, sampling, datasets, checkpoints, and validation.

### 11. Modern LLM training
Transfer learning, full fine-tuning, LoRA/PEFT, instruction tuning, quantization, dataset construction, evaluation, catastrophic forgetting, and behavioral analysis.

### 12. Post-training
Preference data, reward models, RLHF, DPO-family objectives, reinforcement-learning approaches, synthetic data, distillation, verifiers, and reasoning-oriented post-training.

### 13. AI systems engineering
GPU architecture, VRAM accounting, compute vs memory bandwidth, precision formats, gradient accumulation, activation checkpointing, distributed collectives, data parallelism, tensor parallelism, pipeline parallelism, sharding, and distributed training.

### 14. Inference and production systems
KV caches, batching, continuous batching, quantization, speculative decoding, throughput vs latency, serving, observability, and capacity planning.

### 15. Research engineering
Paper reading, algorithm reconstruction, experiment design, baselines, ablations, reproducibility, statistical interpretation, critical evaluation, and reproduction work.

## Major milestones

1. I understand how a neural network learns.
2. I can build and train neural networks competently.
3. I understand and can implement a transformer.
4. I can pretrain a small language model.
5. I can fine-tune and post-train pretrained models.
6. I understand how large-model training and inference systems scale.
7. I can engage meaningfully with current AI research and engineering.
