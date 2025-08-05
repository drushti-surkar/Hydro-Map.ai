This project, is a water leakage detection system that utilizes citizen-submitted flow rate data and machine learning to identify potential leak zones. The system includes a citizen form for submitting flow measurements and a municipal dashboard for visualizing predicted leak locations.

Features
Citizen Form: Allows users to submit their water flow rate along with their location (latitude and longitude) and user ID.
Anomaly Detection: Uses the Isolation Forest algorithm to detect anomalous flow rates that may indicate a leak.
Municipal Dashboard: Displays predicted leak locations on a map using Leaflet.js.
SQLite Database: Stores flow measurements and leak predictions.
Setup

Clone the repository:
 pip install pandas numpy geopandas shapely scikit-learn flask gradio
  sudo apt-get update
  sudo apt-get install -y sqlite3
