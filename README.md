# Markov Chain Models of Classical Music Based on the Implication-Realization Model

## Project Overview

This project explores the use of Markov chains to model musical patterns and structures based on Eugene Narmour's Implication-Realization (IR) Model. The goal is to capture a piece’s melodic expectancy and analyze classical music compositions from the Baroque, Classical, and Romantic eras.

## Contents

- **Presentation**: `Presentation.pdf`
- **Jupyter Notebook**: ``Markov_Chains_IR_Model.ipynb``

## Project Structure

### Presentation

The presentation file `Presentation.pdf` provides a comprehensive overview of the project, including:

- Introduction to the IR Model
- Methodology for data extraction and Markov chain representation
- Results and discussions on the analysis of different musical eras
- Validation methods and insights

### Jupyter Notebook

The notebook `IR-Markov_Chains_IR_Model.ipynb` contains the code used for:

1. **Musical Data Extraction**
   - Using `music21` to extract musical elements from a dataset.
  
2. **IR Rule Definition**
   - Defining the rules of the IR Model for melodic expectancy.

3. **IR Symbol Assignment**
   - Assigning symbols to musical elements based on IR rules.

4. **Markov Chain Representation**
   - Creating Markov chain models from the assigned IR symbols.

5. **Graph Visualization**
   - Visualizing the Markov chain models to analyze patterns.

6. **Validation Methods**
   - Entropy Rate: Measures the variability and predictability of musical transitions.
   - Chi-Squared Test: Compares transition frequencies across different styles.
   - Kullback-Leibler (KL) Divergence: Assesses similarity or dissimilarity in structural patterns.

## Recommendations and Conclusions

The analysis showed that the IR model provides reasonable approximations of melodic patterns, although traditional expectations were not fully met. Future work could include:

- Implementing Hidden Markov Models for better insights into melodic archetypes.
- Expanding the dataset to include more diverse musical pieces across different eras.
- Refining IR Model segments based on multiple factors for clearer grouping and segmentation.

## References

- A comprehensive list of academic papers and resources used in the project can be found in the presentation.
