# Football_Player_Transfer_Analysis

## Project Overview
This project focuses on analyzing the 2022 summer football (soccer) player transfer market using semi-structured JSON data. The analysis explores transfer fees, player movements, and the financial activities of football clubs, providing insights into the trends and patterns within the transfer market.

## Data Source
The dataset used for this project was downloaded from Kaggle. It contains information about 2,344 football player transfers during the 2022 summer transfer window, including details such as:
- Player Name
- Age
- Position
- Nationality
- New Club
- Transfer Cost

## Project Structure
The project is organized into the following sections:

1. **Data Exploration and Cleaning**
    - Loaded the JSON dataset into a pandas DataFrame.
    - Renamed the misspelled column `player_valuje` to `player_value`.
    - Converted the `player_value` column from a string containing a currency value (in Euros) to a float using a custom function `convert_value()`.

2. **Data Analysis**
    - Computed key statistics such as the most expensive player transfer and the club with the highest total transfer expenditure.
    - Created tables listing the top 10 nations by the number of players transferred from and to, offering insights into player migration patterns.
    - Plotted bar graphs to visualize:
        - The top 10 highest and lowest player transfer fees.
        - The total transfer fees spent by the top 10 clubs.

3. **Comparison Questions**
    - **Total Transfer Fees by League**: Analyzed the total transfer fees spent by leagues such as the Premier League, LaLiga, and Ligue 1.
    - **Top 10 Clubs by Transfer Fees**: Identified the top 10 clubs by total transfer fees spent.
    - **Top 10 Countries by Player Count**: Compared the top 10 countries by the number of players from those nations and the top 10 countries by the number of players arriving at clubs within those nations.

## Requirements
To run this project, you'll need the following Python libraries:
- 'pandas'
- 'matplotlib'
- 'seaborn'
- 'json'

You can install the required libraries using pip:
pip install pandas matplotlib seaborn

## Results
Top Club by Transfer Fees: Identified the club with the highest overall transfer expenditure.
Most Expensive Player: Highlighted the player with the highest transfer fee.
Player Migration: Provided insights into player migration patterns across different countries.
Transfer Fee Distribution: Visualized the top 10 highest and lowest transfer fees, as well as the spending habits of elite football clubs.

## Conclusion
This project provides valuable insights into the football transfer market, highlighting the financial activities of clubs, player valuations, and migration patterns. The analysis can benefit football fans, analysts, and stakeholders interested in the economics of the sport.

Tools: Python, Jupyter Notebook, Pandas, Matplotlib, Seaborn
