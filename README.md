# automa-o_insta

import pyautogui
import time

pyautogui.PAUSE = 1

#Entrar no site
pyautogui.press("Win")
pyautogui.write("chorme")
pyautogui.press("enter")

link = "https://www.instagram.com/"
pyautogui.write(link)
pyautogui.press("enter")

time.sleep(3)

pyautogui.click(x=954, y=291)
pyautogui.write("anthony_henriquecs")
pyautogui.press('tab')
pyautogui.write("senha")
