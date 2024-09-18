# VisionQA
VisionQA is a visual question answering (VQA) application leveraging the Vision-and-Language Transformer (ViLT) model.
This project uses the dandelin/vilt-b32-finetuned-vqa pre-trained model to process images and answer questions related to the visual content. 
The application integrates FastAPI for handling form data and file uploads, allowing users to submit images and questions to receive accurate answers based on the visual context.

# Key Features
* Utilizes the ViLT model for advanced visual question answering.
* Processes images and text inputs to generate relevant answers.
* Built with FastAPI for efficient and scalable API endpoints.
* Supports form data and file uploads for seamless user interaction.

# Technologies Used
* FastAPI
* Transformers (Hugging Face)
* PIL (Python Imaging Library)
* Uvicorn (ASGI server)

# Installation
1. Clone the repository
2. Create and activate a virtual environment: [python -m venv .venv] [.venv\Scripts\activate] (On windows) [ource .venv/bin/activate] (on macOS/Linux)
3. Install the required packages: [pip install -r requirements.txt]

# Usage
1. Run the FastAPI server: [uvicorn main:app --reload]
2. Access the API: Open your browser and go to http://127.0.0.1:8000/
