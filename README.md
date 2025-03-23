Analyzing sales of Video games and consoles by genre and launch year?


videogame data from: https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales
console data from: https://www.kaggle.com/datasets/tayyarhussain/best-selling-game-consoles-of-all-time







## Data Dictionary  

This dataset contains information about video game sales, platforms, and console details. Below is a description of each column:  

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