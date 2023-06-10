# switso_classifier
Fine-tuned VGG-19 for Switso classification

## Environment Setup
1. Ensure that Python is installed on your machine. If not, download and install the latest version of Python from the official Python website [here](https://www.python.org).
2. Optionally, you can set up a Conda environment by installing Conda from the Anaconda distribution [here](https://www.anaconda.com/products/individual).
3. Open a terminal or command prompt and create a new Python environment using the desired tool. For example:
    - Using Conda: `conda create --name myenv`
    - Using virtualenv: `python -m venv myenv`
4. Activate the newly created environment using the appropriate command:
    - Using Conda: `conda activate myenv`
    - Using virtualenv: `source myenv/bin/activate`
5. Install the required libraries, packages, and modules by executing the following command:
`pip install -r requirements.txt`

## Setting up the project
1. Upload the dataset in the same directory and run the following command on your Jupyter Notebook to extract all the zipped folders:
`import zipfile
with zipfile.ZipFile("all_doggo_img_folders.zip", 'r') as zip_ref:
    zip_ref.extractall(".")`
2. Open the `switso_classification.ipynb` notebook and enjoy!
