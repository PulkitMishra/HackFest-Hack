# HackFest 2019
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PyPI status](https://img.shields.io/pypi/status/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
[![GitHub release](https://img.shields.io/github/release/Naereen/StrapDown.js.svg)](https://GitHub.com/Naereen/StrapDown.js/releases/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


![Alt text](assets/image.png?raw=true "Title")


#### *eye.ai* - WeUseTabs


Look around. What do you see?
Your computer flashing Google's I/O live.
Your favorite novel that you've been cherishing upon lying there in the corner.
Oh! Look at that friend of yours who is heading right towards you to snatch that tasty burrito from your hand.
RUN!
No. Stop.

Now, close your eyes. What do you see?
DARKNESS.
No computer. No novel. Nothing but darkness.
Spare a moment from your busy life to realize that there are 40 million people in the world whose entire life has been consumed battling this darkness due to visual impairment.

We propose an AI based System, *'eye.ai'* to completely revolutionize the lifestyle of the visually impaired by providing real time analysis of surroundings and helping them to interact with the environment around them. The solution consists of a wearable with a camera attached to it that is connected to Raspberry Pi. Voice commands will be sent through Alexa which will then fetch data from the Pi camera, process the data on a cloud server using trained models and respond appropriately with speech by providing information about the environment, recognizing known faces, helping in commuting by avoiding obstacles and also in reading books, handwritten text, information on webpages out loud on being instructed to do so by the user.

### Features:
- Environmental Analysis to give the visually impaired a brief summary of his/her surroundings.
- Identifies faces of known people(friends and relatives) and informs about their presence
- Object Identification (like clocks)
- Identification and option to read out texts in surroundings, i.e- banners, information at stations, etc.
- Alexa AI for voice interface

### How to Run:

1. **Create Virtual Environment** :
  - python3 -m virtualenv env
  - source env/bin/activate
2. **Install Requirements** : 
  - pip3 install -r requirements.txt
  - sudo snap install ngrok
3. **Run voice.py** :
  - python3 main.py
  - cd server
  - bash ./ba.sh
4.  **Run ngrok in a new terminal**
  - ngrok http 5000

### Contributors:

- @satyamtg
- @zeus0789
- @jay4jyotika
- @PulkitMishra
