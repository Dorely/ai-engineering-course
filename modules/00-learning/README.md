# Module 0 — What Does It Mean for a Machine to Learn?

## Purpose

Build a precise mental model of machine learning before introducing frameworks or heavy mathematics.

## Knowledge deliverables

By the end of this module, the student should be able to explain and use:

- examples / observations;
- features and targets;
- model vs algorithm;
- parameters vs hyperparameters;
- forward pass;
- prediction;
- loss;
- optimization;
- parameter update;
- training vs inference;
- epochs and batches;
- training, validation, and test data;
- the complete training loop.

## Module work

### Lecture 0.1 — The training loop
Trace a tiny model from input to prediction to error to parameter update.

### Lecture 0.2 — Parameters and optimization
Understand what a model stores and what training actually changes.

### Lecture 0.3 — Data and generalization
Understand why memorizing training examples is not the actual goal.

### Problem Set 0
Conceptual and hand-calculation problems covering training steps and terminology.

### Lab 0 — Train a model with ordinary Python
Implement a one-parameter model without NumPy, PyTorch, scikit-learn, or other ML frameworks. Observe predictions and loss improve as the parameter is updated.

### Module 0 assessment
Trace a training step manually and explain each operation. Includes a short oral/code defense of Lab 0.

## Mastery criteria

A successful student can answer the following without relying on memorized vocabulary:

1. What information is stored in a trained model?
2. What exactly changes during training?
3. How do we measure that a prediction is wrong?
4. How does that error influence the next version of the model?
5. What is different during inference?
6. Why is low training loss alone not enough to establish that a model is useful?
