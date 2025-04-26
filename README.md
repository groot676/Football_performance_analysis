Football Performance Analysis:
This project explores football match data (tracking + event data) to understand player and team performance, inspired by the techniques taught in the Friends of Tracking YouTube series.

Using real match datasets, the project processes raw positional and event data to generate insights into in-game dynamics such as player movements, passing patterns, and spatial usage.

Project Overview:
The analysis is performed on two types of data:

Event Data: Records in-game events like passes, tackles, shots, and fouls, including location and timestamp information.

Tracking Data: Captures the continuous position of all 22 players and the ball at 25 frames per second throughout the match.

Key Steps:
Imported and cleaned event and tracking data.

Transformed the coordinate system from normalized units to real-world field dimensions (106m x 68m).

Explored event types to understand match flow and player contributions.

Prepared tracking data for visualizations and further analysis.

Skills Demonstrated:
Data Processing: Handling large-scale, high-frequency tracking data.

Coordinate Transformations: Normalizing positional data for accurate plotting.

Exploratory Data Analysis (EDA): Understanding event distributions and player activities.

Data Visualization: Animating player movements and event sequences using Matplotlib.

Sports Analytics: Deriving insights from player and ball dynamics.

Future Work:
Animating key match moments using player tracking data.

Building passing networks and pressure heatmaps.

Analyzing player spatial control and off-the-ball movements.

Developing metrics for possession dominance and attacking threat.

Acknowledgements:
This project is inspired by the Friends of Tracking YouTube series, a fantastic resource for anyone interested in learning sports analytics, especially football tracking and event data analysis.
