# Data-Wrangling
#### Data Wrangling, Data Quality Project
----------------------------------------------

Ismail EL HADRAMI
Yassine ABOU HADID

----------------------------------------------
Paper: https://arxiv.org/pdf/1806.02920.pdf ( GAIN: Missing Data Imputation using Generative Adversarial Nets )

Authors code: https://github.com/jsyoon0823/GAIN

----------------------------------------------
In this project, we reviewed the research paper above, implemented the experiments code from scratch and introduced multiple variations in the standard GAIN architecture to improve the model's performance and to extend it to image data.
  
----------------------------------------------
Repository organization: 
* the folder [Experiments reconstruction](https://github.com/abouhadid/Data-Wrangling/tree/main/Experiments%20reconstruction) contains the notebook of the experiments discussed in the article along with the 5 datasets and plots
* the subfolder [Contribution/GAIN-V2](https://github.com/abouhadid/Data-Wrangling/tree/main/Contribution/GAIN-V2) contains the same files for the modified model GAIN-V2
* the subfolder [Contribution/MNIST](https://github.com/abouhadid/Data-Wrangling/tree/main/Contribution/MNIST) contains a script input_data.py to download MNIST, a notebook of the architectures definition and experiments and the resulting imputation images
* the subfolder [Contribution/PNEUMONIA](https://github.com/abouhadid/Data-Wrangling/tree/main/Contribution/PNEUMONIA) contains a notebook for the preprocessing pipelines, the architectures definition and experiments and the resulting imputation images. Make sure to use the link provided in the notebook header to download the data.
* the subfolder [Contribution/WGAIN](https://github.com/abouhadid/Data-Wrangling/tree/main/Contribution/WGAIN) contains the dataset, the loaded models and the notebook used to train and test the wGAIN model.
