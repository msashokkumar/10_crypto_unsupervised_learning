# 10_crypto_unsupervised_learning
Cryptocurrencies clustering based on their performance in different time periods.

## Technologies

This cryptocurrency cluserting tool is a Jupyter notebook built with the following technologies:

### Language

| Language | Version |
|----------|---------|
| Python   | 3.7.11  |

### Libraries and Frameworks

| Component | Version |
|-----------|---------|
| Anaconda  | 1.9.0   |
| Conda     | 4.11.0  |
| Jupyter   | 3.2.1   |

### Operating System

This version of the software is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Python 3.7
- Anaconda 1.9.0
- Conda 4.11.0
- Jupyter 3.2.1
- A conda environment created specially for this project.

### Running the Clustering Tool

Install a new conda environment for this project. We will be using `python 3.7.11` for this repository.

```bash
conda create -n dev_unsupervised_learning python=3.7.11 anaconda
```

Activate the newly created environment and verify the python version.

```bash
conda activate dev_unsupervised_learning
python --version
```

Install and add the ipykernel environment to your jupyter notebook.

```bash
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=dev_unsupervised_learning

```

Install the required python packages.

```bash
conda install hvplot
```

Clone the remote repository to your local developer environment and `cd` into the folder.
```bash
git clone git@github.com:msashokkumar/10_crypto_unsupervised_learning.git
cd 10_crypto_unsupervised_learning
```

Start the jupyter lab server from the terminal as follows:

```bash
jupyter lab
```

Open and execute the file crypto_investments.ipynb

---
## Contributors

```markdown
{
  "name": "Ashok Kumar Madhavi Selvaraj",
  "email": "ashok.ms.kumar@gmail.com",
  "linkedin": "https://www.linkedin.com/in/msashokkumar"
}
```
---

## License

Please refer to LICENSE.