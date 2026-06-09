# NYC Uber Pickup Analysis (2014)

## Project Overview
This project presents a comprehensive data analysis of Uber pick-up patterns in New York City for the year 2014. The primary goal is to uncover hidden insights regarding travel demand, identify key temporal and spatial trends, and evaluate Uber's market position against other For-Hire Vehicle (FHV) companies.

## Key Highlights
* **Advanced Data Processing:** Performed large-scale data cleaning and harmonization of fragmented raw datasets.
* **Memory Optimization:** Utilized vectorization and memory-efficient data handling techniques to process millions of records seamlessly.
* **Geospatial & Temporal Analysis:** Visualized pick-up hotspots and analyzed demand spikes across different times of the day and year.
* **Market Insights:** Conducted a comparative analysis of Uber's market share relative to other NYC transportation services.

## Technologies Used
* **Languages:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Plotly (Interactive Charts), Seaborn, Matplotlib
* **Geospatial:** GeoPandas, Geopy
* **Utilities:** Scipy, Garbage Collector (gc)

## Project Structure
* `uber_analysis.ipynb`: The main notebook containing the full analysis, from data ingestion to final visualization.
* `data/`: Directory containing the source datasets (Note: Ensure the datasets are placed here for the notebook to function correctly).

## Key Findings
* **Demand Patterns:** Identified clear peak hours and days where Uber demand significantly outpaced traditional services.
* **Spatial Hotspots:** Mapped high-density pickup zones across NYC, providing insights into urban mobility needs.
* **Market Dominance:** Visualized the competitive landscape of the 2014 NYC FHV market.

## How to Run
1. Clone this repository: `git clone [your-repository-url]`
2. Install the necessary libraries: `pip install pandas numpy geopandas plotly geopy`
3. Launch the Jupyter Notebook: `jupyter notebook uber_analysis.ipynb`

## License
This project is for educational and portfolio purposes. Feel free to use and adapt the code.
