**Live Speech Recognition and Translation :**
----------------------------------------------
This project enables real-time speech recognition and translation using Python. It utilizes various libraries to transcribe spoken language into text and translate it into the desired language, followed by converting the translated text back into speech.

**Features :**
-----------------------
**1. Live Speech Recognition:** Capture spoken language in real-time using the microphone.

**2. Translation:** Translate the recognized speech into different languages using the Google Translate API.

**3. Text-to-Speech Conversion:** Convert the translated text back into speech using Google Text-to-Speech (gTTS).

**4. Easy Installation:** Simple setup with pip for required packages.

**Requirements :**
-------------------------------
To run this project, you need to install the following Python packages:

SpeechRecognition: pip install SpeechRecognition

googletrans: pip install googletrans

gtts: pip install gtts

playsound: pip install playsound // If encountering errors, downgrade the playsound version using pip install playsound==1.2.0.

**Usage :**
-------------------
Run the main script live_translator.py.

Speak into the microphone when prompted.

The speech will be transcribed, translated, and played back.

Feel free to customize the script or contribute to the project by forking the repository and submitting a pull request.

Acknowledgements
This project relies on the following libraries:

SpeechRecognition

googletrans

gTTS

playsound
--------------------------------------------------
License: This project is licensed under the MIT License.
