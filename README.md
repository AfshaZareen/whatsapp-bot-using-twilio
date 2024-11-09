# whatsapp-bot-using-twilio
A WhatsApp chatbot built with Twilio, Python, and Flask, designed to respond with random quotes or cat images based on user input.
For your GitHub repository description, you can use something like:

**"A WhatsApp chatbot built with Twilio, Python, and Flask, designed to respond with random quotes or cat images based on user input."**

### README.md Content

For your README file, here’s a sample structure you might use:

---

# WhatsApp Chatbot with Twilio and Python

## Overview
This project is a simple WhatsApp chatbot built using **Twilio**, **Python**, **Flask**, and **Ngrok**. It responds to specific keywords sent by users, providing either inspirational quotes or random cat images.

## Features
- **Quote Response:** Sends a random inspirational quote when the user types "quote".
- **Cat Image Response:** Returns a random cat image when the user types "cat".

## Getting Started

### Prerequisites
- Python 3.x
- Twilio account with WhatsApp sandbox setup
- Ngrok account

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/AfshaZareen/whatsapp-bot-using-twilio.git
   cd whatsapp-chatbot-twilio-python
   ```

2. Set up a virtual environment:
   ```bash
   python3 -m venv whatsapp-bot-venv
   source whatsapp-bot-venv/bin/activate  # For Windows: whatsapp-bot-venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install twilio flask requests
   ```

### Running the Chatbot
1. Start the Flask server:
   ```bash
   python bot.py
   ```

2. In a new terminal, run Ngrok to expose the local server:
   ```bash
   ngrok http 4000
   ```

3. Copy the Ngrok URL to Twilio's **"When a message comes in"** field in the WhatsApp sandbox settings, appending `/bot`.

4. Test the bot by sending "quote" or "cat" from your connected WhatsApp number.

---

