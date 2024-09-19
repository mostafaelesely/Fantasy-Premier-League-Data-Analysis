# Fantasy Premier League Data Analysis

## Project Overview

This project is a comprehensive analysis of Fantasy Premier League (FPL) player statistics, utilizing the power of data visualization to help FPL managers make informed decisions. It includes various analyses such as top players by expected goals, assists, clean sheets, and more. The visualizations provide insights into player performance based on different metrics and positions.

## Features

- **Top 10 Players Expected to Score Goals:** Visual representation of players most likely to score based on expected goals (xG).
- **Top 10 Players Expected to Make Assists:** Insights into players who are expected to provide the most assists (xA).
- **Top Defenders by Clean Sheets per 90 Minutes:** Analysis of defenders who are expected to keep the most clean sheets.
- **Top Goalkeepers by Clean Sheets:** Visualizations for the best goalkeepers based on the number of clean sheets.
- **Performance Details:** Heatmap visualization showcasing various performance metrics of top players.
- **Expected Goals vs. Expected Assists:** Scatter plot showing the relationship between xG and xA for top players.
- **Points per Game vs. Selected by Percent:** Bubble chart depicting the relationship between points per game and the percentage of teams that have selected the player.
- **Cost vs. Points per Game by Position:** Violin plot illustrating the cost-effectiveness of players in different positions.

4. **Run the Analysis:**
   You can run the analysis scripts to generate the visualizations by executing:
   ```bash
   python analysis.py
   ```

## Data

The data used in this project is obtained from the official Fantasy Premier League website. It contains various attributes of FPL players such as:

- `expected_goals`: Expected goals (xG) based on past performance.
- `expected_assists`: Expected assists (xA) based on past performance.
- `clean_sheets_per_90`: Clean sheets per 90 minutes for defenders and goalkeepers.
- `total_points`: Total points scored by the player in the season.
- `position`: The position of the player (Goalkeeper, Defender, Midfielder, Forward).

## Visualizations

Below are some of the visualizations included in the project:

### 1. Top 10 Players Expected to Score Goals
![image](https://github.com/user-attachments/assets/64152a42-3b44-4062-8efb-5603c383a9f0)

### 2. Top 10 Players Expected to Make Assists
![image](https://github.com/user-attachments/assets/51aeaf16-4a42-476c-b1a9-cb56a8412ef5)

### 3. Top 10 Defenders Expected to Keep Clean Sheets
![image](https://github.com/user-attachments/assets/80cd5d47-75a6-40aa-b239-b46cdbf0e154)

### 4. Expected Goals vs. Expected Assists
![image](https://github.com/user-attachments/assets/c1ba8a4d-ddab-4f2a-9e92-f5f0d018ef80)

### 5. Points per Game vs. Selected by Percent (Top 20 Players)
![image](https://github.com/user-attachments/assets/3502a356-344b-4147-853e-dfa51d3089d5)


## Contributing

Contributions are welcome! Please create a pull request or open an issue if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

