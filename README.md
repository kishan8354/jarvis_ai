
# JARVIS-AI-ASSISTANT

<p align='center'>
  <img src = "https://github.com/JoelShine/JARVIS-AI-ASSISTANT/blob/main/jarvis-assets/J.A.R.V.I.S.png" height='300' width='300'>
  </p>

JARVIS is an offline AI assistant built with `Vosk` for speech recognition, `pyttsx3` for text-to-speech, and `AIML (ALICE)` for intelligent conversation handling.

## 🔹 About JARVIS

**J.A.R.V.I.S** stands for **Joel's Artificial Realistic Virtual Internet Service**. Inspired by the AI from the Iron Man movies, this assistant is fully developed in Python and performs best on Windows.

## 🔸 Features

- Conversational AI using AIML (ALICE)
- Offline speech recognition (Vosk)
- Offline text-to-speech (pyttsx3)
- Program launching through voice commands
- Fully local and privacy-friendly (no cloud required)

## 🔹 Installation

1. Install **Python 3.7 or higher (64-bit recommended)**.
2. Open terminal/command prompt in the project folder and install dependencies:

   ```bash
   pip install -r requirements.txt


### Getting the models for our Speech Engine

<ul>
  <li><h4>Now, the next step is to download the models for our vosk speech Engine. Go to this website for downloading the model of your choice - https://alphacephei.com/vosk/models</h4></li>
  <li>There are models available for several accents of English and I am currently using the Indian Model. If you are in USA, you could download the usa-english model. The model is not uploaded on github as it will take up large space.<br></li>
  <li>Once you have downloaded the Vosk speech engine model, then extract all the files inside the downloaded folder and copy the files inside the <b>'vosk_speech_engine/model'</b> folder. Make sure to place this in the model folder inside vosk_speech_engine.<br></li>
  <li>Once you have placed that, we can successfully run our JARVIS program<br><br></li>
  </ul>

## Running the Python script

Now we can run our python script. Just navigate to the cloned directory and open cmd and then type :
```python
python jarvis.py
```
This will initialize the python program. If you run into any problems during the installation of any modules, feel free to open an [issue](https://github.com/JoelShine/JARVIS-AI-ASSISTANT/issues). Thanks for supporting this project and happy coding !!
