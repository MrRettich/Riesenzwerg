# Riesenzwerg

Riesenzwerg is a fork of `hugh`. (https://github.com/IgnoranceAI/hugh) 
It is a web application that allows you to do improv theatre with an ai actor. It records audio, transcribes it, and then reacts, as if on stage based in the transcription. The application uses the Whisper API, the ChatGPT API, and the ElevenLabs API.
`Riesenzwerg`is able to talk to you in many different languages such as English, German, Italian, and French.
Other languages are possible but not tested yet.

### Installation
0. `You need python.`

1. Clone this repository:
`git clone https://github.com/MrRettich/Riesenzwerg.git`

2. Install the Python packages:
`pip install -r requirements.txt`

3. Add your API keys to `.env`:    
`OPENAI_API_KEY = "YOUR API KEY HERE"`.   
`ELEVENLABS_API_KEY = "YOUR API KEY HERE"`

### Usage
1. Start the Flask server: `python app.py` or `flask run`
2. Open your web browser and navigate to the address given in the terminal. Most likely http://localhost:5000
3. Click the “Record” button to start recording audio. Speak into your microphone and then click the button again when you’re done. The transcription will appear in the text box.
4. Alternatively, type your question into the text box and click the “Ask” button to submit your question and generate a response.
5. The response will appear in the area below the audio player. It will begin playing and typing once it is ready.


### Credits
Record and Ask was created by Artificial Ignorance using Flask, OpenAI’s Whisper, OpenAI’s ChatGPT, and ElevenLabs. 
Most of the code is made by Charlie Guo (https://github.com/charlierguo)
Some of it by Caspar (https://github.com/MrRettich)

### License
This project is licensed under the MIT License - see the LICENSE file for details.
