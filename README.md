# epos_IS
Follow these steps to run EPOS on the IndustryShapes dataset.

##
Apply some non-critical changes to the EPOS repo:

```
cd epos
git apply ../diff.patch
```
Follow the instructions in the EPOS repo to set it up.

## Dataset
Download the IndustryShapes dataset in BOP format [here](https://huggingface.co/datasets/POSE-Lab/IndustryShapes).  

## Data preparation

The IndustryShapes dataset provides BOP formated data. No preprocessing is needed. 

## Training and Inference

Follow the instructions here to setup EPOS for training and inference. If you only want to perform inference and replicate our results in the IndustryShapes dataset you can download the pre-trained weights from [here](https://ntuagr-my.sharepoint.com/personal/mpateraki_ntua_gr/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fmpateraki%5Fntua%5Fgr%2FDocuments%2FIndustryShapes%5Fweights&ga=1).
We also provide the [params.yaml](https://github.com/POSE-Lab/epos_IS/blob/main/params.yaml) needed for training and inference.
