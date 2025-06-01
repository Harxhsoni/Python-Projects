# Fantasy Cricket Team Creator

## Overview
Fantasy Cricket Team Creator is a Python-based data analytics project designed to help users create the **best fantasy cricket team** for Dream11 and other fantasy sports platforms. Using **NumPy** and **Pandas**, this tool analyzes recent player performances and selects an optimized **playing XI** along with **Captain and Vice-Captain** recommendations.

## Features
- **Data-driven player selection** using recent match performance metrics.
- **Automated CSV generation** for easy reference.
- **Captain & Vice-Captain suggestions** based on performance trends.
- **Fully customizable** for different cricket formats and team structures.

## Project Structure
The project consists of four Jupyter Notebook (`.ipynb`) files:

1. **`team_1.ipynb`** – Import Team 1's data, including:
   - Batting and bowling stats (batting average, strike rate, economy, etc.)
   - Performance in the last 5 matches
   - Metrics are saved into a CSV file.

2. **`team_2.ipynb`** – Similar to `team_1.ipynb`, but for Team 2.
   - Generates another CSV file with updated team metrics.

3. **`best11.ipynb`** – Combines both teams' data from previous CSVs.
   - Processes and selects the **best fantasy playing XI**.
   - Exports the final team selection to a new CSV file.

4. **`C&VC2.ipynb`** – Analyzes the final playing XI.
   - Determines the **best candidates for Captain and Vice-Captain**.
   - Saves the updated recommendations.

## Getting Started
### Prerequisites
Ensure you have the following dependencies installed:
- Python (`>=3.8`)
- NumPy
- Pandas
- Jupyter Notebook

### Installation
1. Clone the repository: git clone https://github.com/Harxhsoni/Python-Projects/new/main/Fantasy%20Team%20Creator
2. Navigate to the project directory: cd Fantasy-Team-Creator
3. Install dependencies: pip install numpy pandas


## Usage
1. Open `team_1.ipynb` and `team_2.ipynb`, input player data in CSV format, and generate CSVs with updated metrics.
2. Load both CSVs into `best11.ipynb` to create the optimized **playing XI**.
3. Import the final team into `C&VC2.ipynb` to get **Captain & Vice-Captain** picks.
4. Use the results for your fantasy team selection. **Enjoy!**

## Future Improvements
- Add **multi-match simulation** to refine team selection.
- Integrate **real-time player stats** via an API.
- Build a **user-friendly web interface** using **Streamlit or Flask**.

## Contributing
Feel free to submit **issues, feature requests, or pull requests** to enhance the project!

## License
This project is open-source under the **MIT License**.


