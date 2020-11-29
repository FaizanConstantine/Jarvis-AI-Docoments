# Jarvis-AI-Docoments
AI
import pyttsx3
engine = pyttsx3.init('sapi5')
voices= engine.getProperty('voices') #getting details of current voice


engine.setProperty('voice', voice[0].id)


def speak(audio):
       pass      #For now, we will write the conditions later.
def speak(audio):

engine.say(audio) 

engine.runAndWait() #Without this command, speech will not be audible to us.
def wishme():

hour = int(datetime.datetime.now().hour)
if hour>~0 and hour <12:
 speak ("Good Morning!")
 
elif hour>=12 and hour<18:
speak ("Good Afternoon!")

else:
speak ("Good Evening!")

speak ("I am FRIDAY Sir. Please tell me How mayb i help you")
if __name__=="__main__" :

speak("Hello Sir. My name is FRIDAY. You made me to keep and help you. How can i hlep you sir?")
