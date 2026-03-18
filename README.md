# Application-Projects-MUTSC

Material used for teaching about **Application Projects (APPR)** in the Master’s Degree in Signal Theory and Communications (MUTSC) at ETSIT-UPM (Escuela Técnica Superior de Ingenieros de Telecomunicación, Universidad Politécnica de Madrid).

## Contributors & Contact

**Contributors:**
- Patricia A. Apellániz (patricia.alonsod@upm.es)
- Alba Garrido (alba.garrido.lopez@upm.es)

## Repository Structure
This repository focuses on the core concepts of **Survival Analysis** and handling **Censoring Data**.

### Datasets

The `Datasets/` folder contains the raw data used for the practical exercises:

* `BrainCancer.csv`: Survival times for patients with primary brain tumors.
* `Publication.csv`: Data investigating publication bias and the time-to-publication for clinical trials.

### Exercises

The `Exercises/` folder contains a notebook with practical applications and questions:

* **[Exercises Survival Analysis](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Exercises/Exercises_Survival_Analysis.ipynb)**

### Material

The `Material/` folder contains the lecture slides used throughout the course:

* **[Application Projects](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Material/Application_Projects.pdf)**: Real-world applications
* **[Glossary](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Material/Glossary.pdf)**: Glossary of key concepts used in survival analysis
* **[Seminar Project](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Material/Seminar_Project.pdf)**: Explanation of the proposed project
* **[Survival Analysis](https://github.com/AlbaGarridoLopezz/Application-Projects-MUTSC/blob/main/Material/Survival_Analysis.pdf)**: Theoretical foundations of survival analysis
  
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
