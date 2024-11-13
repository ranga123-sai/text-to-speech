# text-to-speech
import pyttsx3
engine = pyttsx3.init()
text = input("enter the text you want to convert into voice:")
engine.say(text)
engine.runAndWait()
