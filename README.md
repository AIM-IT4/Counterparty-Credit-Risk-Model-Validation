# Counterparty-Credit-Risk-Model-Validation

This project aims to demonstrate the process of validating counterparty credit risk models used for Pillar-I, CCAR, IFRS-9, and internal stress testing. The project uses a hypothetical dataset of 100 counterparties, each with attributes such as Exposure at Default (EAD), Probability of Default (PD), Loss Given Default (LGD), industry, country, and rating.

**Overview**
The project is structured as follows:

Data Generation: We start by generating a hypothetical dataset of 100 counterparties with attributes such as EAD, PD, LGD, industry, country, and rating.

Pillar-I: We calculate the capital requirement for Pillar-I using the formula Capital Requirement = EAD * PD * LGD * 12.5.

CCAR (Comprehensive Capital Analysis and Review): We perform a stress test under a scenario involving a 50% increase in PD and a 20% increase in LGD, and calculate the stressed capital requirement.

IFRS-9: We calculate the expected credit loss as the product of EAD, PD, and LGD.

Internal Stress Testing: We perform a stress test under a scenario involving a 100% increase in PD and a 50% increase in LGD, and calculate the stressed capital requirement.

Visualizations: We create various visualizations to explore the data and the results of the calculations.

**Note**
This is a simplified version of the model validation process and may not cover all the intricacies involved in each process. The regulatory requirements can vary greatly depending on the specific jurisdiction and the exact nature of the models and processes involved.

**Usage**
You can run the notebook in this project to go through the process step by step. The notebook includes detailed comments explaining each step.

**Dependencies**
This project requires Python and the following Python libraries installed:

NumPy
Pandas
Matplotlib
Seaborn
You will also need to have software installed to run and execute a Jupyter Notebook.
