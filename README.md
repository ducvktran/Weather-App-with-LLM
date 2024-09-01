# Weather-App-with-LLM

This repository contains the Jupyter notebook with the Python code to create an LLM app/chatbot that lets users enter a city name to search for a five-day weather forecast. The app first verifies whether the input is a valid city name and then retrieves the weather forecast data from the [API](https://www.visualcrossing.com/weather/weather-data-services). If you want to view the notebook on nbviewer, please click [here](https://nbviewer.org/github/ducvktran/Weather-App-with-LLM/blob/main/Weather_App_with_LLM.ipynb).

Once you run all the code cells (using GPU and following some specific instructions in the notebook), you should get the chat interface like the picture below.

![Chat Interface](https://github.com/user-attachments/assets/5328a731-d5a4-4452-8acd-7446c020a7f5)

From here, you can type in any city name to look up the five-day weather forecast, or you can choose some of the examples provided at the bottom. For example, if you enter "Ho Chi Minh City, Vietnam," the following result (or something similar depending on the date) would appear.

![Valid Example](https://github.com/user-attachments/assets/1cc940f5-65b9-439e-9854-dd5bcd9e7733)

If you do not enter a valid city name, the app will return "Please enter a valid city name."

![Invalid Example](https://github.com/user-attachments/assets/63c26d15-4d91-4f14-a5bb-8f98e36fc1f2)
