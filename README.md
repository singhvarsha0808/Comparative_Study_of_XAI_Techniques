# Unlocking the Black Box: A Comparative Study of Explainable AI Techniques: PDP vs ALE and, SHAP vs i-Breakdown

## Table of Contents

+ [About](#about)
    + [About The Dataset](#datasetinfo)
    + [Documentation notebook](#docnote)
    + [Key sections of the Notebook](#getting_started)
+ [Running the code](#run_locally)
    + [Code Locations](#codeloc)
    + [Configuration](#configuration)
    + [Running Jupyter](#jupyter)

## About <a name = "about"></a>

In this [notebook](https://nbviewer.org/github/singhvarsha0808/Comparative_Study_of_XAI_Techniques/blob/main/XAI.ipynb#About-the-Dataset), a comparative case study has been conducted to examine the two most common approaches to global explanation:

- [Accumulated local effects](https://arxiv.org/abs/1612.08468)
- [Partial dependence](https://christophm.github.io/interpretable-ml-book/pdp.html)

and two local explanation strategies:

- [SHAP Waterfall Plots](https://shap.readthedocs.io/en/latest/example_notebooks/api_examples/plots/waterfall.html)
- [Breakdown Interaction Plots](https://ema.drwhy.ai/iBreakDown.html)

These methods each provide distinctive insights that are essential to comprehending our models.

### Documentation notebook <a name = "docnote"></a>
This notebook comprehensively demonstrate the idea detailing each aspect. 
- [`XAI_Comparative_Study`](https://github.com/singhvarsha0808/Comparative_Study_of_XAI_Techniques/blob/main/XAI.ipynb)

### About The Dataset <a name = "datasetinfo"></a>

The [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?datasetId=1120859&language=Python) is available on Kaggle. This dataset provides information on individuals and their potential risk of stroke.

Attributes

`id`: unique identifier for each individual <br>
`gender`: gender of the individual (male or female or other)<br>
`age`: age of the individual<br>
`hypertension`: presence of hypertension (1 = yes, 0 = no)<br>
`heart_disease`: presence of heart disease (1 = yes, 0 = no)<br>
`ever_married`: marital status of the individual (yes or no)<br>
`work_type`: type of work the individual is involved in, "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"<br>
`residence_type`: type of residence the individual lives in, "Rural" or "Urban"<br>
`avg_glucose_level`: average glucose level of the individual<br>
`bmi: body mass` body mass index of the individual<br>
`smoking_status`: smoking status of the individual, "formerly smoked", "never smoked", "smokes" or "Unknown"<br>
`stroke`: whether the individual has had a stroke (1 = yes, 0 = no)<br>


## Running the code <a name = "run_locally"></a>

### Code Locations <a name = "codeloc"></a>

- The dataset is in the datasets directory
- The jupyter notebook used is the [XAI.ipynb](https://nbviewer.org/github/singhvarsha0808/Comparative_Study_of_XAI_Techniques/blob/main/XAI.ipynb#About-the-Dataset)
- Python [utils.py](https://github.com/singhvarsha0808/Comparative_Study_of_XAI_Techniques/blob/main/utils.py) file has all the functions used in notebook.
- HTML version of the notebook [here](https://github.com/singhvarsha0808/Comparative_Study_of_XAI_Techniques/blob/main/XAI.html). 
- Configuration: requirement.txt

### Configuration <a name = "configuration"></a>

Python Version - 

```
$ python -V
Python 3.9.7
```

Install the relevant packages using the following command: pip install -r requirements.txt

### Running Jupyter <a name = "jupyter"></a>

Run `jupyter notebook` and open the [XAI.ipynb](https://github.com/singhvarsha0808/Comparative_Study_of_XAI_Techniques/blob/main/XAI.ipynb) file.
