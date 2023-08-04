# Home Assistant Project with ChatGPT

This project aims to create a Home Assistant connected to ChatGPT, allowing users to interact with the system using a wake word ("Hey FlashMate"). The Home Assistant will be able to respond to a variety of user queries using natural language processing provided by the OpenAI ChatGPT model.

## Prerequisites

Before getting started, make sure you have the following elements:

- Raspberry Pi (preferably Raspberry Pi 4 or higher)
- USB microphone or a microphone module compatible with Raspberry Pi
- Speaker or an audio module compatible with Raspberry Pi
- Active Internet connection
- OpenAI account to access the ChatGPT API
- Python environment with necessary dependencies (listed in `requirements.txt`)

## TODO

- [ ] Generate a dataset using [howl](https://github.com/castorini/howl) for training the Wake Up Word system using the wake word "Hey FlashMate."
- [ ] Train the Wake Up Word Recognition model on the generated dataset.
- [ ] Integrate a Voice Activity Detection model to identify the end of the user's request.
- [ ] Add the Speech-to-text model to convert voice commands into text.
- [ ] Integrate the ChatGPT API to process text queries and obtain responses from ChatGPT.
- [ ] Set up the Text-to-speech model to read ChatGPT responses aloud.
- [ ] Test and debug the complete system.
- [ ] Improve error and exception handling.
- [ ] Provide comprehensive project documentation and update the README.
- [ ] Create an animated GIF or demonstration video for the README.


