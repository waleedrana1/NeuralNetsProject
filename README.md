# TO-DO 
- Add Experiment 1: Grayscale
- Complete Experiment 2: Perimeter Masking

# Change Log
## 2022-05-1: Erica
- Seeded the notebook to keep consistency between runs.
- Lowered the amount of training/validation/testing data used. It still loads all the data, it just truncates the amount used.
- Deleted all the coments inside the TissueCNN class
- Added more information about train/val/test data when loading
- Made epochs go through whole training data
- Changed the number of batches: 64 -> 256
- Validation checks all the batches in the validation set
- Fixed validation so that it actually checks the validation set
- Deleted test function within the training function
- Changed learning rate: 0.0001 -> 0.00005
- Changed ```test_network()``` to return accuracy
