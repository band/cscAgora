# cscAgora
Some scripts and software to access content on the cscAgora Mattermost server.

This repository holds scripts to access content on the CSC Agora
Mattermost server. The scripts were developed on macOS and written in Python3.

## Get messages from a specific channel

## Installation and use

1. clone or copy repository contents to some directory

2. These tools are all written in Python3; my way of running them is:
   - set up working Python3 virtual environment
```
   $ python3 -m venv venv
   $ source venv/bin/activate
```     
   (remember to `pip install -r requirements.txt`)

```
./mm-getMessages.py -c "channel name or part of it"
```
