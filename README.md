Overview

This Python program is a speech translation tool that uses a combination of speech recognition, language translation, and text-to-speech technologies to convert spoken sentences into translated speech in a target language. It features a user-friendly GUI built with tkinter and integrates functionality for real-time language translation.

Usage Instructions

1.	Setup and Requirements:
Install required libraries:

        pip install speechrecognition googletrans==4.0.0-rc1 gtts pygame

Ensure your microphone is connected and configured correctly for use.

3.	Running the Program:
Execute the script in your Python environment:

        python translator.py

5.	Using the Application:
Click the "Start Translation" button.
Speak the name of the target language when prompted (e.g., "French", "Spanish").
Speak the sentence you want to translate.
View the translated text in the interface and listen to the translated audio.

7.	Supported Languages:
The program supports several languages including Tamil, Spanish, French, German, Hindi, Chinese, and more. For a complete list, refer to the language_mapping dictionary in the code.

9.	Playback:
The translated speech is played directly within the app using pygame.


