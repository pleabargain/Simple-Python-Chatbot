# Simple-Python-Chatbot

# TODO
* clean up the UI
* pop responses so that they don't get used twice in the same session
* call function from intent
* load images, webpages, etc. from intent
* bind chat bot to telegram or similar
* set up a requirements document (poetry? requirements.txt?)
* check for cyrillic support with NLTK
* figure out a json UI 
  * It's really not convenient to work with json


# Done
* convert UI from tk to pysimple GUI
* response intent is included in the chat UI
* get logging to work
  * Generates a log file with time stamp
  * I need to see how the chat brain is parsing input.
  * I don't see any evidence in the code for recording what the users type
* bind return key in UI to send user input
  

Creating a simple Python chatbot using natural language processing and deep learning.

1. run the libraries.py first
Check your dependencies. A requirements file or poetry config would be useful here.

2. run train_chatbot

3. run chatgui.py


# Questions
* How to call a Python function from a json file?



# misc
* convert_json_to_csv.py
I found this on the web here
https://datatofish.com/json-string-to-csv-python/
and was hoping a csv file would be easier to edit than json. No such luck.