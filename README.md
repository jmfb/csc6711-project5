# CSC6711 Project 5: Content-Based Filtering

## Local Setup

Download the datasets from [BoardGameGeek on Kaggle](https://www.kaggle.com/datasets/threnjen/board-games-database-from-boardgamegeek?resource=download)
to the `datasets` directory.


Install the latest versions of dependencies via chocolatey

```PowerShell
& choco install python
```

Configure a python virtual environment for the class (from the project directory):

```PowerShell
& python -m venv msoe
& ./msoe/Scripts/activate.ps1
& python -m pip install -U pip wheel
& pip install -r requirements.txt
```

And to run the notebooks:

```PowerShell
& ./msoe/Scripts/activate.ps1
& jupyter notebook
```
