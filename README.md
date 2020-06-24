# Text-to-Speech Example

Example app for converting text to speech using Amazon Polly.

This app is based on the source code found here https://docs.aws.amazon.com/polly/latest/dg/examples-python.html. I did some modification to do the following:

- Add support for SSML
- Allow to choose TTS engine to either standard or neural

## Running

Create a virtual environment:

``virtualenv env``

Activate the virtual environment:

``source bin/env/activate``

Install Python dependencies

``pip install -r requirements.txt``

Run the app:

``python server.py``