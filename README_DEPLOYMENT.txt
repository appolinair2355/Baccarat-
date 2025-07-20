# Telegram Card Counter Bot - Deployment Package

## Files included:
- simple_bot.py: Main Telegram bot
- simple_web.py: Web monitoring interface
- All supporting modules and templates

## Deployment Instructions for Render.com:

1. Upload this ZIP file to your render.com service
2. Set environment variable: TELEGRAM_BOT_TOKEN=your_bot_token
3. The bot will start automatically using the Procfile configuration

## Environment Variables Required:
- TELEGRAM_BOT_TOKEN: Your Telegram bot token from @BotFather

## Services:
- Bot Service: Runs the Telegram bot (simple_bot.py)
- Web Service: Monitoring dashboard on port 5000 (simple_web.py)

Generated on: 2025-07-20 19:35:55