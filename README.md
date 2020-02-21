# Tutorial: Going beyond ‘Hey Google’: building a Rasa-powered Google Assistant

This repository contains the code of the tutorial of connecting Rasa-powered assistant to Alexa. You can find the step-by-step tutorial here.

## What's in this repository?

This repository consists of the following files and directories:  
- **place_finder** - a directory which contains a pre-built Rasa assistant. This assistant is used in this tutorial to demonstrate the integration to Aleza.
- **alexa_schema.json** - a custom Alexa configuration file that will create an intent and slot to return the user's complete response.
- **alexa_connector.py** - a custom Rasa-Alexa Assistant connector. If you follow the tutorial using your own assistant, add this connector to your project directory.

## How to use this repository?

The best way to use this repository is to follow a step-by-step tutorial on how to integrate the Rasa assistant to Alexa. If you choose to use a Place Finder assistant to follow the tutorial, make sure to install Rasa by using the command below:  
```
pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
```

## Let us know how you are getting on!

If you have any questions about this tutorial or this repository, feel free to share them on [Rasa Community Forum](https://forum.rasa.com). 
