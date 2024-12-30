import pynput
from pynput.keyboard import key,Listener

def on_press(key):
    try:
       print('{0}'.format(key.char))
except attributeError:
       print('{0}'.format(key))

       def on_release(key):
       if key==key.esc:

       return False

      with listener(
      on_press=on_press,
      on_relese=on_release)as listener:
 listener.join()     
     
  
  
