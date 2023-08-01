# Medical Data Visualizer

The goal of this project is to analyze and visualize medical examination data using various data analysis and visualization techniques in Python.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Technologies Used](#technologies-used)
- [License](#license)

## Introduction

The Medical Data Visualizer project focuses on analyzing a dataset containing medical examination records of patients. The dataset includes various health metrics such as age, gender, body mass index (BMI), blood pressure, cholesterol levels, and more. By performing data analysis and visualizations on this dataset, we can gain insights into the relationships between different health factors and explore potential correlations.

## Features

The Medical Data Visualizer project provides the following features:

- Calculating summary statistics of the dataset, such as mean, median, and percentile values.
- Creating visualizations to explore the distribution of BMI values, as well as comparing BMI distributions between males and females.
- Analyzing the relationship between a patient's age and their cholesterol levels.
- Creating visualizations to showcase the distribution of different cholesterol types (normal, above normal, and well above normal) by gender.
- Analyzing the relationship between a patient's BMI and their systolic blood pressure.
- Creating visualizations to highlight the relationship between smoking habits, age, and BMI.

## Installation

To use this project, follow the steps below:

1. Clone the repository:

```bash
git clone https://github.com/JosephMusenge/Medical-Data-Visualizer.git
```

2. Navigate to the project directory:

```bash
cd Medical-Data-Visualizer
```

3. (Optional) Create a virtual environment to keep the project dependencies isolated:

```bash
python3 -m venv env
```

4. Activate the virtual environment:

- On macOS and Linux:

```bash
source env/bin/activate
```

- On Windows:

```bash
.\env\Scripts\activate
```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

6. You're ready to use the Medical Data Visualizer!

## Usage

To use the Medical Data Visualizer, run the `medical_data_visualizer.py` script:

```bash
python medical_data_visualizer.py
```

The script will execute the data analysis and visualization tasks on the provided dataset. The results will be displayed in the console and saved as output images.

## File Descriptions

The project repository contains the following files:

- `medical_data.csv`: The dataset file containing medical examination records.
- `medical_data_visualizer.py`: The main Python script that performs data analysis and visualization.
- `README.md`: This README file provides an overview of the project.
- `main.py`: This entry point file is used in development and serves as the starting point for running the data analysis and visualization tasks.

## Technologies Used

The Medical Data Visualizer project utilizes the following technologies:

- Python: The core programming language used for data analysis and visualization.
- Pandas: A powerful library for data manipulation and analysis.
- Matplotlib: A plotting library for creating visualizations in Python.


