# Data Science Capstone Project

## Project Description

This project is part of the Data Science Foundations to Core Career Track Capstone Two: Data Wrangling. The goal of this project is to collect, organize, define, and clean data from The MET API for further analysis and exploration.

## Dataset

The dataset used in this project is obtained from The MET API, which provides metadata about artworks from The Metropolitan Museum of Art. The dataset includes information such as object IDs, image URLs, and other relevant metadata about the artworks.

## Setup

# first clone the repository
git clone <repository_url>

# navigate the the repository
cd path/to/the/repository

# create the virtual environment in a folder named venv
python3 -m venv venv

# start using the environment
source venv/bin/activate

# updgrade pip and install dependencies
pip install --upgrade pip
pip install -r main/requirements.txt

# install kernel for jupyter notebook
# this allows you to use this virtualenv in the notebooks
ipython kernel install --user --name=arart

# to deactivate the environment after use
deactivate

## Project Steps

### 1. Data Collection
- Use The MET API to fetch metadata about artworks.
- Save the metadata to a CSV file (`metdata.csv`).

### 2. Data Organization
- Create a directory structure for the project.
- Add the `metdata.csv` file to the project's GitHub repository.

### 3. Data Definition
- Analyze column names, data types, description, counts, unique values, and ranges of the dataset.

### 4. Data Cleaning
- Handle missing values and duplicates in the dataset.
- Save the cleaned data to a new CSV file (`metdata_cleaned.csv`).

## Project Setup

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Execute the Jupyter notebook:

```bash
jupyter notebook
```

4. Follow the steps outlined in the notebook to perform data wrangling tasks.

## Author

Syed Hussain Ather

## License

This project is licensed under the [MIT License](LICENSE).

