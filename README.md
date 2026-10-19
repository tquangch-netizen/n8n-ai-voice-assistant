# n8n-ai-voice-assistant
My AI Voice Assistant powered by n8n

# AI Voice Assistant using n8n

An AI voice assistant built using n8n and OpenAI.

## Live Demo

[Try the AI Voice Assistant](https://tquangch-netizen.github.io/n8n-ai-voice-assistant/)

## How It Works

1. User speaks through a microphone.
2. Browser converts speech into text.
3. n8n receives the question through a webhook.
4. AI Agent processes the question.
5. OpenAI converts the response into speech.
6. The browser plays the AI-generated voice.

## n8n Workflow

[Download n8n Workflow JSON](./AI-Voice-Assistant-Workflow.json)

## Technologies Used

- n8n
- OpenAI GPT-4o-mini
- OpenAI Text-to-Speech
- JavaScript and HTML
- GitHub Pages

## How to Run

1. Download the workflow JSON file.
2. Import it into n8n.
3. Configure your own OpenAI API credentials.
4. Update the webhook URL in index.html.
5. Publish the workflow.
6. Open the voice assistant webpage and test it.
