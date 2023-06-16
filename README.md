## Venture Funding Success Predictor

I'm excited to introduce a project where we're using deep learning to predict startup success. This project involves building a binary classification model that helps us forecast the potential success of businesses applying for funding. To ensure the best results, the data undergoes rigorous preprocessing before being fed into our neural network model. We compile and evaluate this model following the model-fit-predict pattern, optimizing it to yield the most accurate predictions.

You'll find all the code, data, and resources for this project in this repository. Feel free to dive in, explore, and offer suggestions for improvement. Just a note: don't forget to check the preprocessing section, as proper data preparation is crucial for our neural network model's success. 

Last Updated: 2023-06-16.


---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, hvplot, prophet, pathlib, tensorflow, sklearn

- **Framework:** JupyterLab, Google Colab
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

If you don't have Python, JupyterLab, or Anaconda installed on your operating system:

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**


**1. Conda 'dev' Environment** - To run the main application you will need to create a new enviornment that will be compatible with this application, type and enter the following. You will still use the previous steps' command to activate:

        conda create -n env_name python=3.7 anaconda

Activate conda enviorment by running the following function:

        conda activate env_name 

**2. Other Libraries** - It was mentioned earlier that the other required libraries should already be installed with the Anaconda package. To confirm installation for these libraries, you can either use the 'conda list' command followed by the library name to confirm installation. Or, you can install the libraries which will either install successfully or if already installed, will result in a 'requirement already satisfied' message. Listed below are the commands to install each library if needed:
        
        pip install sklearn
        pip install tensorflow


**3. Clone Repo**

After completing all prerequisite installations, you're ready to clone this repository to your local machine. To do this, begin by copying the SSH keys.

Next, navigate to the directory in your terminal where you want this repository to be placed. Once you're in your desired directory, execute the following command:

        git clone 'paste ssh keys here'

To operate the repository in JupyterLab, navigate into the repository folder by typing:

        cd 'repository folder name'

Then, initiate JupyterLab by entering:

        jupyter lab

### **NOTE:** 

If you're using a Mac with an M1 chip, you may encounter installation issues with libraries such as sklearn and tensorflow. In such cases, we recommend using Google Colab for this project. This cloud-based IDE enables remote execution of Jupyter Notebooks, bypassing potential installation hurdles. Here's how you can access the notebook from this repository:

1. Launch your preferred web browser (Chrome recommended). Visit `https://colab.research.google.com/`.

2. Once the page loads, navigate to 'File' at the top-left corner, then select 'Open Notebook'.

3. A window will appear. Click on 'Upload', then 'Choose File'.

By following these steps, users with a Mac M1 chip can seamlessly access and work with the notebook in this repository via Google Colab, avoiding any sklearn and tensorflow installation issues.

___

## *Usage*


**1. Code Execution**: Once your data is uploaded, you can start running your code. Execute each code cell individually by clicking the 'play' button on the cell's left, or use 'Shift+Enter' as a shortcut to run the current cell and move to the next one.

**2. Accessing Uploaded Files**: After uploading your file, you can reference it directly in your Python scripts by its name. For instance, to load a file named `data.csv` into a pandas DataFrame, use the following code: 
```python
import pandas as pd 
df = pd.read_csv('data.csv')
```

**3. Work Preservation**: Regularly save your work since Google Colab sessions may timeout after periods of inactivity. Save your progress by clicking on 'File' > 'Save'. You can also save a copy of the notebook in your Google Drive by choosing 'File' > 'Save a copy in Drive'.

**4. Notebook Download**: To maintain a local copy of your notebook, navigate to 'File' > 'Download .ipynb'. If you need a Python script version, select 'File' > 'Download .py'.
Once you launch JupyterLab with the repository code, open the 'user_input.ipynb' notebook first.

---

## *Contributors*

For any questions, comments, concerns, feel free to contact below: 

**Rosalinda Olvera Fernandez**

[GitHub](https://github.com/rolvera05) - rolvera98271@gmail.com
