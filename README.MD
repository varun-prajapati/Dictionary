Application 1: Dictionary

Features:
- enter word and get definition(s) of the word as per language
- definitions are returned regardless of the case in which word is entered (Hello, hEllO, hello, HELLO, etc. are all same)
- get nearest matching words from dictionary if entered query does not exist in language
- application terminates when word is found in dictionary or /exit is entered

Additional Files:
1] data.json: contains stored database of english dictionary in python dictionary format i.e. key-value(s) pairs

Libraries:
os      : to clear screen in windowsand linux terminals
json    : to get dictionary data from data.json file
difflib : to get close matches of usery query

functions:
clear        : to clear the display screen
printer_func : to print definition(s) of word
data_check   : to check if entered query exists in dictionary in any case formatting

How to use:
1] Download data.json and Ver1.py in same folder
2] Install Python 3 
3] In windows, open command prompt in current folder and type python Ver1.py
4] in linux, open terminal in current directory and type python3 Ver1.py