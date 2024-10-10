#  Speech Assistant with Twilio Voice and the OpenAI Realtime API (Python)

This is a fork of [Twilio](https://www.twilio.com)'s phone-enabled server tools and [OpenAI](https://www.openai.com)'s voice-to-voice features. It opens websockets with the OpenAI Realtime API and Twilio, sending voice audio from one to the other to enable a low-latency phone call with an AI voice agent. 

See [here](https://www.twilio.com/en-us/voice-ai-assistant-openai-realtime-api-python) from Twilio for a tutorial overview of the code.

Note that running this on a local server requires ngrok to tunnel to a local port (in the tutorials port 5050 is used) to serve as a node connecting to Twilio. A Twilio account and OpenAI API access are both required.