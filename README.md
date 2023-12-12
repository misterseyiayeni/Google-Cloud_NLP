### Analyze Text

This Python code analyzes text using the Google Cloud Natural Language API. It extracts entities and sentiment from the text.

### Prerequisites
Python 3.7 or later
A Google Cloud Platform account with the Natural Language API enabled
A JSON key file for a service account with access to the Natural Language API

### Installation
Clone this repository.
Install the dependencies using pip install -r requirements.txt.
Set the GOOGLE_APPLICATION_CREDENTIALS environment variable to the path of your JSON key file.

### Output
The code outputs the following information:

For each entity in the text, it prints the entity name, type, salience, and mentions.
It prints the sentiment score and magnitude of the text.

