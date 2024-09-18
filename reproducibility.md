Software Requirements:
Python: Version 3.9
Anaconda/Miniconda: Recommended for managing dependencies.
Git: For cloning the repository and version control.
JupyterLab: For running the analysis notebooks.

Here is a quick overview of the project structure:

/TFM-Reproducible
├──                    
│   ├── Costumer Behavior Survey           
│   │   ├── raw            
│   │   ├── procesado      
│   ├── Reviews          
│   │   ├── raw          
│   │   ├── procesado     
│   ├── Sale Report           
│   │   ├── raw            
│   │   ├── procesado      
├── Jupyter notebooks              
│   ├── AmazonReviews.ipynb  
│   ├── AmazonSaleReport.ipynb  
│   ├── CostumerBehaviorSurvey.ipynb  
├── README.md               
├── environment.yml         
└── reproducibility.md      # This guide

To begin, clone the repository to your local machine using the following command:

#git clone https://github.com/username/TFM-Reproducible-Project.git
#cd TFM-Reproducible-Project

This project uses Conda to manage dependencies. All necessary packages are listed in the environment.yml file.

#conda env create -f environment.yml
#conda activate TFM-environment
#conda list

If any packages are missing, you can install them manually using conda install or pip install.

Each dataset must be preprocessed before running the analysis notebooks. The processing scripts are included in the notebooks, so you only need to execute them in the correct order.

1. Open and run the notebooks
2. Run the cells: Execute all cells in each notebook to reproduce the analysis. The processed data will be saved in the corresponding processed/ folder under each dataset.

After running the notebooks, the processed data and results will be saved in the processed/ folder under each dataset directory. You can view visualizations, model evaluations, and other results directly in the notebook outputs.
   
