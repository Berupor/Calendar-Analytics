# Google Calendar Analytics
This Python program allows you to perform analytics on your Google Calendar events. With this program, you can visualize the total duration of your events, compare the length of events across different time periods, and gain insights into which events take up the most time.

## Features
- Extract events from your Google Calendar
- Compute the total duration of events in a specified time range
- Visualize the duration of events in a pie chart and a bar chart
- Limit the number of events displayed in the charts
- Save the charts as PNG images

## Installation
You can install the dependencies for this program by running the following command:
```console
pip install -r requirements.txt
```
### Setup
You will need to create a Google API key to be able to access your Google Calendar data. The instructions for doing this can be found in the [Google API documentation](https://developers.google.com/calendar/api/guides/quickstart/python).

Once you have obtained your API key, you will need to save it as a JSON file and place it in the `src/authentication/` directory of the program. The file should be named `credentials.json`

## Usage
To run the program, simply run the following command:
```console
python main.py
```
The program will prompt you for the start and end dates for the time range you would like to analyze. After entering the dates, the program will compute the total duration of your events and generate pie charts and bar charts that visualize the duration of your events.