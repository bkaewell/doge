# Federal Regulation Analysis Project  
  
This project provides interactive visualizations and data analysis tools to help inform decision-making on potential deregulation efforts across the government. It leverages both historical and current datasets of federal regulation text to generate actionable insights.  
  
## Project Overview  
  
- **Interactive Analysis:** Jupyter Notebooks (`federal_regulation_analysis.ipynb`) with comprehensive code and analysis  
- **Web App:** A Streamlit app (`app.py`) for deploying interactive plots via web app 
- **Data Files:** Two CSV files (`historical_df.csv` and `current_df.csv`) containing reduced datasets for analysis  
- **Dependencies:** Listed in `requirements.txt`  
- **Assignment Feedback:** Markdown file `Writeup.md`
  
## Installation  
  
1. **Install Jupyter Notebook**   
If not already installed, run:  
```bash  
pip install notebook  
```  
  
2. **Install Python Dependencies**  
Install all required packages with:  
  
```bash  
pip install -r requirements.txt  
```  
  
## Setup and Usage  
  
### Explore the Code  
Launch Jupyter Notebook to view the interactive notebooks and source code:  
```bash  
jupyter notebook  
```  
Open the relevant notebooks to run and interact with the analysis  
  
### Deploy the Web App  
To launch the interactive Streamlit app, run:  
```bash  
streamlit run app.py  
```  
The app will open in your web browser and display the visualizations  

## Input Files  
- **`historical_df.csv`** — Contains historical regulation data (from 3/27/2020)  
- **`current_df.csv`** — Contains current regulation data (from 3/272025)  
  
These files are used to analyze and plot data that help reveal trends and insights into federal regulation text, making complex regulatory data more digestible and actionable  
  
  
## License  
N/A  
  