
##A simple AI-powered platform to check news and spot fake stuff.

**what it does**
- fast news check: Analyzes news in seconds.
- multiple checks: Evaluates the source, content, facts, and writing style.
- confidence scores: Gives a percentage on how real the news is.
- detailed breakdown: Explains why the news was flagged as fake or real.
- optional source input: Include the source for better accuracy.
- clean ui: Smooth, responsive interface.
#tech-stack
##frontend
- next.js
- typescript
- tailwind.css
- recoil
##backend

- Python
#local setup

##Prerequisites

 - node.js 22+ and npm
 - python 3.8+
 - git
#1. Docker setup

assuming you have vscode and docker installed
super minimal

just run-:

 '''  git clone https://github.com/pulkit777exe/haawww
  docker compose up'''

  and you are good to go

  #normal setup

  ##1. clone the repository

  '''git clone https://github.com/pulkit777exe/haawww
cd haawww'''
##2(a). start the backend (windows)

'''cd ml-backend
python -m venv venv
source venv/bin/activate 
pip install -r requirements.txt
python run.py'''

##2(b). start the backend (mac / linux)

'''cd ml-backend
python -m venv venv
pip install -r requirements.txt
python3 run.py'''

Backend URL: http://localhost:8000

##3. start the frontend
'''cd frontend
npm install
npm run dev'''

Frontend URL: http://localhost:3000

#how to use

Enter news text – Paste any news snippet.

Add source (optional) – Include the source for better accuracy.

Hit verify – Get instant results.

Research analysis – See a full breakdown of the classification.

##api docs

Not yet done

##wanna help?

fork the repo

'''make a new branch: git checkout -b feature/cool-feature

commit your changes: git commit -m 'add cool feature'

push to the branch: git push origin feature/cool-feature

open a pull request
'''

#stuck

- open an issue on github
- read the backend readme in ml-backend/readme.md



haawww: your news sidekick.


