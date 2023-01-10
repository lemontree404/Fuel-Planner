# Fuel-Planner - The Smart Refueling Assistant
Fuel-Planner is a smart refueling assistant that helps drivers plan their routes and find the best refueling options based on their vehicle's current mileage and fuel level. The app uses the Google Maps API to calculate routes, determine when a vehicle might need to refuel, and find nearby refueling stations that meet the driver's criteria.

## Features
- Calculates the total distance and duration of a route between two locations.
- Identifies potential break points along a route where a vehicle might need to refuel.
- Finds nearby refueling stations based on a query and minimum rating.
- Provides the distance and duration from the break point to all the nearby refueling stations.
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You will need to have Python and pip installed on your machine. You can download Python from the official website https://www.python.org/downloads/

You will also need to have a Google Maps API key. You can get one from the Google Cloud Console https://console.cloud.google.com/

### Installing
Clone the repository to your local machine.

```bash
git clone https://github.com/lemontree404/Fuel-Planner.git
```
Create a virtual environment and activate it.
```bash
python -m venv env
source env/bin/activate
```
Install the required dependencies.
```bash
pip install -r requirements.txt
```
### Running the App
To run the app run the following command:
```bash
streamlit run app.py
```
The app will be available at http://localhost:8501/ in your web browser.

![](https://github.com/lemontree404/Fuel-Planner/blob/main/streamlit-app-2023-01-10-14-01-12.gif)

## Built With
- [Python](https://www.python.org/) - Programming language
- [pandas](pandas.pydata.org) - Data manipulation library
- [numpy](https://numpy.org/) - Scientific computing library
- [streamlit](https://streamlit.io/) - App framework
- [googlemaps](https://github.com/googlemaps/google-maps-services-python) - Google Maps API client library
- [pydeck](pydeck.gl) - 3D visualization library
## Authors
- Manav Karthikeyan - [Github](https://github.com/lemontree404)
- P Rahulram - [Github](https://github.com/Mr-Appu)
## Acknowledgments
Karun A [Github](https://github.com/Karun842002) (Thank you for the API key 💖💖)
## License
This project is licensed under the MIT License 



