# DT2-Algos
Audio detection algorithms for Johns Hopkins Design Team 2

READ ALL PROTOCOLS BEFORE RUNNING CODES. Data should be uploaded to the DT2_2023 Google Drive in the appropriate folder in DT2_2023 > Spring 2024 > Audio_models.

Note that all code is currently pulled directly from Drive, so code will have to be modified to access and use files locally (as of 17:30 on 04/15/2024).

General protocol (FOR ALL TESTING, CHANGE THE DIRECTORIES AS NECESSARY BASED ON LOCAL FILE MANAGMENT):
1. Use splicing code to splice audios based on labels
2. Run spliced audios through spectrogram codes to create spectrograms for the model
4. Train and tune a model on the created spectrograms
5. Record results
6. Upload ALL data (spliced code, spectrograms, model, model code) to the Drive in their respective folders

Spectrogram naming protocol:
  Spectrogram codes are in "Spectrogram Codes" folder
  -  Spectrograms themselves are saved in spectro_output. Naming convention for folder:

       " [Parameter being changed]_[Unique identifier]_[Audio input folder]_[Date] "

Model naming protocol: Model training codes are in Model Training and Inference code
  -  All outputs from each model should be saved in the same folder with the convention: saved_models/[Parameter Being Changed]_[Unique Identifer]_[Audio Input Folder]_[Date]
  -  Models themselves:"[Date]_[Parameter Being Changed]_[Unique Identifier].keras"
  -  Model loss/accuracy graphs and confusion matrices: "[loss/acc/conf]_[Date]_[Parameter Being Changed]_[Unique Identifier].png"

Naming key:
  -  Date: Year (2024) Month (XX) Day (XX) (Ex: 20240401)
  -  Audio input folder is the folder name of the audios being used
  -  Parameter being changed: Shorten the parameter
  -  Window size: WS
  -  Audio length: AL
  -  Frequency ranges: FR
  -  Color scale: CS
  -  Unique identifier is a random number of your choosing to prevent overwriting





