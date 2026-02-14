# Application-Projects-MUTSC


Material used for teaching about **Application Projects (APPR)** in MUTSC (ETSIT-UPM). This repository focuses on the core concepts of **Survival Analysis** and handling **Censoring Data**.

## Repository Structure

### Datasets

The `Datasets/` folder contains the raw data used for the practical exercises:

* `BrainCancer.csv`: Survival times for patients with primary brain tumors.
* `Publication.csv`: Data investigating publication bias and the time-to-publication for clinical trials.

### Notebooks

The `Notebooks/` folder contains step-by-step implementations using the `lifelines` library in Python. You can access them directly here:

* **[Brain Cancer Analysis](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Notebooks/BrainCancer.ipynb)**
* **[Publication Bias Analysis](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Notebooks/Publication.ipynb)**

## Execution in Google Colab

The recommended way of executing these codes is to use **Google Colab**. This ensures that all dependencies are handled in a cloud environment.

### How to open via GitHub:

1. Go to [Google Colab](https://colab.research.google.com/).
2. In the **Open** dialog box, select the **GitHub** tab.
3. Enter the URL of this repository.
4. Add this repository and select the desired notebook (`.ipynb`) to start working.

### Alternative: Local Execution

Finally, you can also download the code and execute it locally. If you choose this option, ensure you have Python installed along with the required dependencies:

```bash
pip install lifelines pandas numpy matplotlib

```
