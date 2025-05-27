# Data Analysis Project

## Overview

The project is my capstone project for CODE:you. The project analyzes Video game sales and consoles sold to determine which console was the most successful. It also explores how specific regions or game genres contribute to the overall success.

## Data

The dataset used in this project contains information about sales, including details such as title, genre, publisher, developer, total sales, and release dates.
- [videogame data ](https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales)
- [console data ]( https://www.kaggle.com/datasets/tayyarhussain/best-selling-game-consoles-of-all-time)





### Project Structure
---

The project is organized as follows:

- **Data Exploration:** Jupyter notebook to explore the dataset.

- **Analysis:** Using Python with Pandas to clean the data.

- **Visualizations :** Using Matplotlib and Seaborn to visualize my findings. 


### Tools & Libraries Used

- **Python** (data analysis and scripting)
- **Pandas** (data cleaning and manipulation)
- **Matplotlib** & **Seaborn** (data visualization)
- **Jupyter Notebook** (interactive analysis)
- **Virtual Environment** (dependency management)
- *(Planned: PostgreSQL, Docker, Tableau for future iterations)*

## Getting Started

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/V-Pool/vg_sales`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Explore the Jupyter notebook.

## Data Dictionary  

This dataset contains information about video game sales, platforms, and console details. Below is a description of each column in the combined dataframe:  

| Column Name              | Data Type  | Description |
|--------------------------|-----------|-------------|
| **Name**                 | `object`  | Title of the video game. |
| **Platform**             | `object`  | The gaming console or platform the game was released on. |
| **Year**                 | `int64`   | The year the game was released. |
| **Genre**                | `object`  | The genre/category of the game (e.g., Action, Sports, RPG). |
| **Publisher**            | `object`  | The company that published the game. |
| **NA Sales**             | `float64` | Number of sales in North America (in millions). |
| **EU Sales**             | `float64` | Number of sales in Europe (in millions). |
| **JP Sales**             | `float64` | Number of sales in Japan (in millions). |
| **Other Sales**          | `float64` | Number of sales in other regions (in millions). |
| **Global Sales**         | `float64` | Total number of sales worldwide (in millions). |
| **Console Type**         | `object`  | Category of the console (e.g., handheld, home console). |
| **Console Manufacturer** | `object`  | The company that produced the console. |
| **Console Released**     | `int64`   | The year the console was first released. |
| **Console Discontinued** | `int64`   | The year the console was discontinued. |
| **Consoles Sold**        | `float64` | Total number of units sold for the platform (in millions). |
 
## Features Utilized for the project

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files (JSON, CSV, Excel, etc.)| 2 CSV files from kaggle          |
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged them with pandas. Created 2 new values from the combined dataframes |
  | Make 3 matplotlib or seaborn (or another plotting library) visualizations to display your data.  | Created different plots of my Data. |
  | Make at least 1 Pandas pivot table and 1 matplotlib/seaborn plot. Pivot tables are a way to summarize your data and present it easily in a way that isn’t just a graph. They can be useful when combined with graphs. | Made a pivot table and created a seaborn heatmap from the pivot |
  | Utilize a virtual environment and include instructions in your README on how the user should set one up| Created a venv. |
  |   Build a custom data dictionary and include it either in your README or as a separate document. This will only apply if your data set does not already have a data dictionary or if you’re building a custom data set. For an example, see the resources to the right.  | Data Dictonary in the README. |
  | Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md. Tidy up your notebook, and make sure you don’t have any empty cells or incomplete cells that don’t do anything. Make sure it’s all functional before your final github commit. | In my code, you will find clear notes describing each code block. |


## Virtual Environment Instructions

1. After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.
1. Create a virtual environment in the project folder. 
2. Activate the virtual environment.
3. Install the required packages. 
4. When you are done working on your repo, deactivate the virtual environment.

Virtual Environment Commands

| Command | Linux/Mac | GitBash |
|---------|-----------|---------|
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

## Conclusion

Through this analysis, I identified the PlayStation 2 as the most successful console, with 155 million units sold and over $1.25 billion in global game sales. The data also revealed that North America and Europe are the largest markets, and that genres like Sports, Action, and Racing significantly contributed to console success. This project demonstrates my ability to clean, merge, and analyze real-world datasets, and to communicate insights through visualizations and clear documentation.


## Next Steps/Future Iterations

To further develop this project, I plan to:
- Migrate the cleaned data into a PostgreSQL database running in Docker.
- Use Tableau to create interactive dashboards connected to the database.
- Share Docker and Tableau setup instructions for reproducibility.

Stay tuned for updates as I add these features!