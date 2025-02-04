# YOLOv11 Setup Guide

## Prerequisites
Ensure you have Python 3.10 installed on your system.

## Create a Virtual Environment
To create a virtual environment, run the following command:
```sh
python -m venv venv
```

### If you're using Multiple Python Versions
If you have multiple Python versions installed, specify Python 3.10 explicitly:
```sh
py -3.10 -m venv venv
```

## Activate the Virtual Environment
Activate the virtual environment with the following command:
```sh
.\venv\Scripts\activate
```

## Install Dependencies
Install the required dependencies using:
```sh
pip install -r .\requirements.txt
```

-------------------------------

### **Note**
The dataset should be splitted to:
```
datasets
    images
        test
        train
        val
    labels
        test
        train
        val
```

The sample yaml file was provided in the datasets folder to serve as guide