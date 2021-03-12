# Simple-Python-Chatbot


# TODO WEB UI
* make chat UI into a flask object
* add intent to log output to make it easier to track
* load images, webpages, etc. from intent
* bind chat bot to telegram or similar
* check for cyrillic support with NLTK\

# Deprecated TODO
* center the UI in the screen
* I've received some index out of range errors. Need to set up error catching.
* clean up the UI
* done in the code: pop responses so that users don't necessarily see same response twice in the same session
* call function from intent
* set up a requirements document (poetry? requirements.txt?)
* figure out a json UI 
  * It's really not convenient to work with json though editing the json file here in repl.it is not hard.


# Done
* convert UI from tk to pysimple GUI: Thanks Horst!
* response intent is included in the chat UI: Thanks Horst!
* get logging to work: Thanks Horst!
  * Generates a log file with time stamp
  * I need to see how the chat brain is parsing input.
  * I don't see any evidence in the code for recording what the users type
* bind return key in UI to send user input: Thanks Horst!
  

Creating a simple Python chatbot using natural language processing and deep learning.

1. run the libraries.py first
Check your dependencies. A requirements file or poetry config would be useful here.

1. update the intents.json file

2. run train_chatbot.py

3. run chatgui.py


# Questions
* How to call a Python function from a json file?
* how to process logs more effectively?



# misc
* the intents file is to support chatbot for a Toastmasters club.
* convert_json_to_csv.py
I found this on the web here
https://datatofish.com/json-string-to-csv-python/
and was hoping a csv file would be easier to edit than json. No such luck.
