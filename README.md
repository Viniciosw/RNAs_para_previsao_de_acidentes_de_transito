# 💡 RNAs for traffic accident prediction 💡

🌟 Repository dedicated to building neural networks for classification/prediction of traffic accidents in the **Amazônia Region**.

🌟 Each code snippet in all scripts is **previously documented**.

![handshake](images/images_readme/handshake_ia_and_human.png)

## ⚠️ Observations ⚠️

⚠️ The **data download** was done through the **electronic address**: https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf

⚠️ The data used was those **grouped by occurrence**.

⚠️ The code execution was done through **Jupyter Notebook**.

⚠️ This branch contains the **current version** of the code.

## ▶️ Execution of the application ▶️

To run the application, some prerequisites will be necessary:

1. Installation of the **Python** language (preferably the latest version).

2. Installation of **Anaconda**, which will come with **Jupyter Notebook**, preferably in the latest version (Regarding this requirement, it's up to your preference to run the application in other environments).

3. Installation of the **libraries** mentioned below:

```
!pip install keras
!pip install tensorflow
!pip install sklearn
!pip install imblearn
!pip install pandas
!pip install numpy
!pip install shap
!pip install seaborn
!pip install scikit-plot
!pip install SimpleFilter
```

4. Download the files through the open data platform of the Brazilian Federal Government, the link to which is provided in the notes section of this README.md.

5. Place these files inside the **"raw"** folder of the application.

6. Run the scripts in the following sequence:

    1. **trusted_script.ipynb** (depending on the type of file you have downloaded, some code snippets may need to be modified in this script).

    2. **refined_script.ipynb**

    3. Run all scripts present in the **"networks_training"** folder.

    4. Run all scripts present in the **"networks_test"** folder.

    5. The **"data_analysis_scripts"** folder contains some analyses about the datasets, so it's up to your discretion whether to execute these scripts.