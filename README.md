# cat-translator
## Dataset credits
- The dataset can be found on https://www.kaggle.com/datasets/andrewmvd/cat-meow-classification.

## How to run
1. Install the dataset from https://www.kaggle.com/datasets/andrewmvd/cat-meow-classification.
2. Install required dependecies listed in requirments.txt.
3. Run the notebook and train the model.
4. To evaluate and compare the performance of different model weights, update the line: `new_weights_path = os.path.join(weights_dir, select_file_from_dir(weights_dir, "0"))`. Replace "0" with the appropriate number found in the desired weight file.
