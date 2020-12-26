Download the raw dataset from the link:
https://www.kaggle.com/praveengovi/coronahack-chest-xraydataset

After unzip it, upload the unzipped folder to your google drive, by default it is named: 'Coronahack-Chest-XRay-Dataset'.

Now, upload the script(.ipynb or .py) to your google colab account, make sure to change your runtime type to 'GPU' hardware accelerator. 


Run the line from the first cell: 

from google.colab import files, drive

drive.mount('/content/drive')


Click the link that popped up, click the google drive where you save the unzipped folder, and click to accept their terms and warnings.

Now you can run all the script. 