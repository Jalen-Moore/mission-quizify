# Overview
Gemini Quizify is a Python web application that leverages the Google Gemini AI to create AI-generated multiple choice quiz questions from user-provided pdf files.

Gemini Quizify prompts the user to enter in files regarding a specific topic. Then, the user must give a name for the quiz as well as the number of questions (1 - 10), and the application will generate that many questions regarding the specific topic, using the provided files to fact-check.

The purpose of this application is to help provide educational resources by using AI-generated content.

# Python Required Installations
streamlit
chromadb
langchain
langchain-google-vertexai
pypdf
