# Deep Residual Time Series Forecasting

Implementation of architecture for our 2020 OhioT1D competition submission. Includes weights from pre-training runs with Tidepool data set. 

The baseline architecture is N-BEATS (https://arxiv.org/abs/1905.10437), modifications include using blocks with an RNN and shared outputs, the use of additional variables, and additional Losses.

drtf.py contains all code for analysis

convert_data.py converts raw competition data into a format suitable for drtf.py to read

PRETRAINS.txt contains links to download pretraining weights derived from the tidepool database (https://www.tidepool.org/)