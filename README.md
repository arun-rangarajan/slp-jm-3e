# Speech and Language Processing

Python code for the eminent book on natural language processing (NLP) by Dan Jurafsky and James H. Martin.

As of today (2024-01-19), the book has a third edition draft available [here](https://web.stanford.edu/~jurafsky/slp3/). The draft has been last updated on 2023-01-07, a little over a year ago. I hope the book is completed and the 
print edition comes out soon. But until then, thanks to Prof. Jurafsky for making the draft available. This repository is an attempt to code up the relevant sections of the book in Python.

## Project setup

I like conda environments. I also like to name my conda environments the same as the project so it's easy for me to use the correct one with each project. So I fire up Anaconda prompt and run:

```
conda create -n slp-jm-3e python=3.10
```

Once that completes, activate it by:

```
conda activate slp-jm-3e
```

## Jupyter notebooks

Jupyter notebooks are best for interactive development. So let's get our conda environment registered with Jupyter. 

```
conda install -y -c anaconda ipykernel
python -m ipykernel install --user --name=slp-jm-3e
```

Now I can start Jupyter notebook from Windows start menu and select `slp-jm-3e` as the kernel.

I also like to use the Anaconda prompt command line to install any new packages, so will add those as I go along.

