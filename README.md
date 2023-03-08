# DCC Week Challenge 2023
## Data Processing

For processing the ECG data, some libraries were used, namely: PyWT, Scipy and Biosppy. The processing code is available in the `process_dataset.ipynb` file.

## ML Model

The model used for data classification was a GBT (Gradient Boosted Trees) model called *LightGBM*. For its training, larger weights were used for the minority classes and the cross validation technique called **Stratified KFold** was also used.
The code for the model is in the `model_f.ipynb` file.

## Predictions

As predições finais selecionadas na plataforma estão presentes na pasta *output* no arquivo `lgb_v2000_final.csv`.
