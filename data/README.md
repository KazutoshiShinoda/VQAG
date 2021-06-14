# Synthetic Datasets

We created three synthetic datasets with our variational question-answer pair generation (VQAG) model, which is trained by maximizing the following objective:

<img width="495" alt="vqag" src="https://user-images.githubusercontent.com/16998772/121932607-05b22100-cd80-11eb-837c-fa591711548c.png">

where C_a and C_q are the hyperparameters.

Each dataset is created with VQAG using the corresponding hyperparameters as follows:

- `D_5_5.json`: (C_a, C_q) = (5, 5)
- `D_5_20.json`: (C_a, C_q) = (5, 20)
- `D_20_20.json`: (C_a, C_q) = (20, 20)

Please refer to our paper for more details about dataset construction.
