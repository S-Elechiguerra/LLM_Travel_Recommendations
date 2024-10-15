# AI-Powered Travel Advisor
Overview
This repository contains a Python-based interactive travel advisor that leverages OpenAI's API and cosine similarity to recommend travel destinations based on user preferences. The application filters destinations by interests, budget, and travel type, and allows users to ask AI-powered questions about their recommended destinations.

Features
Gather User Preferences: The program collects user input for interests, budget, and travel type.
Destination Recommendations: Uses TF-IDF vectorization and cosine similarity to suggest travel destinations that align with user preferences.
Interactive Q&A with OpenAI API: Allows users to ask detailed questions about their recommended destinations using the OpenAI API.
Installation
Clone the repository:

bash
Copy code
cd ai-powered-travel-advisor
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Set up your .env file with your OpenAI API key and other necessary credentials:

makefile
Copy code
OPENAI_API_KEY=your_openai_api_key
Usage
Run the script:

bash
Copy code
python travel_advisor.py
Follow the prompts to input your travel interests, budget, and preferred travel type.

The program will suggest top travel destinations based on your preferences and offer the option to ask AI-powered questions about the destinations.

Example
python
Copy code
# Example input during the interactive session:
Interests: culture, beaches
Budget: medium
Travel Type: adventure
The system will provide destination recommendations and offer the ability to ask follow-up questions using OpenAI.

Files
travel_advisor.py: Main script for gathering user preferences, recommending destinations, and interacting with OpenAI.
.env: Environment file to securely store your OpenAI API key.
requirements.txt: List of Python dependencies.
Dependencies
pandas: For managing and filtering the travel destination data.
scikit-learn: For TF-IDF vectorization and cosine similarity calculations.
openai: To interact with OpenAI's API for the Q&A feature.
python-dotenv: For loading environment variables.
License
This project is open-source and licensed under the MIT License. Feel free to use and modify it as per your needs.

Enjoy discovering your next adventure with AI-Powered Travel Advisor!

Team Members:
Lidia Mayor
Adrán Benítez
José Miguel Sánchez
Saraluz Elechiguerra
