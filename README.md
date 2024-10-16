# ML-wine-quality-and-prices-prediction

## Using Machine Learning to predict wine quality and prices: A demonstrative case using a large tabular Database

This repository contains six Jupyter notebooks, each representing a different combination of target variable (wine quality or price) and feature selection strategy. These notebooks were developed to showcase the best models discussed in our research article titled "Using Machine Learning to Predict Wine Quality and Prices: A Demonstrative Case Using a Large Tabular Database".

### Context

The wine industry plays a significant role in the economy of many countries. In our research, we explored the prediction of wine quality and price using a large worldwide tabular database retrieved from the [Vivino platform](https://www.vivino.com/), which includes around 167,000 price records and over 4 million quality examples. Our study aimed to create predictive models that can assist various wine industry stakeholders, including producers, sellers, and consumers, by providing data-driven insights into wine quality and pricing.

### Notebooks

In the notebooks folder, you will find the following notebooks:

- [price/FS1-pricePredictor.ipynb](https://github.com/DMoreira97/ML-wine-quality-and-prices-prediction/blob/main/notebooks/price/FS1-pricePredictor.ipynb): 
    - Predicts wine price using feature selection scenario 1.
- [price/FS2-pricePredictor.ipynb](https://github.com/DMoreira97/ML-wine-quality-and-prices-prediction/blob/main/notebooks/price/FS2-pricePredictor.ipynb):
    - Predicts wine price using feature selection scenario 2.
- [price/FS3-pricePredictor.ipynb](https://github.com/DMoreira97/ML-wine-quality-and-prices-prediction/blob/main/notebooks/price/FS3-pricePredictor.ipynb):
    - Predicts wine price using feature selection scenario 3.
- [quality/FS1-qualityPredictor.ipynb](https://github.com/DMoreira97/ML-wine-quality-and-prices-prediction/blob/main/notebooks/quality/FS1-qualityPredictor.ipynb):
    - Predicts wine quality using feature selection scenario 1.
- [quality/FS2-qualityPredictor.ipynb](https://github.com/DMoreira97/ML-wine-quality-and-prices-prediction/blob/main/notebooks/quality/FS2-qualityPredictor.ipynb):
    - Predicts wine quality using feature selection scenario 2.
- [quality/FS3-qualityPredictor.ipynb](https://github.com/DMoreira97/ML-wine-quality-and-prices-prediction/blob/main/notebooks/quality/FS3-qualityPredictor.ipynb):
    - Predicts wine quality using feature selection scenario 3.

Each notebook contains the necessary code to train and test the models based on different feature selection scenarios, which consider various sets of input features such as wine characteristics, [Vivino platform](https://www.vivino.com/) data, and user-generated data.

### Data Privacy and Limitations

- Data Privacy: Due to data ownership restrictions, the datasets used in these notebooks are encoded. This ensures that the data and models cannot be used for commercial purposes.
- Data Limitations: The datasets provided are intentionally small and may not generalize the results as effectively as the original larger datasets used in the research. The purpose of these small datasets is to demonstrate the modeling process without exposing sensitive or proprietary data. As a result, the predictive performance might be lower than reported in the research article.

### Usage

To test the models, follow these steps:

Clone the repository:

```console
foo@bar:~$ git clone https://github.com/your-username/wine-quality-price-prediction.git
foo@bar:~$ cd wine-quality-price-prediction/notebooks
foo@bar:~$ pip install -r requirements.txt
foo@bar:~$ jupyter <notebook>
```

### Conclusion

This repository provides a practical implementation of the predictive models discussed in our research. While the provided datasets are limited in size, they serve as a valuable demonstration of the modeling techniques and their potential applications in the wine industry. We hope this repository aids in understanding the process and encourages further exploration and development of machine learning models in this domain.

For more details on the research and results, please refer to our article "Using Machine Learning to Predict Wine Quality and Prices: A Demonstrative Case Using a Large Tabular Database".