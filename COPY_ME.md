# xp-Chat-Bot-For-Discord
This is a simple program that will print out a statement every 65 seconds giving you xp.
ITS FOR PYTHON JUST COPY AND PASTE INTO A TEXT FILE AND MAKE SURE YOU HAVE pynput INSTALLED (pip install pynput)


from pynput.keyboard import Key, Controller
keyboard = Controller()
import time

def text():
    x = 1
    while x == 1:
        def say(word):
            time.sleep(65)
            keyboard.type(word)
            keyboard.press(Key.enter)
            keyboard.release(Key.enter)
            

        say("WADOABDOADWOIBWIODIOBD")


text()
