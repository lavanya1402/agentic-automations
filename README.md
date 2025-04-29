# Inventory AI Agent (n8n + Google Sheets)

This n8n workflow connects to a Google Sheet and responds to inventory questions like:
> "How many packs of grapes are in stock?"

✅ Features:
- Natural language understanding via OpenAI
- Extracts item names, quantities, and units
- Responds through chat (e.g., WhatsApp, Telegram, email)

## How to Use
1. Import the `.json` workflow into your n8n instance
2. Set up Google Sheets and OpenAI credentials
3. Connect to your preferred messaging service (e.g., WhatsApp via Twilio)
