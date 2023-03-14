<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://static.javatpoint.com/tutorial/machine-learning/images/machine-learning-life-cycle.png" alt="Project logo"></a>
</p>

<h3 align="center">End To End Machine Learning Project Deployment</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Project: End to end Machine Learning Deployment
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

Learn how to complete machine learning project for deployment!

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Create a Git repo and virtual env.
```

### Installing

A step by step series of examples that tell you how to get a development env running.
To create the virtual environment
```
conda create -p venv python==3.9 -y
conda activate <path/to/folder>/venv
```

And then clone your git repo

```
git init
git add README.md
git commit -m "first commit" 
git push -u origin main
```
Also, add .gitignore then:

```
git pull origin main
touch setup.py
touch requirements.txt
mkdir src
touch src/__init__.py
mkdir src/components
touch src/components/__init__.py
touch src/components/data_ingestion.py
touch src/components/data_validation.py
touch src/components/data_transformation.py
touch src/components/model_trainer.py      
mkdir src/pipeline  
touch src/pipeline/train_pipeline.py       
touch src/pipeline/predict_pipeline.py
touch src/pipeline/__init__.py        
touch src/logger.py           
touch src/exceptions.py
touch src/utils.py
```

Example of getting some data out of the system for a little demo.

## 🔧 Running the tests <a name = "tests"></a>

To run the code after activating the venv and following the code line by line run:
```
python src/components/data_ingestion.py 
```

### End to end tests

Apply all possible regression model and find/keep the best performing model for predicitng the math_score.

```
python src/components/data_ingestion.py 
```
Got r2_score of near 0.87

### And coding style tests

Pick the best performing model for your project objective.

## 🎈 Usage <a name="usage"></a>

Above code can be used and tested with the command shared above.

## 🚀 Deployment <a name = "deployment"></a>

TODO: Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [Python](https://www.python.org/) - Python Programming Language
- [Sklearn](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning) - Sklearn


## ✍️ Authors <a name = "authors"></a>

- [@RILUCK](https://github.com/RILUCK) - Idea & Initial work
- [@Linkedin](https://www.linkedin.com/in/rishabhshrivas/) - Rishabh Shrivas : Linkedin Profile

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Keep hustling!
