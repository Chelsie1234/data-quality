# Data Quality Exercise

## Table of Contents
1. [Overview](#overview)
2. [Key Rules and Steps](#key-rules-and-steps)
3. [Getting Started](#getting-started)
4. [Contact](#contact)

## Overview
This project is a data quality exercise focusing on key Data Management & Ethics principles. The goal is to ensure high-quality data through systematic practices like setting up a collaborative environment, performing careful data extraction, using data analysis tools, and implementing data cleaning and encryption measures.<br>
Data quality is a critical aspect of any data-driven process. In this project, we aim to explore and address various facets of data quality including accuracy, consistency, completeness, and security

## Key Rules and Steps

### 1. Set Up the Collaboration Environment
Effective collaboration starts with a well-configured environment. Using GitHub and automated workflows, we ensure:
- **Availability**: Everyone has access to the data.
- **Accessibility**: The data is easy to retrieve and use.
- **Coherence**: The data remains consistent across versions.
- **Durability**: Changes are securely tracked and preserved.

### 2. Careful Data Extraction
Data extraction must be precise, with correct delimiters to avoid errors in the dataset. This foundational step ensures that the subsequent processes are built on accurate data.

### 3. Data Analysis Tool
Instead of traditional methods like Jupyter Notebooks, we use **Dataiku** to enhance our data analysis. This tool provides advanced insights, helping to reinforce observations and identify critical data elements we might otherwise overlook.

### 4. Deep Dive into Data Cleaning
Post-analysis, we dive deeper into data cleaning. By applying relevant metrics, we identify and correct inconsistencies and errors, ensuring the data is ready for further processing.

### 5. Understanding Levels of Confidentiality and Encryption
Data security is paramount, especially in case of data leaks. We categorize data into four levels:
- **Public**: Open information (e.g., company website content).
- **Internal**: Non-sensitive internal communications.
- **Confidential**: Sensitive information requiring encryption (e.g., customer data).
- **Restricted**: Highly sensitive information with strict access controls (e.g., trade secrets).

Encryption practices are applied appropriately to protect data according to its confidentiality level.

### 6. Visualizations
Visualizing data helps in identifying trends and patterns. We use **Plotly**, a library that provides interactive and insightful visualizations, enhancing our understanding of complex datasets. By running the notebook you will be able to access them whenever you want as they are save in html files in the "visualizations" folder.

### 7. Code Review
Regular code reviews ensure code quality and security. Tools and practices include:
- Peer reviews on GitHub.
- Automated checks for potential vulnerabilities (e.g., exposed passwords).
- Restricting direct pushes to the main branch to prevent unapproved changes.

## Getting Started

### Prerequisites
- Python 3.x
- Git
- Plotly for data visualization
- Dataiku for advanced data analysis (optional)

### Installation
1. Clone the repository:
   ```cmd
   git clone https://github.com/your-username/data-quality-exercise.git
   ```
2. Navigate to the project directory:
   ```cmd
   cd data-quality-exercise
   ```
3. Create a virtual environment:
   ```cmd
   # If you don't have the library installed
   pip install --upgrade pip virtualenv
   ```
   ```cmd
   python -m venv .venv
   ```
4. Activate the virtual environment:
   ```cmd
   # On Windows
   ./.venv/Scripts/activate
   ```
   ```cmd
   # On Unix/MacOS
   source .venv/bin/activate
   ```
4. Install the required packages:
   ```cmd
   pip install -r requirements.txt
   ```

### Usage
* Run the scripts in the repository to perform data extraction, cleaning, and visualization.
* Ensure encryption is applied based on the data's confidentiality level.

### Contact
For any questions or suggestions, please open an issue or contact the project maintainers.<br><br>
