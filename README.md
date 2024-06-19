# AI Chatbot Framework

Welcome to the AI Chatbot Framework repository! This framework provides a foundation for building and deploying AI-powered chatbots using Python and Flask.

## Project Structure

The project is organized into the following directories and files:

### ai_model/

This directory contains files related to the chatbot model and its training:

- `chat_bot.py`: Python script defining the chatbot model and its training logic.
- `main.py`: Entry point for running the chatbot or training the model.
- `chatbot_model.h5`: Pre-trained model weights in HDF5 format.
- `intents.json`: JSON file containing intents and responses for training the chatbot.
- `classes.pkl`: Pickle file storing the classes used in the intents.
- `words.pkl`: Pickle file storing the words used in the intents.

### web_app/

This directory contains files related to the web-based chatbot interface:

- `chatbot_app.py`: Python script defining the Flask web application and integrating the chatbot model.
- `templates/`: Directory containing HTML templates for the web app.
  - `index.html`: HTML template for the chatbot interface.

### venv/

This directory typically contains the virtual environment where Python dependencies are installed.

### requirements.txt

File listing all Python dependencies required to run the project. You can install them using `pip install -r requirements.txt`.

## Getting Started

To get started with the AI Chatbot Framework, follow these steps:

1. **Set Up Environment:**
   - Create a virtual environment (optional but recommended): `python -m venv venv`.
   - Activate the virtual environment: `source venv/bin/activate` (Linux/macOS) or `venv\Scripts\activate` (Windows).

2. **Install Dependencies:**
   - Install required packages: `pip install -r requirements.txt`.

3. **Run the Chatbot:**
   - Navigate to the `web_app/` directory: `cd web_app`.
   - Run the Flask application: `python chatbot_app.py`.
   - Open your web browser and go to `http://localhost:5000` to interact with the chatbot.

4. **Train or Customize the Chatbot (Optional):**
   - Modify `intents.json` to add new intents or customize existing ones.
   - Train the chatbot model using `python main.py`.

5. **Deploy (Optional):**
   - Deploy the web application to a server for public access.

## License

This project is licensed under the MIT License

## Acknowledgments

- This project was inspired by the need for a simple yet powerful AI chatbot framework.
- Thanks to OpenAI for their GPT models that sparked interest in conversational AI.

