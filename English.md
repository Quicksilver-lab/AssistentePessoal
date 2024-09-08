# Personal Assistant with Python

Hello everyone, this is Ana, a virtual personal assistant that listens to your voice commands and executes them!

## Features:

- **⌚ Current time:** "What time is it?"<br>
- **🔎 Google search:** "Search object on Google"<br>
- **🪙 Exchange rate for dollar, euro, and bitcoin:** "What's the dollar exchange rate at the moment?"<br>
- **📰 Last 5 news headlines:** "What are the latest news?"<br>
- **📽️ Top 5 popular movies:** "What are the most popular movies right now?"<br>
- **🎧 Open the best song, band, and album in the world on Spotify:** "What's the best song in the world?"<br>
- **⛅ Weather forecast:** "Weather in São Paulo"<br>
- **🔃 English and Portuguese translator:** "Translate to English"<br>
- **📒 Create and view reminders:** "Create new reminder" or "View reminders"<br>
- **💻 Open programs on your computer:** "Open Discord"<br>
- **💤 Shut down computer in 1 hour or 30 minutes:** "Shut down computer in one hour"<br>
- **❌ Cancel computer shutdown:** "Cancel shutdown"<br>
- **🙋🏽‍♀️ Close the assistant:** "Close assistant"

## Technologies used:

- [Python](https://www.python.org/): programming language
- [Speech Recognition](https://pypi.org/project/SpeechRecognition/): speech recognition
- [gTTS](https://pypi.org/project/gTTS/): voice synthesis
- [Playsound](https://pypi.org/project/playsound/): audio player
- [Beautiful Soup 4](https://pypi.org/project/beautifulsoup4/): web scraping
- [Translate](https://pypi.org/project/translate/)
- Others: os, sys, webbrowser, urllib.request, json, datetime, requests

## How to run:

### **1. Install `Python` on your machine via [this link](https://www.python.org/)**

### **2. Clone [this repository](https://github.com/rafaballerini/AssistentePessoal.git) on your machine:**

- Create a folder on your computer for this program, I recommend naming it **Personal Assistant**
- Open `git bash` or `terminal` inside this folder
- Copy the [URL](https://github.com/rafaballerini/AssistentePessoal.git) of the repository
- Type `git clone <copied URL>` and press `enter`

### **3. Install the required libraries via terminal inside the created folder:**

- gTTS: `pip install gTTS`
- playsound: `pip install playsound`
- beautiful soup 4: `pip install beautifulsoup4`
- speech recognition: `pip install SpeechRecognition`
- translate: `pip install translate`

In case you encounter an error related to any of the imported libraries in the program, search for the name of the library on Google and follow the installation steps required.

### **4. Download the reminder tool:**

- Visit [Notezilla](https://www.conceptworld.com/Notezilla) and download the software
- Use the path `C:\Program Files\Conceptworld\Notezilla` for installation

### **5. Create your API keys:**

**Movies API:**

- Go to [The Movie DataBase](https://www.themoviedb.org/) and create an account
- In settings, go to API and create a new key
- Copy the key and paste it in the `token` of the `movies()` function, replacing the phrase `<yourapikey>`

**Weather API:**

- Go to [Open Weather Map](https://openweathermap.org/) and create an account
- Confirm the received email, then go to settings and access your API Keys
- Copy the key and paste it in the `token` of the `weather()` function, replacing the phrase `<yourapikey>`

### **6. Fill in the paths of the programs on your machine:**

- Search for the paths of the following executable programs on your machine: Google Chrome, Visual Studio, Visual Studio Code, Discord, and Notion
- Below the comment `open programs on the computer`, paste the respective path in each function call
- Example: `os.startfile("C:\Program Files\Google\Chrome\Application\chrome.exe")`
- If you want to add or delete any program, do it using the same pattern in the code

### **7. Run the program via terminal:**

- Type `python assistant.py`

## Studies:

In the `studies` folder, you will find some simple codes I used to learn about the tools, including using others like [espeak](https://espeak.sourceforge.net/) and [pyttsx3](https://pypi.org/project/pyttsx3/)
