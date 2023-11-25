# Map Generator - Prefecture France From API

This repository contains Python scripts to generate a map of French prefectures using API data and visualizing it through Folium. The main script, `API_VF+Interface.py`, provides an interactive interface to input the department code and visualize the corresponding prefecture data on the map.

## Repository Files:

### API_VF+Interface.py

This script fetches French departmental and regional data via APIs and generates a map using Folium. It allows user interaction through an input field to visualize specific department data.

### API_VF.py

This Python script fetches departmental and regional data via APIs and generates a map using Folium. It provides a console-based interaction, taking user input for the department code to visualize the corresponding prefecture data on the map.

## Requirements

Ensure you have the following libraries installed:
- `requests`
- `webbrowser`
- `folium`
- `csv`
- `numpy`

## Instructions:

1. Clone or download the repository to your local machine.
2. Install the required libraries.
3. Run the scripts using Python 3.x.

### Usage

#### API_VF+Interface.py
Run the script and input the department code in the graphical interface to visualize the prefecture data on the map.

#### API_VF.py
Run the script and input the department code in the console to visualize the prefecture data on the map.

## Execution Instructions

To execute the `API_VF+Interface.py` or `API_VF.py` script:

1. Open your terminal or command prompt.
2. Navigate to the directory where the script is located.
3. Run the command: `python API_VF+Interface.py` or `python API_VF.py`.

## License

This project is licensed under the [MIT License](LICENSE).
