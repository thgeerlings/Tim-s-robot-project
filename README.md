# Tim-s-robot-project
A repo for working on a deeplearning chatbot.

These are the files of a deeplearning chatbot I am working on. 
Chatbot is the code I edit for the other files.(this file will most likely not run properly)
Training is the file I use to train my chatbot.
Audio to speech converts the chatbots text into google text to speech.
Get_audio to speech converts to users voice to text inputs.

These are my sources for my code.
https://pytorch.org/tutorials/beginner/chatbot_tutorial.html
The main code.
https://www.techwithtim.net/tutorials/voice-assistant/
The google text to speech code.

Be mindfull that you do need to repath some of the directories if you want to run the code.
(corpus = os.path.join("D:\Documents\Python\intents\\", corpus_name)This is line 24 in "training".
(save_dir = os.path.join("D:\Documents\Python\intents\Cornel save map", "save") This is line 128 in "training".
Plus you need to have a formatted version of cornel-movie dialog corpus, this is a dataset.
This can be done using the chatbot file.
And the code is currently running of a trained file meaning that you might need to set the loadfile name for your checkpoint to none (line 581 in the file training).
