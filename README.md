# DT2-Algos
Audio detection algorithms for Johns Hopkins Design Team 2

READ ALL PROTOCOLS BEFORE RUNNING CODES. Data should be uploaded to the DT2_2023 Google Drive in the appropriate folder in DT2_2023 > Spring 2024 > Audio_models.

Note that all code is currently pulled directly from Drive, so code will have to be modified to access and use files locally (as of 17:30 on 04/15/2024).

High-level protocol:
1. Use splicing code to splice audios based on labels
2. Run spliced audios through spectrogram codes to create spectrograms for the model
3. Train and tune the model on spectrograms
4. Record results
5. Upload ALL data (spliced code, spectrograms, model, model code) to the Drive

Spectrogram naming protocol:
  Spectrogram codes are in Spectrogram Codes
  -  Spectrograms themselves are saved in spectro_output. Naming convention for folder:
        " Parameter being changed_Unique identifier_Audio input folder_Date "

Model naming protocol:
  Model training codes are in Model Training and Inference code
    -  All outputs from each model should be saved in the same folder with the convention: saved_models/Parameter Being Changed_Unique Identifer_Audio Input Folder_Date
    -  Models themselves:"Da te_Parameter Being Changed_Unique Identifier.keras"
    -  Model loss/accuracy graphs and confusion matrices: "(loss/acc/conf)_Date_Parameter Being Changed_Unique Identifier.png"

Naming key:
  Date: Year (2024) Month (XX) Day (XX)
    Ex: 20240401
  Audio input folder is the folder name of the audios being used
  Parameter being changed: Shorten the parameter
  Window size: WS
  Audio length: AL
  Frequency ranges: FR
  Color scale: CS
  Unique identifier is a random number of your choosing to prevent overwriting


