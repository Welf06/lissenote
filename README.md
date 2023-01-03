# Lissenote

Lissenote is a web app that converts audio and video files into notes, providing a range of useful features for users. These features include live audio recording, multi-language support for notes, the ability to include images from videos (currently only for videos centered around ppts), and optional Wikipedia links in notes.

Lissenote is built with a react frontend and a flask backend, and it uses wave2vec for speech recognition. The app also makes use of a few APIs, including the Wikipedia API and the Google Translate API, to enhance its functionality and usability.

This code sample was a winner in the Smart India Hackathon 2022. The frontend code of Lissenote is contained in this repository, and the backend code is available at https://github.com/GNAR55/lissenote_backend. Both the frontend and backend were developed by a team, with the team member responsible for this repository focusing on the frontend and other team members working on the backend and model training.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run Lissenote, you will need to have the following software installed on your system:

- Node.js (for the frontend)
- NPM (comes with Node.js) (for the frontend)
- Python 3 (for the backend)
- Flask (for the backend)


### Frontend Installation

1. Clone the repository:

```npm
git clone https://github.com/Welf06/lissenote.git
```

2. Install the dependencies:
```
npm install
```


3. Start the development server:

```
npm start
```
The frontend app should now be running on http://localhost:3000.


### Backend Installation

1. Clone the repository:
```
git clone https://github.com/GNAR55/lissenote_backend.git
```


2. Install the dependencies:
```
pip install -r requirements.txt
```


3. Start the development server:
```
python app.py
```


The backend should now be running on http://localhost:5000.

## Built With

- [React](https://reactjs.org/) - The frontend framework used
- [Flask](https://flask.palletsprojects.com/) - The backend framework used
- [Wave2vec](https://github.com/TomiBajsic/Wave2Vec) - Used for speech recognition
- [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page)


