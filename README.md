# Improving the accuracy of Luftdaten devices using machine learning
Jupyter notebooks to train and apply machine learning model to improve accuracy of PM2.5 and PM10 concentration determination using low-cost devices. Model is trained using data from the year-long colocation comparison between Luftdaten and reference device. Trained model is used to process results gathered by four other low-cost PM devices. This altered results are compared to the average of PM2.5 and PM10 concentrations measured by three nearest reference stations.

## Detailed description
Will be updated with a link to the research paper when it will be published.

## Dependencies
You need to have Python 3, Jupyter Notebook, Matplotlib, Pandas, NumPy, SciPy, scikit learn and TensorFlow installed on your computer to run these scripts.

## Simplest way to setup your system:

1. Install Python

  1.1. Windows
  
Go to the https://www.python.org/ and download the current version of Python 3. Install it selecting checkbox to add Python to the PATH during setup.

  1.2. Linux

Open command line and type:

    sudo apt install python3

2. Install dependencies

Open command line and type:

    pip install jupyter matplotlib pandas numpy scipy scikit tensorflow

If there will be an error than pip command is not recognized, try using pip3 instead.
