import pyautogui, pyperclip, random, time
from http import server
from re import S
from this import d
from unicodedata import name
import keyboard
import smtplib

from threading import Semaphore, Timer

print("Tool spam 1.0")
msg = input("Nhap noi dung can spam: ").split(" ||")
n = int(input("Nhap so lan spam =)) "))
m = float(input("nhap so time delay: "))

print("Chuan bi")
for i in range(5,0,-1):
    print(i,end="...",flush='True')
print('Bat dau')

for i in range(n):
    pyperclip.copy(random.choice(msg))
    pyautogui.hotkey("ctrl","v")
    pyautogui.press("enter")
    time.sleep(m)
