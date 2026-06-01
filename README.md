# cat-translator
## Description
- This project uses a CNN to classify cat vocalizations into three categories: brushing, waiting for food or isolation in an unfamiliar environment. Audio recordings are processed and converted into mel spectrograms using Librosa. The dataset contains 440 recordings, which leads to overfitting because of the small sizes of training and validation data. The model achieves 65.91% accuracy and a loss of 0.6703 during evaluation.

## How to run
1. Install the dataset from https://www.kaggle.com/datasets/andrewmvd/cat-meow-classification.
2. Install required dependecies listed in requirments.txt.
3. Run the notebook and train the model.
4. To evaluate and compare the performance of different model weights, update the line: `new_weights_path = os.path.join(weights_dir, select_file_from_dir(weights_dir, "0"))`. Replace "0" with the appropriate number found in the desired weight file.

## Dataset credits
- The dataset can be found on https://www.kaggle.com/datasets/andrewmvd/cat-meow-classification.
