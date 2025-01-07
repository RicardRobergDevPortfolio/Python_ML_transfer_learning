# Python_ML_transfer_learning

Language: Python
Environment: Jupyter Notebook
Libraries: Tensorflow, Numpy, Keras, Matplotlib

The .ipynb file contains the explanation of the exercise.
This README will add the HOWTO, implementations, fixes, and workarounds.

## Set environment

Create a Python environment, install libraries, and set up the environment kernel in Jupyter Notebook.

```prompt
python -m venv env_name
./activate
python -m pip install --upgrade pip

pip install numpy keras matplotlib tensorflow tensorflow-gpu

pip install ipykernel

python -m ipykernel install --user --name env_name
```

1) If you want to use a different dataset, adjust cell 4 and the last one to match your dataset.
2) If you don't have enough computing power and want to reduce the number of images in your dataset, uncomment cell 5 and change the value of X to the number of images to remain in each folder.
3) If you don't have enough computing power and want to reduce the number of images in your dataset, uncomment cell 5 and change the value of X to the number of images to remain in each folder.
      1) You can also reduce the batch size and epochs in cells 26 and 45 (both 3 and 3.1 will significantly decrease the training and prediction accuracy).
5) Remember to change the file name and path in the last cell to reflect the image you want to predict.
