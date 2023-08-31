# T2MAW_LLM

Talk To Me About Water LLM Pipeline

Currently we have 2 versions planned:

- online tool for interacting with our custom trained LLM to learn more about water.
- interactive immersive installation - realtime conversation with the LLM.

Our current demo uses touchdesigner and the OpenAI api to interact with Whisper to transcribe speech from a microphone, sends that transcription to chatgpt as a prompt, and types the response in text on screen or projection.

Next, we will be connecting the chatgpt response to text to speech and voice conversion tools to give a voice to the AI collaborator.

We plan to transition the software stack that we are using to open-source models to enable full control and ensure privacy with the proper hardware.

These include:

- whisper for speech transcription
- llama2 for text generation
- tortoise tts for generative text to speech
- rvc (retrieval based voice conversion) for refining tts output

We have begun development of the interactive installation for proof of concept. Once pipeline is solidified we will begin model training and development of public tool.

We are going with the flow ~~~

[talktomeaboutwater.com](https://talktomeaboutwater.com)
