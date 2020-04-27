# SemEval 2020 - Task 10: Emphasis Selection For Written Text in Visual Media

# Installation
```
git clone https://github.com/SahilDhull/emphasis_selection.git
cd emphasis_selection
pip install -r requirements.txt
```

### Team 'Corona Survivors':
- Rishabh Agarwal
- [Sahil Dhull](https://sahildhull.github.io/)
- Vipul Singhal

#### Under the guidance of:
[Prof. Ashutosh Modi](https://ashutosh-modi.github.io/)

## Problem Statement
The problem statement ([Task 10 in SemEval-2020](https://competitions.codalab.org/competitions/20815)) is designing automatic methods for emphasis selection i.e. choosing candidates for emphasis in short written text.

More formally,
Given a sequence of words or tokens C = <img src="https://render.githubusercontent.com/render/math?math=\{ x_1, x_2, ..., x_n \}">, we want to compute a score <img src="https://render.githubusercontent.com/render/math?math=S_i"> for each <img src="https://render.githubusercontent.com/render/math?math=x_i"> which indicates the degree of emphasis to be laid on the word.

## Directory Structure
datasets/ - contains the train and development sets

BiLSTM + Attention Approach/ - contains the model for this approach

Transformers Approach/ - contains model and ensemble files for this approach

requirements.txt - contains versions of packages required