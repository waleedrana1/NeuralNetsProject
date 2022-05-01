# TO-DO

- Change training loop to do epochs correctly
    - Make epochs go through whole training data
    - Refactor validation check in the training loop
    - Change stuff until accuracy > 70% again. 
- Change ```test_network()``` to return accuracy

# Change Log
## 5/1/22
- Seeded the notebook to keep consistency between runs.
- Lowered the amount of training/validation/testing data used. It still loads all the data, it just truncates the amount used.
- Deleted all the coments inside the TissueCNN class