<h1 style="text-align: center;">Bigfoot Sightings Data Analysis</h1>

### <h2>Overview</h2>
This project loads, cleans, and visualizes data related to the location and seasonal distribution of Bigfoot sightings as reported to the Bigfoot Field Researchers Organization.
* Loads the data from csv file of bfro reports
* Cleans the data by removing unnecessary columns and adding relevant attributes
* Creates the following visualizations:
    * A line graph of sightings per year
    * A choropleth map showing the distribution of sightings per state
    * A horizontal bar graph showing the 10 counties with the most sightings in the state with the most sightings
    * Bar graphs depicting the distribution of Bigfoot sightings based on season, month, and weekday both overall and in the state with the most sightings

This project was created using a virtual environment. 

### <h2>Clone the repository</h2>
To run this project, first you'll need to clone the repository to your local machine.
```bash
git clone https://github.com/jubilbee/Bigfoot_Sightings_EDA.git
```
Navigate into the project repository:
```bash
cd Bigfoot_Sightings_EDA
```
### <h2>Create the virtual environment</h2>

**Virtual environment commands**
| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

Create and activate a virtual environment in the project file, then install the requirements.txt 

### <h2>Usage</h2>
**Run the notebook:** Once you have the repository loaded in and the necessary packages installed, open and run the Jupyter Notebook to perform the analysis and generate visualizations.

### <h3>Credits</h3>
The data used in this project came from this [Bigfoot Sightings](https://www.kaggle.com/datasets/thedevastator/unlocking-mysteries-of-bigfoot-through-sightings)  dataset on Kaggle.
