# CleanMind
App in preparation for the Google's Gemini contest.

I worked on the python scripts to download emails and record and transcribe meetings.

The python scripts work by contacting Gmail API to collect Emails information, then it will decode and encode the body of the email in order to create a txt file that can be used by other parts of the program.

The Recording and Transcribing of meetings works by using a python script that connects with the Windows WASAPI to be able to record audio coming from the computer. Then, the recorded audio is constantly being fed into google's speech to text in Speech Recognition library. The function outputs text strings so we store it in a list sequentially.
