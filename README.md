# deepseekr1-playground
Running DeepSeek R1 locally to play around with it. I did this using a Mac.  


My Steps (Thank you Rohan Paul, Twitter: @rohanpaul_ai):

1. Downloaded Ollama
2. The following DeepSeek-r1 models are available thru ollama, run whichever you prefer and think will be able to run locally on your machine:
1.5B version (smallest):
ollama run deepseek-r1:1.5b

8B version:
ollama run deepseek-r1:8b

14B version:
ollama run deepseek-r1:14b

32B version:
ollama run deepseek-r1:32b

70B version (biggest/smartest):
ollama run deepseek-r1:70b

The larger they are --> need more GPU power. I followed the suggestion of starting with deepseek-r1:8b. Running the appropriate command on my terminal allows for local usage. 
3. As per Rohan's suggestion, I downloaded an AI chatbot application for a better (or more aesthetically pleasing) user experience. I used Rohan's own application: https://chatboxai.app
  1. I chose to use his because it is privacy focused, stores all your data locally—from conversation histories to personal settings. Everything stays on your device, giving you full control. DID I MENTION IT'S FREE? 
  2. In ChatBOX -> go to settings and switch the model provider to Ollama. You can ignore the built-in cloud AI options because we will be running the models locally.
  3. I will say then when I set it up, the DeepSeek-r1 model that was available for me was deepseek-r1:70b. I wasn't sure if my laptop specs would handle that, so I went back on my terminal, ran `ollama run deepseek-r1:8b`, and then re-configured my settings on the chatbox app.
  5. Set up the Ollama API host - the default setting is http://127.0.0.1:11434, which should work from the get-go. Here is how:
     1. On MacOS run the following commands:
        1. OLLAMA_HOST=0.0.0.0
        2. OLLAMA_ORIGINS=*
        3. I restarted the chatbox app after running these, checked my settings before continuining on. 
  7. Pick the model and hit save. Now you're ready to chat with DeepSeek-R1 while running it locally!

