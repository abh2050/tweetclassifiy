![](https://miro.medium.com/v2/resize:fit:1400/1*xlCyGCKz8Wxws7gP_XcjnQ.png)
# Tweet Classifier Using Gemini LLM
![image](https://github.com/abh2050/tweetclassifiy/blob/main/pic.png)
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
