# TO-DO 
- Reorder data loading at the beginning of notebook to stop crashing computers (See Crop Data on Experiment 2)
- Add Experiment 1: Grayscale
- Return true and pred from ```test_network()```

# Change Log
## 2022-05-1: Erica
### Main Code
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

### Experiment 2
- Added optional parameter ```num_pixels``` to ```negateContext()``` for (maybe) future use. Defaults to 32.
- Added ```NegateContextOfData()``` to iterate through every image in a dataset (most likely mega inefficient lol)
- Added time elapsed when loading data to Dataset just for curiosity

## 2022-05-02: Erica
### Experiment 2
- Test the original model on cropped data
- Train and test new model on cropped data
- Test new model on uncropped data

## 2022-05-02: Shikhar
### Experiment 2
- Added bar plot for accuracies