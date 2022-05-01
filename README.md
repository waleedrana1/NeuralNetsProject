# TO-DO
- Change training loop to do epochs correctly
    - Refactor validation check in the training loop
    - Change stuff until accuracy > 70% again. 
- Change ```test_network()``` to return accuracy
- Add Experiment 1: Grayscale
- Complete Experiment 2: Perimeter Masking

# Change Log
## 5/1/22
- Seeded the notebook to keep consistency between runs.
- Lowered the amount of training/validation/testing data used. It still loads all the data, it just truncates the amount used.
- Deleted all the coments inside the TissueCNN class
- Added more information about train/val/test data when loading
- Made epochs go through whole training data
- Changed the number of batches: 64 -> 256
- Validation checks all the batches in the validation set
- Fixed validation so that it actually checks the validation set
- Deleted test function within the training function
