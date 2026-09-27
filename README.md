## Description

This repo contain exercises and answers for the first part of the AI course

## Setup

Tested with Python 3.14.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Each chapter folder (`kap1`-`kap6`) has a `questions.ipynb`. Run the notebooks from their own folder, since data is read from `data/` relative to the notebook. Chapters 2 and 4 download datasets (California housing and seaborn's mpg in chapter 2, MNIST in chapter 4) the first time they run, so they need internet access.
