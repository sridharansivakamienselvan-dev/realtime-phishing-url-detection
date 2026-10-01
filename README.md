# Real-Time Phishing URL Detection

MSc dissertation project: a real-time phishing URL detector built around an ensemble machine learning model, with Explainable AI so an analyst can see why a URL was flagged.

## Status

Work in progress. This repository is being built from scratch and will hold the data preparation, feature engineering, model training, and explainability work.

## Approach

The classifier is written in Python and trained on the PhiUSIIL phishing URL dataset, reaching around 80 percent detection accuracy in evaluation. Several feature-engineering approaches are compared so that latency and accuracy can be balanced for use in a real-time pipeline, where a slow model is not useful to an analyst under alert pressure.

## Explainability

Predictions are paired with Explainable AI output so that a flagged URL comes with the features that drove the decision, rather than an opaque score. The aim is detection that an analyst can defend during triage and write up in an incident ticket.

## Planned repository layout

Data loading and preprocessing will live under data, feature extraction under features, training and evaluation scripts under models, explainability notebooks under explainability, and inference code under src.

## Note

This is research and coursework code for defensive detection purposes. It contains no phishing kits or live malicious URLs.
