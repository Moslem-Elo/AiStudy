Moslem El-Omar 585039

Shevin Walo 584560

How to Use Your AI-Based Learning Assistant for Students Here’s a detailed guide on how to effectively use the AI-Based Learning Assistant for Students application, including setting up and using the features for optimal academic management.

Project Overview Project Name: AI-Based Learning Assistant for Students Goal: To help students manage their academic schedules, track deadlines, and create personalized study plans using AI-driven insights. Target Users: HTW University Students Problem Statement: Students struggle to keep track of deadlines, exam dates, and study schedules, which can negatively impact their academic performance. Solution: The application integrates with Moodle to fetch assignment deadlines and provides personalized study plans, reminders, and study recommendations through AI.

How to Set Up the Application

Install Necessary Packages Ensure you have Python installed on your machine. Then, install the required packages using pip: pip install streamlit openai requests

Obtain an OpenAI API Key Register: Create an account on OpenAI's website. Credit Your Account: Add a minimum amount of 5€ to your account. Get Your API Key: Go to the API section on your OpenAI dashboard and generate a new API key.

Add Your API Key to the Application In the main.py file of your project, add your OpenAI API key:openai.api_key = „your-openai-api-key-here"

Run the Application Start the Streamlit app with the following command: streamlit run main.py The application will open in your default web browser.

How to Use the Application

Login to Your Moodle Account Navigate to the Login Section: Enter your Moodle username and password. Click the Login Button: The application will fetch your assignment data from Moodle.

View Your Assignments Once logged in, you will see a list of your assignments: Course: The name of the course. Due Date: When the assignment is due.

Chat with the AI Ask the AI questions related to your academic tasks: Example Questions: "What are my upcoming assignment deadlines?" "How should I divide my time between my assignments and exam preparation?"

Understand the AI’s Recommendations The AI will provide responses based on your assignment data and your questions.
