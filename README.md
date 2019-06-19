# Interactive Football Pitch Using Jupyter Voila
[Jupyter voila](https://blog.jupyter.org/and-voil%C3%A0-f6a2c08a4a93) allows to serve Jupyter notebooks, and especially ipywidgets, as standalone applications.
This repository contains an example notebook which uses `qgrid` and `bqplot` to create a simple interactive football pitch.
You can test it live in Binder or run it locally.  

The deployed notebook can be found here: [Notebook on Heroku](https://voila-football-pitch-example.herokuapp.com/)  
(Be patient, it might need some time to spin up the dyno on Heroku.)

## Voila in Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/voila-interactive-football-pitch/master?urlpath=voila%2Frender%2FInteractive-Football-Pitch.ipynb)


## Notebook in Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/seidlr/voila-interactive-football-pitch/master?filepath=Interactive-Football-Pitch.ipynb)

## Local installation
To run the example notebook, first create a `conda` environment.
```bash
conda env update
```
This creates an environment `voila-football-pitch` which can be used in a jupyter notebook.
Next, activate the environment and start the voila server.
```bash
conda activate voila-football-pitch
```
```bash
voila
```
or run the notebook by
```
voila Interactive-Football-Pitch.ipynb
```

## Deployment on Heroku
You can easily deploy the notebook to Heroku following these steps: 
First, follow the setup steps on Heroku: [here](https://devcenter.heroku.com/articles/getting-started-with-python)
Then run
```bash
heroku create
git push heroku master
```



