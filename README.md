# Project: Visualize how presidential speeches change over time

## Data
[sotu.zip](https://github.com/user-attachments/files/26684891/sotu.zip)

## Idea Overview
This project uses machine learning and text analysis to explore how presidential language changes over time. First, each speech is converted into a vector, which turns the text into numerical features based on how important certain words are in each document. Principal Component Analysis (PCA) is then used to reduce them to just two dimensions so the speeches can be plotted and visually compared.

## Goal
The goal is to see whether speeches naturally separate by time period, president, or historical context. For example, older speeches may appear far from modern ones because the vocabulary and style are different. Speeches delivered during wars or national crises may cluster together because they use similar themes and language. Addresses from the same president may also group together, showing a consistent style. This project works especially well when combined with clustering, which can help identify hidden groupings in the speeches beyond what is obvious from the dates alone.

### Research question
Can the model do the following:
 - detect older speeches from modern speeches
 - cluster war era speeches together
 - group speeches from the same president

## What I could visualize

This project gives me many opportunities for visual output:

- side-by-side comparisons
- a simple quality score table



