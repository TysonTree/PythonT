 Opening and Reading/Printing File
- The following code is used to Open, Read, and Print out the text in a your File.

== Operating in PyCharm
== Specific Codes
== Trouble Shooting

FIRST == Operating in Pycharm
-the following code was written in PyCharm. 
Easily download PyCharm @ -- https://www.jetbrains.com/pycharm/download/?section=linux

SECOND == Specific Codes
- Necessary Variables:
file_path = "add/your/file/path.txt"
- Code: 
with open(file_path, "r") as file:
  file_content = file.read()

  print(file-content)

THIRD == Trouble Shooting 
- Ensure file ends in .txt (error appears as such [File "<frozen codecs>", line 322, in decode UnicodeDecodeError: 'utf-8' codec can't decode byte 0xc5 in position 10: invalid continuation byte])
- Ensure file path is correct (easiest way is to copy and paste exactly from files bar)
- Ensure code is following all necessary rules (added tip is to make code follow Snake case or similar convention for user friendly code).

