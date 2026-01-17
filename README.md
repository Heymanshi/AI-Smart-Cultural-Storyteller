# AI-Smart-Cultural-Storyteller

## Overview
AI Story Teller is an educational project that generates simple and engaging stories to explain learning concepts.  
The goal of the project is to make learning more interesting by converting topics into age-appropriate stories using AI.

This project demonstrates the use of Large Language Models (LLMs) for educational content generation.

---

## Project Track
AI Applications – Individual Open Project

---

## Features
- Story-based explanation of educational topics  
- Age-specific storytelling approach  
- Text-based story generation  
- Speech-to-text and text-to-speech support in the full application  
- Focus on safe and responsible AI usage  

---

## Repository Structure
- **AI_Story_Teller_Project_FINAL.ipynb**  
  This notebook is the primary evaluation artifact.  
  It contains the complete project description, implementation logic, sample outputs, evaluation, and ethical considerations.  
  The notebook runs end-to-end without requiring any external cloud credentials.

- **app.py**  
  This file contains the full Flask-based implementation of the project using Google Vertex AI and speech services.  
  It represents the real-world deployment version of the application.

---

## Execution Note
The `app.py` file requires a valid Google Cloud setup, including an active project, enabled APIs, and service account credentials.  
Since cloud credentials cannot be shared publicly, the Flask application may not run without configuration.

For evaluation purposes, the Jupyter Notebook uses a demo-safe implementation that runs without external dependencies.

---

## Technologies Used
- Python  
- Jupyter Notebook  
- Flask  
- Google Vertex AI (Gemini)  
- Natural Language Processing (NLP)  

---

## Ethical Considerations
- The system avoids generating harmful or inappropriate content  
- No personal user data is collected or stored  
- The application is intended only for educational use  
- Responsible AI practices are followed  

---

## Conclusion
This project shows how AI-driven storytelling can improve learning by making explanations more engaging and easier to understand. The approach highlights the potential of LLMs in modern educational applications.

---

## Author
Student Project – Academic Submission
