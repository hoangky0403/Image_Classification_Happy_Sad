# Image_Classification_Happy_Sad

## Overview

This project builds and trains a deep learning image classification model using TensorFlow and OpenCV. The model classifies images from folders (for example: `happy` and `sad`). The implementation is provided in a Jupyter Notebook.

---

## Project Structure

```
project-folder/
│
├── data/
│   ├── happy/
│   └── sad/
│── logs
├── image_classification.ipynb
├── README.md
├── happytest
├── sadtest

```

Each folder inside `data/` represents a class.

---

## System Requirements (Windows)

* Windows 10 or Windows 11
* Python 3.10 recommended
* Command Prompt or PowerShell
* Jupyter Notebook

Check Python version:

```bash
python --version
```

---

## Step 1: Create Virtual Environment (Windows)

Open **Command Prompt** or **PowerShell** in your project folder.

Create virtual environment:

```bash
python -m venv env
```

---

## Step 2: Activate Virtual Environment

Command Prompt:

```bash
env\Scripts\activate
```

PowerShell:

```bash
env\Scripts\Activate.ps1
```

After activation, you should see:

```
(env) C:\your-project-folder>
```

---

## Step 3: Install Required Libraries

Run:

```bash
pip install tensorflow opencv-python==4.5.5.64 matplotlib "numpy<2" jupyter
```

Optional: save dependencies

```bash
pip freeze > requirements.txt
```

---

## Step 4: Run Jupyter Notebook

Start Jupyter:

```bash
jupyter notebook
```

Your browser will open automatically.

Open:

```
image_classification.ipynb
```

Run all cells from top to bottom.

---

## Step 5: Dataset Setup

Place your dataset inside the `data` folder:

```
data/
 ├── happy/
 └── sad/
```

Example:

```
data/happy/image1.jpg
data/sad/image2.jpg
```

Folder names are used as class labels.

---

## Step 6: Expected Output

After running the notebook, the model will:

* Load and clean images
* Train a CNN model
* Show training progress
* Display accuracy and loss graphs

---

## Step 7: Deactivate Environment (When Finished)

```bash
deactivate
```

---



