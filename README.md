![](https://miro.medium.com/v2/resize:fit:1400/1*xlCyGCKz8Wxws7gP_XcjnQ.png)
![dotenv 0.20.0](https://img.shields.io/badge/dotenv-0.20.0-brightgreen?style=flat)
![Streamlit 1.10.0](https://img.shields.io/badge/Streamlit-1.10.0-blue?style=flat)
![Google API](https://img.shields.io/badge/Google_API-latest-yellow?style=flat)
![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python&logoColor=white)

# Tweet Classifier Using Gemini LLM
This Streamlit application classifies tweets as 'Non-Spam' or 'Spam' using the Gemini LLM API.

## Features

- Classify tweets into 'Non-Spam' or 'Spam' categories.
- Exception handling to gracefully manage API errors or invalid inputs.
- Display a history of classified tweets.
- Reset functionality to clear inputs and history.

## How to Run the Application

1. Ensure you have Python installed on your system.
2. Install the required packages using `pip install -r requirements.txt`.
3. Set your environment variables for the Google API key in a `.env` file.
4. Run the application using `streamlit run tweet_classifier.py`.

## Deployment
![image](https://github.com/abh2050/tweetclassifiy/blob/main/pic.png)
The application is deployed at [Tweet Classifier](https://tweetclassifiy.streamlit.app/).

## Requirements

The `requirements.txt` file should contain the following packages:

```
streamlit
google-generativeai
python-dotenv
langchain
pyPDF2
chromadb
```

## Usage

1. Input the main tweet and the reply tweet.
2. Click on 'Classify Reply' to get the classification.
3. View the classification history below.
4. Use the 'Reset' button to clear inputs and history.

## Source Code

The source code for the application is structured as follows:

```python
# Python code snippet from the application
```

(Note: Include the source code snippet here if desired.)

## Author

- Developed by Abhishek Shah

## License

This project is licensed under the [Your Preferred License].

## Acknowledgements

Thanks to the Streamlit and Gemini LLM teams for the API and platform support.
