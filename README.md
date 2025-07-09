^Indian-Chess-Growth-Analysis-Visualisation

#Project Description

This repository contains a comprehensive analysis of Indian chess statistics over the past decade (2013-2023), focusing on:
-The exponential growth of Indian Grandmasters (GMs)
-Regional distribution of chess talent (with Tamil Nadu as the epicenter)
-Opening repertoire analysis of Indian players
-Performance across different chess formats
-Accuracy metrics in various openings

#Features
-Data Collection: Web scraping from chess databases (mock data in this example)
-Data Processing: Conversion to pandas DataFrames

Visualizations:

-Line plots showing GM growth over time
-Pie/bar charts of regional distribution
-Scatter plots of opening success vs accuracy
-Radar charts of format performance
-Heatmaps of opening statistics
-Bubble charts of opening usage patterns
-HTML Report Generation: Automated report with all findings

#Visualization     Examples
Chart Type       	Description	                  Example
Line Plot	        GM Growth Over Time	          https://gm_growth_line.png
Pie Chart   	    State-wise Distribution	      https://state_distribution_pie.png
Scatter Plot	    Opening Win% vs Accuracy	    https://openings_win_vs_accuracy.png
Radar Chart	      Time Format Performance	      https://formats_radar.png
Heatmap         	Openings Statistics	          https://openings_heatmap.png

#Installation 
Clone the repository:
bash
git clone https://github.com/sutirthacodes/Indian-Chess-Growth-Analysis-Visualisation.git
cd indian-chess-stats

#Install required packages:
bash
pip install -r requirements.txt

#Requirements
-Python 3.8+
-pandas
-matplotlib
-numpy
-seaborn
-requests
-BeautifulSoup4

#Usage
Run the analysis script:
python
python indian_chess_analysis.py
This will:
-Collect data (using mock data in this example)
-Generate all visualizations


File Structure
text
Indian-Chess-Growth-Analysis-Visualisation/
├── chess_data_html/          # Raw data in HTML format
├── indian_chess_analysis.py  # Main analysis script
├── requirements.txt          # Dependency list
├── README.md                 # This file
└── *.png                     # Generated visualization files

#Future Enhancements
-Connect to real chess APIs (Lichess, Chess.com, FIDE)
-Add player-specific performance analysis
-Include tournament performance metrics
-Build interactive dashboards

#Contributing
Contributions are welcome! Please open an issue or submit a pull request.

#License
This project is licensed under the MIT License.
