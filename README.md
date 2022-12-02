# CSE598 Group Project
*Fall-2022 (CSE 598: INTRODUCTION TO DEEP LEARNING)*

*Group 12*
* [Venkatesh Gunda](https://github.com/venkate5hgunda)
* [Varsha Ravindra](https://github.com/Varsha-R)
* [Sujana Duvvuri Venkateswarlu](https://github.com/sduvvur7)

## INSTRUCTIONS:
* For Downloading the Data, there are two options:
  * Either download the [Official Kaggle Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset) and run all pre-processing Steps, 
  * (or) Download this [Folder](https://drive.google.com/drive/folders/124HOux2P2m1PyKB0C5_SnBxl_lTN4pvG?usp=sharing) into your Dataset Folder
* Once Downloaded, organize the folders in the following way: 
  * For Google Colab:
    ```
    DriveRoot/
      Colab Datasets/AnimeFacesDataset/ -> (Dump the previously downloaded Data Files in here)
      Colab Models/CSE598_GroupProject/[MODEL_NAME].pt -> (Model Root Directory, .pt for PyTorch Models)
      Colab Results/CSE598_GroupProject_[MODEL_NAME]/ -> (Each Model Results is its own directory)
      [NoteBooks]
    ```
   * For Local (or) Custom Environment:
     ```
     Code/
        Data/
        Models/
        Results/
        [NoteBooks]
     ```
* Once the Project Organization is Done, ensure the paths are set correctly as mentioned in the [Diffusion Model Notebook](https://colab.research.google.com/drive/1p9jPcfo6gIRQbRSQGVcCh0_pudpF7QHW#scrollTo=CA7a_TR8h_3j&line=3&uniqifier=1).

* The Jupyter Environment in Google Colab has all the necessary packages for Baseline & Diffusion Models. The few additional packages necessary are installed using inline `pip install xxxxx` commands, so no additional setup is necessary to run the code.
* Click on the Link (or Upload the Notebook) and Connect to a GPU Colab Instance (CPU Works, but it is very slow), or a GPU Environment.

## ADDITIONAL RESOURCES:
### NOTEBOOK LINKS:
* Baseline Model Jupyter Notebook: [Link](https://colab.research.google.com/drive/1pwrK0NQtamiWkEWdlC6m8WenJnQp4var?usp=sharing)
* Diffusion Model Jupyter Notebook: [Link](https://colab.research.google.com/drive/1p9jPcfo6gIRQbRSQGVcCh0_pudpF7QHW?usp=sharing)
* DCGAN with 50 epochs Kaggle Notebook: [Link](https://www.kaggle.com/code/patrocharm/dcgan-15k-50-epochs)
* DCGAN with 300 epochs Kaggle Notebook: [Link](https://www.kaggle.com/patrocharm/dcgan-15k-300-epochs)

### MODEL LINKS:
* Baseline DCGAN Model: [Link](https://drive.google.com/drive/folders/1i4_4soLUGullCS5ioMxT10kbOtf4nEWz?usp=sharing)
* Diffusion Model: [Link](https://drive.google.com/drive/folders/1q1jn6r8smsGKxrxkNN2G9eodMUbUOhd8?usp=share_link)

### RESULTS LINKS (Generated Samples):
* Baseline DCGAN & Diffusion Models: [Link](https://drive.google.com/drive/folders/1-0UbtOwF8sD6vOUnmLrpb9XxsCWSoZbp?usp=sharing)
