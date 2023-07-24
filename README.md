# GrammarChecker
**Project Description: Grammar Check Desktop Application using OpenAI API**

This project is a Grammar Check Desktop Application built using Python and the OpenAI API. The application allows users to input paragraphs or text and checks for 
grammar mistakes using OpenAI's language models. Users can choose from a selection of available models, set the maximum number of tokens (words) for processing the 
input, and control the response randomness with a temperature slider.

**Key Features:**

Model Selection: Users can choose from a list of supported OpenAI language models, including options like GPT-3.5-turbo, Davinci, and others.

Input Text: Users can input or paste paragraphs or text that they want to check for grammar errors into the application.

Max Tokens Limit: Users can set the maximum number of tokens (words) to be processed by the OpenAI API using a slider. This helps manage the API usage and response 
length.
Temperature Control: The application allows users to set the temperature value to control the randomness of the response from the OpenAI API.
Real-Time Updates: The application provides real-time updates for the selected model, maximum tokens, and temperature through labels and sliders.
Submit and Reset: Users can submit the input text for grammar checking using the "Submit" button. Additionally, a "Reset" button is available to clear the input 
and reset the sliders to default values.
Output Display: The application displays the grammar-checked version of the input text in an output text field, providing instant feedback.

**How to Use:**

Launch the Grammar Check Desktop Application.
Choose a language model from the dropdown list (ComboBox).
Input or paste the paragraph or text to be checked into the "Prompt" TextEdit.
Adjust the "Max Tokens" slider to set the maximum number of tokens for processing.
Adjust the "Temperature" slider to control the response randomness.
Click the "Submit" button to send the input for grammar checking.
View the grammar-checked output in the "Output" TextEdit.

**Prerequisites:**

Python installed on the system.
OpenAI API key, which should be stored in a "password_manager.ini" file (as described in the documentation).

This project provides a user-friendly interface for grammar checking and leverages the power of the OpenAI API and Python to offer a powerful and efficient grammar 
checking solution. It is designed to be beginner-friendly and can be used as a practical learning resource for building desktop applications with Python and PyQt 
framework.
