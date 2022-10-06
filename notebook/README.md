# Notebook guide

## Environment setup

After cloning this repo move to the `notebook` folder and run the following commands.

The required dependencies for installing the environment can be found in the root folder `requirement.txt` file. For installing them we suggest using a [Python Virtual Environment](https://docs.python.org/3/library/venv.html).

Create a virtual environment as follows:

```bash
python3 -m venv .venv
```

this will create a folder in you current path named `.venv`. Activate the virtual environment with:

```bash
source .venv/bin/activate
```

you're now using the virtual environment, update `pip` and install the required dependencies.

```bash
pip3 install --upgrade pip
```

```bash
pip3 install -r requirements.txt
```

You can then open the notebook with:

```bash
jupyter notebook
```

or with:

```bash
jupyter-lab
```

More info on the [official documentation](https://docs.jupyter.org/en/latest/)

## Google Colab

Run this notebook in Google Colab using the following link: [Anomaly Detection on the Edge Colab](https://colab.research.google.com/github/mattdibi/eclipsecon-edgeAI-talk/blob/master/notebook/AD-EdgeAI.ipynb)

## Presentation mode

Run the Jupyter Lab server with

```bash
jupyter-lab
```

and then connect to: [http://localhost:8888/notebooks/AD-EdgeAI.ipynb#Edge-AI-Anomaly-Detection](http://localhost:8888/notebooks/AD-EdgeAI.ipynb#Edge-AI-Anomaly-Detection)
