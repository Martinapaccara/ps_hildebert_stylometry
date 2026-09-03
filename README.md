# Stylometric Analysis of Medieval Latin Poetry

This repository contains materials and code for the stylometric analysis of Medieval Latin poetry.

The project combines lexical and metrical approaches and includes analyses of both elegiac couplets and hexameter poetry.

## Repository Structure

The repository is organised into two main sections:

- `Distici/` – analyses of texts composed in elegiac couplets
- `Esametri/` – analyses of texts composed in hexameters

Each section may contain:

- `Lexical analysis/` – notebooks, data, and results related to lexical stylometry
- `Metrical analysis/` – notebooks, corpora, and results related to metrical stylometry

Individual analyses are organised in separate directories, while shared corpora and resources are stored in dedicated data folders.

## Lexical Analysis

The lexical analyses use Python-based workflows for text preprocessing, feature extraction, and stylometric comparison.

Preprocessing includes linguistic annotation and masking procedures based on the `latin-masking` package and UDPipe.

## Metrical Analysis

The metrical analyses use metrically annotated XML texts and Python tools for the extraction and comparison of metrical features.

MQDQParser (`mqdq`) is used for processing metrically annotated Latin verse.

## Notebooks

The analyses are primarily provided as Jupyter notebooks.

Paths used in the notebooks are relative to the repository structure, allowing the project to be moved or cloned without requiring machine-specific file paths.

## Dependencies

The main Python dependencies include:

- Python
- Jupyter
- pandas
- NumPy
- scikit-learn
- matplotlib
- `latin-masking`
- `mqdq`

Additional dependencies may be required by individual notebooks.

## Data

The repository contains corpora and processed data used for the analyses. Shared datasets are stored separately from individual analysis directories where appropriate.

## Usage

Clone or download the repository, install the required dependencies, and open the relevant Jupyter notebook.

The notebooks corresponding to each text contain the specific configuration and processing steps required for that analysis.

## Acknowledgements

The lexical preprocessing workflow makes use of `latin-masking` and UDPipe.

The metrical analysis makes use of MQDQParser and metrically annotated Latin texts in XML format.
