# CANTEMIST-NET

Recognai's contribution to the [CANTEMIST](https://temu.bsc.es/cantemist/) NER track.

### NER_dataprep.ipynb

Used for the data preprocessing. This repo does not contain the original data set. It can be obtained from the CANTEMIST homepage.
If you want to use the notebook, please store it under `data`.

### train_fasttext_model.ipynb

Used for training our fasttext model. The HPO runs are not included in the notebook!

### train_xlmr_model.ipynb

Used for training our xlmr model. The HPO runs are not included in the notebook!

### predictions.ipynb

Used to create our submitted predictions.

### submitted_models

Contains the `model.tar.gz` files used in the `predictions.ipynb` notebook.