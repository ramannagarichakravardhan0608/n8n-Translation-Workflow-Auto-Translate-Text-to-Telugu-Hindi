n8n Translation Workflow – Telugu & Hindi Translator
📌 Overview

This n8n workflow automatically translates any text received through a webhook into Telugu and Hindi using an AI Agent connected to Google Gemini.

🚀 Features

Accepts text through a Webhook (POST)

Uses AI Agent + Google Gemini for translation

Returns clean, structured translations

Simple and fully automated

🛠️ Workflow Structure
Nodes inside this workflow

Webhook
Receives the input text from body.input.

AI Agent
Processes the input and translates it into Telugu and Hindi based on the system message.

Google Gemini Chat Model
Provides the language model used by the AI Agent.
📥 Input Example

Send a POST request:
{
  "input": "Hello, how are you?"
}
📤 Output Example
Telugu Translation:
<Translated Telugu text>

Hindi Translation:
<Translated Hindi text>
🔧 How to Use

Import the JSON workflow into n8n.

Activate the workflow.

Copy the generated webhook URL.

Send a POST request with your text.

Receive Telugu + Hindi translations instantly.
