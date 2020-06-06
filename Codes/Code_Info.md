1.  **Preprocessing_and_Feature_Extraction.ipynb** 

    **Input**: Alert and Drowsy Videos 
    
    **Output**: Label + features
    
   All four files were used to create Merged_data.csv
    
        1.1) 6_Participants_ In_First_Zip_File.csv 
        
        1.2) 5_Participants_In_Fourth_Zip_File.csv
        
        1.3) 6_Participants_In _Third _Zip_File.csv
        
        1.4) 5_Participants_In _Second_Zip_File.csv 

2.  **Normalization.ipynb** 

    **Input**: Merged_data.csv 
    
    **Output**: 
    
        2.1) final_with_main_features.csv
        
        2.2) total_with_all_information.csv

3.  **Classification_models.ipynb** 

    **Input**:final_with_main_features.csv
    
    **Output**:
    
        3.1)   3.1.1)   accuracy
               3.1.2) f1 score
               3.1.3) confusion matrix 
               3.1.4) ROC
        3.2)   3.2.1) ROC Curves
               3.2.2) Calibration Curves
               3.3.3) comparison of ROC curves
               3.3.4) Comparison of calibration curve
               
4.  **LSTM.ipynb**

    **Input**: final_with_main_features.csv
    
    **Output**: 
    
        4.1) ROC Curve
        4.2) Calibration Curve

5.  **Main_Code.ipynb**

    **Input**: final_with_main_features
    
    **Additional File Used**: Shape_Predictor.dat
    
    **Output**: 
    
        5.1) Live results - Alert or Drowsy
        5.2) Curve for state (Alert or drowsy) with frames.


