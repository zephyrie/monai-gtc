# MONAI - Spring GTC 2021

This MONAI bootcamp offers medical imaging researchers training modules and an architectural deep dive.

Most of the notebooks in this repository would benefit considerably from having GPU support enabled. Therefore, it is recommended to run notebooks on Google Colab.

### Notebooks

1. Getting Started with MONAI 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zephyrie/monai-gtc/blob/main/1.%20Getting%20Started%20with%20MONAI.ipynb)
2. MONAI Datasets and Caching 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zephyrie/monai-gtc/blob/main/2.%20MONAI%20Datasets%20and%20Caching.ipynb)
3. End-To-End Workflow with MONAI [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zephyrie/monai-gtc/blob/main/3.%20End-To-End%20Workflow%20with%20MONAI.ipynb)
4. MONAI Post-Transforms and Inference Methods [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zephyrie/monai-gtc/blob/main/4.%20MONAI%20Post-Transforms%20and%20Inference%20Methods.ipynb)

**Required Packages for Colab Execution**

Each notebook has a `pip` command for installing MONAI and dependencies at the top of it.  This is only needed for executing them in Google Colab.

**Enabling GPU Support**

To use GPU resources through Colab, change the runtime to GPU:

1. From the **"Runtime"** menu select **"Change Runtime Type"**
2. Choose **"GPU"** from the drop-down menu
3. Click **"SAVE"**

This will reset the notebook and probably ask you if you are a robot (these instructions assume you are not). Running

**!nvidia-smi**

in a cell will verify this has worked and show you what kind of hardware you have access to.   
