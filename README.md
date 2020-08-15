# sign_detection
## X_c1.np
The dataset features i.e the images are found at this link https://drive.google.com/file/d/1I3pC0m6i5ucaGsLwn3sOD_zjM5-fng55/view?usp=sharing.(space,space)
## Y_c1.np
The dataset corresponding labels i.e the digits are found at this link https://drive.google.com/file/d/1qzLJKQHbSEHd4rBydKZ4jb6n1d83mGaq/view?usp=sharing.(space,space)
## Main file
The sign_detection.ipynb contains step step process to run, train and test the model. (space)
We first load the dataset and split it into train and test. Since we have multi class it is better to have a test dataset with equal amount of samples in each class. (space)
Next we build the model architecture. The architecture is built using residual blocks and dialated cnns.(space)
We then train the model with bactch size =8, with decay learning rate till 40 epochs. (space)
Next the trained model is tested and different evaluation metrics are shown.(space)
Next we save our trained model in .h5 format, it can be stored in .hdf5 format too. (space)
We then convert the tensorflow model saved in .h5 format to tensorflow lite version to speed up the inference time. (Note : if you save the tf model in .hdf5 format then first convert that to .h5 format before coonverting into tf lite version). (space,space)

## Trained model
The trained model can be found at this link https://drive.google.com/file/d/1-SYSo8_g4aTh58cktmPfNnq8i6IK_GGb/view?usp=sharing. (space, space)

## The overview of the system

