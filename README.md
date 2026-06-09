# DSP Correlation and Signal Detection using MATLAB

## Overview

This project explores the relationship between correlation and convolution in Digital Signal Processing (DSP) and demonstrates how correlation can be used for signal detection and pattern recognition.

The implementation uses MATLAB to generate signals, compute standard and normalized correlation, and evaluate the presence of a reference signal within composite signals.

## Objectives

- Study the relationship between correlation and convolution.
- Compare standard and normalized correlation.
- Detect the presence of a signal within complex signals.
- Analyze the effect of signal amplitude on correlation.
- Demonstrate pattern recognition using correlation techniques.

## Topics Covered

### Correlation
- Cross Correlation
- Similarity Measurement
- Signal Matching
- Pattern Recognition

### Convolution
- System Response Analysis
- Relation to Correlation
- Time-Reversal Concept

## Signal Generation

Reference signals:

s1 = cos(2π·1·t)

s2 = cos(2π·4·t)

s3 = cos(2π·10·t)

Composite signals:

X = 2s1 + 4s2 + s3

Y = s1 + s2

## Analysis Performed

### Standard Correlation

Used to measure signal similarity:

R(X,s1) = 107

R(Y,s1) = 52

### Normalized Correlation

Used to remove amplitude dependency:

σ(X,s1) = 0.452

σ(Y,s1) = 0.714

Results show that normalized correlation provides a more reliable indication of signal similarity.

## Key Findings

- Standard correlation is highly affected by signal amplitude.
- Large amplitudes can produce misleading similarity measurements.
- Normalized correlation focuses on signal shape rather than magnitude.
- Normalized correlation is better suited for signal detection and pattern recognition applications.

## Technologies Used

- MATLAB
- Digital Signal Processing
- Correlation Analysis
- Signal Detection
- Pattern Recognition
- Data Visualization

## Results

- Generated and analyzed multiple sinusoidal signals.
- Compared standard and normalized correlation methods.
- Demonstrated signal detection using correlation.
- Visualized correlation results using MATLAB plots.

## Author

Sara Al Souqi

Birzeit University
