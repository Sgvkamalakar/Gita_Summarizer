# Gita Summarizer
_Condense, Comprehend and Connect with Gita..._

<p align="center">

<img src="https://github.com/Sgvkamalakar/Gita_Summarizer/assets/103712713/8f09a760-d41a-41bf-8f8f-8f255522b633" height=300 width=300/>
</p>




## Overview
The "**Gita Summarizer**" is an advanced application designed to distill the profound teachings of the Bhagavad Gita into concise and comprehensible summaries. This tool leverages the capabilities of Azure Speech-to-Text and LLMWare's powerful summarization models to provide users with insightful summaries of the Gita's chapters and verses

## Features
1. *Real-time Speech Input:*
   - Users can deliver speech directly through their microphone.
   - The application promptly transcribes the speech in real-time.
   - Summarized versions of the transcribed text are provided for streamlined understanding.

2. *Upload Audio File:*
   - Users have the option to upload audio files in WAV format.
   - The application processes the uploaded audio, transcribing it into text.
   - Summaries of the transcribed text are automatically generated.

3. *Interactive User Interface:*
   - Intuitive and user-friendly interface offering options for real-time speech input or file upload.

4. *Speech Recognition and Summarization:*
   - Harnesses the power of Microsoft Azure's Speech-to-Text API for precise speech recognition.
   - Incorporates LLMware's SLIM Summary Tool to condense transcribed text effectively.

##  Technology Stack

<p align="center">
<img src="https://github.com/Sgvkamalakar/Gita_Summarizer/assets/103712713/5fe1a9f6-51f3-49a1-a730-f05304a96696" width=200px height=200px>
<img src="https://github.com/Sgvkamalakar/Gita_Summarizer/assets/103712713/debb5489-2d44-40fc-88ec-23dd149e4acd" width=200px height=200px>
<img src="https://github.com/Sgvkamalakar/Gita_Summarizer/assets/103712713/1f300911-c20f-420e-ba8c-0f3d06e4ee4e)
" width=250pxheight:150px>
</p>


- *Frontend:*
  - **Streamlit:** For building the interactive web interface.
    
- *Backend:*
  - **Microsoft Azure Speech Service**: Utilized for speech recognition tasks.
  - **LLMware's SLIM Summary Model**: Employed for text summarization.
    
- *Languages and Libraries:*
  - **Python:** Primary programming language.
  - **Streamlit:** Facilitates UI components and interactions.
  - **Requests**: Enables HTTP requests to the speech recognition API.
  - **Azure.cognitiveservices.speech**: Azure SDK utilized for managing speech-to-text functionality.

## How It Works

### 1. *Real-time Speech Input:*
   


   - Upon selecting "Real-time Speech Input," the application configures the microphone to capture user speech.
   - Captured speech is then forwarded to Azure's Speech Service for transcription.
   - The transcribed text undergoes summarization using the SLIM Summary Tool before being presented to the user.

### 2. *Upload `wav` Audio File:*
   
   
   - Users opting for "Upload Audio File" can upload their audio files directly.
   - Uploaded files are sent to Azure's Speech Service via an HTTP POST request for transcription.
   - Post transcription, the text is summarized using the SLIM Summary Tool and displayed to the user.



## Demo 📹


### Use Cases for Gita Summarizer

- **Student Aid**: Quickly grasp key concepts for study sessions and exams.
- **Teaching Tool**: Prepare breif summaries for lessons and sermons.
- **Personal Reflection**: Enhance spiritual practice with daily verse summaries.
- **Group Discussions**: Generate discussion points for study groups and book clubs.
- **Content Creation**: Create focused scripts and articles on the Bhagavad Gita.
  
## Getting Started
To commence with GIta Summarizer:
1. Ensure possession of a valid subscription key and service region for Microsoft Azure Speech Service.
2. Clone the repository using
   ```bash
   git clone https://github.com/Sgvkamalakar/Voice-Vista.git
   ```
3. Install the requirements
   ```bash
   pip install -r requirements.txt
   ```
4. Configure the essential environment variables (subscription_key, service_region, token).
   ```bash
   subscription_key="<subscription_key"
   service_region="<service_region>"
   token="<auth_token>"
   ```
5. Run the Streamlit application and engage with it via the user-friendly web interface using the following command.
   ```bash
   streamlit run app.py
   ```

## Contributor

<p align="center">
  <img src="https://github.com/sgvkamalakar.png" height="200" width="200"/>
</p>
<p align="center">
  Kamalakar Satapathi
</p>

Connect with me on [![LinkedIn](https://img.shields.io/badge/-Kamalakar_Satapathi-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sgvkamalakar)
