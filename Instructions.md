## Instructions for the workshop

Welcome to the "Computer Vision with Keras" live coding workshop. In this workshop we will use Keras framework to approach the [APTOS 2019 Blindness Detection](https://www.kaggle.com/c/aptos2019-blindness-detection) competition.
The code will mostly be written live and interactively. For better experience execute the following steps ~20' before the workshop:
- start a new [Colab](https://colab.research.google.com/) session
- Switch to GPU (Edit->Notebook settings -> Hardware accelerator -> GPU)
- Copy the first cells of the [main notebook](https://github.com/Machine-Learning-Tokyo/KaggleDaysTokyo2019/blob/master/kaggleDays_v2.ipynb) to your new notebook (up to the one that imports tensorflow and keras)
- Go to your kaggle account and download the API token. in the json file there is a username and a key.
- At the "Install and authenticate kaggle API" part do not run the first cell since it assumes a file in your Google Drive.
- Uncomment the "Alternatively" cell and paste your username & key and run it. If everything is correct you will be able to download the competition data at the next cell. It takes 5-10 minutes to download and extract the data.

The main idea is to have the data available at your colab session so that you don't spend time downloading them during the workshop.

Have fun!
