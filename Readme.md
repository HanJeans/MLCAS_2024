# MLCAS 2024 / GDSL
## This repository provides all file and code involved in our competition outcome. 


### Dataset
Before we start, we should upload every files. 
Unfortunately we are not able to upload whole data due to capacity issue. 
Please upload raw data to following directory.
 * data for 2022
   * train_Ground_truth_2022 :
     * '/data/MLCAS2024/EvalAI/data/train/2022/DataPublication_final/GroundTruth/HYBRID_HIPS_V3.5_ALLPLOTS.csv'
   * train_Data_aquisition_time_2022 :
     * '/data/MLCAS2024/EvalAI/data/train/2022/DataPublication_final/GroundTruth/DateofCollection.xlsx'
   * train_Satellite_2022 :
     * '/data/MLCAS2024/EvalAI/data/train/2022/DataPublication_final/Satellite'

 * data for 2023
   * train_Ground_truth_2023 :
     *'/data/MLCAS2024/EvalAI/data/train/2023/DataPublication_final/GroundTruth/HYBRID_HIPS_V3.5_ALLPLOTS.csv'
   * train_Data_aquisition_time_2023 :
     *'/data/MLCAS2024/EvalAI/data/train/2023/DataPublication_final/GroundTruth/DateofCollection.xlsx'
   * train_Satellite_2023 :
   * *'/data/MLCAS2024/EvalAI/data/train/2023/DataPublication_final/Satellite'

 * validation data 
   * val_Ground_truth :
     * '/data/MLCAS2024/EvalAI/data/validation/2023/GroundTruth/val_HIPS_HYBRIDS_2023_V2.3.csv'
   * val_Data_aquisition_time :
     * '/data/MLCAS2024/EvalAI/data/validation/DateofCollection.xlsx'
   * val_Satellite :
     *'/data/MLCAS2024/EvalAI/data/validation/2023/Satellite'

 * test data
   * test_Ground_truth :
     *'/data/MLCAS2024/EvalAI/data/test/Test/GroundTruth/test_HIPS_HYBRIDS_2023_V2.3.csv'
   * test_Data_aquisition_time :
     *'/data/MLCAS2024/EvalAI/data/validation/DateofCollection.xlsx'
   * test_Satellite :
     *'/data/MLCAS2024/EvalAI/data/test/Test/Satellite'

Your outpur file would be generated based on your current directory. 
 * out csv file path and name
   * fn_out_final_validation :
     *'./validation_result_forsubmission.csv'
   * fn_out_final_test :
     *'./test_result_forsubmission.csv'

### Code

Python Based Code

### Reference
We have brought model named PheGeMi referring to ["Multi-modal deep learning improves grain yield prediction in wheat breeding by fusing genomics and phenomics (M. Togninalli, et al., 2023)"](https://gdsl.org), and [source code](https://github.com/BorgwardtLab/PheGeMIL).

### Code implementation

We need to install all required package to run the code. Be careful: anaconda does not support some required package, so user should use pip only. 

```
pip install numpy rasterio affine test-tube pytorch pytorch-lightning seaborn pot pandas pillow scikit-learn
```

### Code Procedure
 1. Import packages
 2. Load the input data and read csv and xlsx files with Pandas
 3. We have matched each csv row and corresponding TP values
 4. 
```python

```
 5. d
```python

```
 6. d
```python

```
 7. d 
```python

```





