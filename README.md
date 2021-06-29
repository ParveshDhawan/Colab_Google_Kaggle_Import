# Colab_Google_Kaggle_Import
Using Google Colab importing Kaggle Data set :-)


Importing kaggle data set into colab directly.
Change the credential


Without Json File : 
## https://www.kaggle.com/general/74235
# To download and unzip the dataset in one go:

# you can copy the required dataset URL suffix which is found after "kaggle.com/". Let's call it url_suffix here
# OR just click the kabab menu beside the download button from the dataset page and click copy the API command.
# Then run the below line to download it into the sample_data Colab folder:
# !kaggle datasets download *url_suffix* -p /content/sample_data/ --unzip

#Data set Sample : https://www.kaggle.com/snap/amazon-fine-food-reviews
!kaggle datasets download snap/amazon-fine-food-reviews -p /content/sample_data/ --unzip
