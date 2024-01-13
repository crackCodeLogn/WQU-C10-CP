# Statistical Analysis of Financial Markets
# 23/10 MScFE Capstone Project: G4532

- **Instructor:** Professor Saad Zaman
- **Contributors:**
  
    | Contributor Name | Country                    |
    |------------------|----------------------------|
    | Harsha Chaube    | United Kingdom             |
    | Vivek Verma      | Canada                     |
    | Chen Liang       | United States of America   |

## Abstract

The analysis involves studying time series datasets of 3 major cryptocurrencies - Bitcoin (BTC), Ethereum (ETH), and Binance (BNB), denominated in US Dollars at the Crypto Exchanges, between November 09, 2017 and November 13, 2023. To identify various regions of the market, multiple models such as Clustering, GMM, HMM, and MSM are utilized, which apply a wide range of logic including combination of univariate autoregressive and dependent mixture mode, in order to classify the behavior of the cryptocurrencies within the 3 hidden state regime - Bull, Bear, Stagnant.

## Running the Notebook

- Basic prerequisite: Python 3.7+

### 1. On Google Colab
- No explicit changes required, the cloud colab will be able to resolve the dependencies and run the notebook as is.

### 2. On Local System
- For local system, the requirements.txt needs to be run before attempting to run the notebook.

  To install the required dependencies, run:

  ```bash
  python -m pip install -r requirements.txt

- Then to start the local jupyter, run the following command in terminal having the present working directory being the one where the ipynb is located :

  ```bash
  jupyter notebook

  
