Face attribute classification by Gavrilova Anna, Zink Ruben

Introduction

We are developing a deep learning model employing Convolutional Neural Networks (CNNs) to accurately categorize facial features such as age, gender, facial hair, eyeglasses and headwear. This is a multi-label problem, so one image can have multiple labels. This neural network can be used, to make observation about people based on their appearance.
Our work is based on the knowledge we gained in Deep-Learning courses including the knowledge about CNN's, basic and fundamental studies about Al and machine training. Besides, we are using some extra information from various sources.

Instructions how to run the code:
1. Go to our github repository and download our code named "celeba project.ipynb"
2. Go to our github repository and download data.csv file which contains corresponding labels. It is given in the directory named "img_align_celeba"
3. You have to install the required packages. The requirements are provided in a separate .txt file named "requirements.txt" which you can find in the root directory of the project
4. Run the code

Additional information:
Regarding the data downloading, we are using keras generators. This way of dataset loading seemed to be highly efficient as we are having a large amount of data.

Sources:
https://www.tensorflow.org/tutorials/images/cnn?hl=ru
https://keras.io/api/layers/convolution layers/
https://www.mdpi.com/2313-433X/8/4/105
https://stanford.edu/~shervine/blog/keras-how-to-generate-data-on-the-fly
