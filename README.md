# Thinkful Data Science Flex Course
# Final Capstone Project: Classification of Observed Astronomical Objects

**Project Description**

- Developed supervised learning models to predict whether objects observed from a ground-based telescope are stars, galaxies, or quasars.
- Compared performance of four model types: logistic regression, decision tree, random forest, and artificial neural network.
-	Built models using Python, pandas, scikit-learn, and TensorFlow in a Jupyter notebook.

**Source Data**

The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17) and is in the form of a 16 MB csv file with 100,000 rows and 18 columns.
- The data come from the Sloan Digital Sky Survey (SDSS), which uses an on-the-ground optical telescope in New Mexico.
- There are 17 feature columns, and 1 column indicating the known classification as a star, galaxy, or quasar. 
- These features included quantities measured from images and spectra such as magnitudes and redshifts.
- The 100,000 rows we are using here are a subset, because there are image and spectra data for approximately 0.5 × 10<sup>9</sup> and 3 × 10<sup>6</sup> objects, respectively.

The data file is available [here](https://raw.githubusercontent.com/JosephMartin610/thinkful_data_science_flex_data_files/main/star_classification.csv) in another repository.

**Jupyter Notebook**

All of the code and results are in one Jupypter notebook, [final_capstone_astro_classification.ipynb](https://github.com/JosephMartin610/thinkful_data_science_flex_astronomical_classification/blob/main/final_capstone_astro_classification.ipynb).

**Presentation**

The development and performance of the models are described here in the capstone [presentation](https://github.com/JosephMartin610/thinkful_data_science_flex_astronomical_classification/blob/main/final_capstone.pdf).
