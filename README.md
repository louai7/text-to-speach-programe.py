# text-to-speach-programe.py
from gtts import gTTS import os import playsound louai=input("enter a phrase :"); print("pleas select the languge --> |fr-> for franch| |en--> for english| |ar--> for arabic| ") lan=input("enter the languge :"); tts=gTTS(louai,lang=lan) tts.save('audio.mp3') playsound.playsound('audio.mp3') os.remove('audio.mp3')
