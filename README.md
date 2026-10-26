# AI Engineering Course

A mastery-based, project-driven course for developing the foundations needed to understand, build, train, evaluate, and operate modern AI systems.

This repository is the laboratory and durable record for the course. Lectures, discussion, oral defenses, exams, and grading happen in the associated ChatGPT Project; code, experiments, write-ups, and capstones live here.

## Course goals

By the end of the core curriculum, the student should be able to:

- reason about the mathematical and computational foundations of machine learning;
- implement core ML and neural-network mechanisms from first principles;
- use PyTorch competently for training and experimentation;
- implement attention and transformer architectures;
- pretrain a small language model;
- fine-tune and post-train pretrained models;
- reason about GPU memory, throughput, distributed training, and inference systems;
- read AI/ML papers critically and reproduce meaningful parts of published work.

## Structure

Each module contains four kinds of work:

1. **Knowledge deliverables** — concepts that must be explainable and usable.
2. **Problem sets** — mathematical and conceptual exercises.
3. **Labs** — implementations and experiments.
4. **Module assessments** — tests and oral/code defenses.

Mastery threshold: **85%**. A score below mastery triggers targeted remediation and a reassessment rather than simply moving on.

## Curriculum

See [SYLLABUS.md](SYLLABUS.md).

## Current module

[Module 0 — What does it mean for a machine to learn?](modules/00-learning/README.md)

## Repository layout

```text
modules/       Lecture notes, objectives, and module material
labs/          Lab specifications and student work
experiments/   Exploratory experiments
notes/         Student notes
capstone/      Final research-engineering project
```

The course intentionally begins below the abstraction level of modern AI frameworks. High-level libraries become useful only after the mechanisms they hide are understood.
