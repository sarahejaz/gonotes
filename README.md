# gonotes
Audio_Features.ipynb: Audio features(along with their plots) extracted from audio files by Zero Crossing Rate, MFCC, and Chroma frequencies. 

pitchTracker.ipynb: Yin algorithm for pitch tracking.

video2text.ipynb: In this file we have transcribed the text from video and tried to generate the summary of the Text. For transcription, we have used Deep Speech Model. Then we punctuated the text using the pip punctuator, then we did some preprocessing on the text using nltk, after that we used the pip sumy summarizer and then LSA Topic Modeling technique to extract key words.

---
UPDATE:

goNotes.ipynb contains all the code dealing with audio and text: extraction of audio, analysis of audio features such as amplitude and frequency, extraction of keywords and key sentences, and so on.

It also contains Flask code that uses Ngrok to run on Google Colab. The HTML pages used for the frontend are in the templates folder.
