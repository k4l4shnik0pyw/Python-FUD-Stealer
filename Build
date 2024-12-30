import clear
import os


print("Before starting, make sure you didn't renamed the main.py fileand you have correctly entered your Chat ID and your Telegram bot token.\n\n")
input("Press ENTER to continue...")
icon = False
clear.clear()
ask_icon = input("Do you want to add an icon ? y/n")

if ask_icon in ["yes", "YES", "y", "Y"]:
  icon_path = input("Please enter the FULL path of the .ico file : ")
  icon = True
else:
  icon = False

input("\n\nPress ENTER to build the executable...")

if icon == True:
  build_command = 'pyinstaller --noconfirm --onefile --windowed --icon f"icon_path" main.py'
else:
  build_command = 'pyinstaller --noconfirm --onefile --windowed main.py'

os.system(build_command)
