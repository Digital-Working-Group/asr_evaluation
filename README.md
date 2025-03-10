# ASR Evaluation
This repository contains example workflows, READMEs, sample data, and [Docker](https://www.docker.com/) files that facilitate the usage of various open-source voice feature extraction packages, tools, datasets, and models for evaluating the performance of automatic speech recognition algorithms.

It is a part of a larger [toolkit](https://github.com/FHS-BAP/Voice-Feature-Extraction-Toolkit/) that was developed to support scientific research surrounding investigations of relationships between brain aging and voice features, although the extraction of voice features does have wider applicability. We invite others to please offer their questions, ideas, feedback, and improvements on this repository.

## Overview
| Name | Description |
| - |-|
| **jiwer** | Evaluate [JiWER](https://github.com/jitsi/jiwer) on sample data, it is a Python package utilized for evaluating ASR systems. It supports the following measures: word error rate (WER), match error rate (MER), word information lost (WIL), word information preserved (WIP), and character error rate (CER).