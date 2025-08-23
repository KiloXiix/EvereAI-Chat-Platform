# EvereAI-Chat-Platform
A gui interface for chatting with my EveréAI model but is compatible with ollama models and can pull them from the internet if needed.

# How To Use
1. download the following files from the latest release: EvereAISetup.exe, EvereAISetup-1.bin, EvereAISetup-2.bin, and EvereAISetup-3.bin.
2. place all the downloaded files in the same folder
3. run the exe from inside the folder
4. proceed with the default installation instructions
5. after the program is installed, run the new app
6. when run, the app naturally stays inside the windows tray so you can just click the icon and open the program
7. once the program is open and running, you can either create the default ai model from the ai model file that comes bundled with the program or you can pull a model from ollama using the normal command without the ollama prefix: ex - "pull llama3".
8. Then create a chat, select your model of choice, and send your first message.

# Pulling Models
To pull an ollama model for use, simply press the "Pull Models" button to upen up the section where you then can type "pull model" where "model" is the name of whatever ollama model you want. Then click execute and wait for the on screen notification that the model was either pulled successfully or failed. If pulled successfully, you can start talking with it immediately after creating a chat to talk to it in.

# Future Plans
There are many planned features for this program such as ~~having my model built in on startup (since that's what the program was made for in the first place)~~(COMPLETED), Including audio playback of the model's last response using my custom voice model (also mainly meant for my soon to be built in model), having a 3d avatar that moves and talks as the model responds to the user, and so much more!

# Things To Note
Initial response after opening the app always takes between 5-10 minutes as it needs to warm up.
All the following responses are much faster and can take less than a minute depending on your hardware.
The program saves computer resources by unloading the model after 5 minutes of inactivity which will cause the next response after the unloading to take 5-10 minutes again.

# Disclaimer
This app is still in its early stages and nowhere near complete at this time as of (08/21/2025).
