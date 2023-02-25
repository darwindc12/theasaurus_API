# Flask Dictionary API
This is a simple Flask web application that serves as a dictionary API. It uses a CSV file named dictionary.csv located in the data folder to fetch word definitions.

## Installation
To run this application, you need to follow these steps:

Clone this repository or download the source code
Install the required packages by running pip install -r requirements.txt
Start the Flask server by running python app.py

## Usage
Once the server is running, you can access the API by making a GET request to http://localhost:5000/api/v1/<word> where <word> is the word you want to look up in the dictionary.

Example:
GET http://localhost:5000/api/v1/sun

Response:
{
    "definition": "the star around which the earth orbits", 
    "word": "sun"
}
