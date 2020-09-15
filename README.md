# FewGLUE
This repository contains the FewGLUE dataset, consisting of a random selection of 32 training examples from the SuperGLUE training sets and up to 20,000 unlabeled examples for each SuperGLUE task.

### 🗂️ Structure

For each task `t` in SuperGLUE, the directory `FewGLUE/t` contains two files: `train.jsonl`, which contains the 32 training examples, and `unlabeled.jsonl`, which contains all unlabeled examples.
The official development and test sets are not included as they can be found [here](https://super.gluebenchmark.com/tasks).

### 📑 Format

All files follow the exact same format as the [original SuperGLUE training files](https://super.gluebenchmark.com/tasks).
