# Dysphagia Pneumonia

This GitHub repository contains the code used for the clustering analysis and scoring system development in the paper "Multifeature endoscopic swallowing patterns associated with pneumonia in hospitalized geriatric patients: A four-year longitudinal cohort study".

## Project Overview

pending

## Key Messages

pending

## Scoring System

pending

## Repository Structure

- [`analysis.ipynb`](./analysis.ipynb): Feature extraction and clustering analysis
- [`data.xlsx`](./data.xlsx): Data from the dysphagia study in geriatric patients
- [`environment.yml`](./environment.yml): Virtual environment used for the analysis
- [`LICENSE`](./LICENSE): License for this project (MIT License, as per the project's uniform approach)
- [`roc_curve.png`](./roc_curve.png): Receiver operating characteristics curve of the scoring system
- [`clustering_score.xlsx`](./clustering_score.xlsx): Sensitivity and specificity of the scoring system with respect to cut-off
- [`endpoints.xlsx`](./endpoints.xlsx): Associations between the scoring system and clinical outcomes

## Explore the Analysis:

Open [`analysis.ipynb`](./analysis.ipynb) in GitHub to inspect the clustering analysis and scoring score development.

It is possible to download or clone the repository and create a virtual environment using conda. \
The data is included in data.xlsx, allowing the full analysis notebook to be rerun.

### Cloning the Repository
1. Open a terminal or command prompt.
2. Run the following command to clone the repository:
   ```
   git clone https://github.com/IfGF-UUlm/dysphagia-pneumonia.git
   ```
3. Navigate into the repository directory:
   ```
   cd dysphagia-pneumonia
   ```

### Setting Up the Environment
This repository includes an `environment.yml` file for creating a Conda environment with the required dependencies.

1. Ensure you have [Conda](https://docs.conda.io/en/latest/) installed.
2. Create the environment using:
   ```
   conda env create -f environment.yml -n dysphagia-pneumonia-env
   ```
3. Activate the environment:
   ```
   conda activate dysphagia-pneumonia-env
   ```

#### The analysis utilizes:
- Python 3.x
- numpy
- pandas
- scipy
- matplotlib
- scikit-learn (sklearn)
- Other dependencies as listed in `environment.yml`

To explore the analysis, open the main notebook (e.g., `analysis.ipynb`) in Jupyter Notebook or JupyterLab after setting up the environment.

## License

This project is licensed under the MIT License.

## Citation

The manuscript is currently undergoing peer review and will be added once published.

## Contact

Questions, Feedback, or Concerns? Reach out to thomas.kocar@uni-ulm.de.
