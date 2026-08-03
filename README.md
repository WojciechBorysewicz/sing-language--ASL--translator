# sing-language--ASL--translator
CNN-based ASL gesture recognition and image-to-text translation project.

## Overview

This project trains a convolutional neural network to classify static American Sign Language gestures representing digits 0–9 and letters A–Z.

## Project context

This repository contains a university project originally completed as an assignment for a Deep Learning course. The goal of the project was to train and evaluate a convolutional neural network for static ASL hand gesture recognition and to demonstrate a simple image-to-text translation pipeline.

## Repository contents

- `notebook/` — Google Colab notebook with training and evaluation code
- `report/` — LaTeX report and final PDF

## Dataset

The dataset is not included in this repository. Before running the notebook, download the ASL-HG dataset and update `PROJECT_DIR` in the notebook. The dataset can be accessed through the source referenced in Pranto et al. (2026), listed in `report/sources.bib`.

## Main steps

1. Load and preprocess the dataset.
2. Run configuration search.
3. Evaluate the selected configuration over multiple final runs.
4. Select the best final run.
5. Generate class-level breakdown table and learning curves.
6. Run gesture-to-text translation demo.
