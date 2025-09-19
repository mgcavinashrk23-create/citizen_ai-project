# citizen_ai-project
Citizen AI: Intelligent Citizen
Engagement Platform
Generative AI with IBM
👥 Team leader
-Avinash R

👥 Team Members
kamalesh S                                                                                                                                                          kiruba sagar s                                                                                                                                                      kaviraj k             
📌 Project Overview
This project is a Gradio web app that runs on Google Colab with a T4 GPU.
It loads the IBM Granite 3.2–2B Instruct model using Hugging Face transformers.
The app has two main features:

1. City Analysis → Gives crime index, accident rates, and overall safety for any city.


2. Citizen Services → Answers public service and government policy–related queries.
The interface has two tabs for these tasks and provides AI-generated responses in real time.


🚀 Features
1. Runs in Google Colab with T4 GPU for faster AI responses.


2. Uses IBM Granite 3.2–2B Instruct model for natural language generation.


3. City Analysis Tab → Gives crime index, accident rates, and overall safety report of a city.


4. Citizen Services Tab → Provides AI-powered answers to public service and government policy queries.

🛠️ Tech Stack
1. Google Colab + T4 GPU → Cloud environment with GPU acceleration for faster model inference.


2. Python → Main programming language.


3. PyTorch (torch) → Deep learning framework used to run the IBM Granite model.


4. Hugging Face Transformers → For loading the pretrained ibm-granite-3.2-2b-instruct model and tokenizer.

📂 Project Structure
1. Install & Import Libraries → Install transformers, torch, gradio and import required modules.


2. Load Model & Tokenizer → Load ibm-granite-3.2-2b-instruct with GPU/CPU compatibility.


3. Helper Function (generate_response) → Handles text generation with sampling and decoding.


4. Feature Functions

city_analysis() → Generates city crime, accident, and safety analysis.

citizen_interaction() → Answers government and civic-related queries.



Demo Video
Watch our project demo here: Click to Watch
https://drive.google.com/file/d/1-3DeolXVMX8EQwV01ZkV_PAoQ8K6y_gH/view?usp=drivesdk

⚡ How to Run
Clone the repository:
git clone https://github.com/mgcavinashrk23-create/citizen_ai-project
