# poultry-bot
Telegram bot for poultry farm monitoring and control
# 🐔 Poultry Farm Telegram Bot

A Telegram bot to monitor and control poultry farm conditions (temperature, humidity, ventilation) via SMS commands.

## Features
- ✅ Send SMS commands to farm equipment
- ✅ Auto-check system status every X minutes
- ✅ Set temperature, humidity, fan speed
- ✅ Persian UI (RTL support)
- ✅ Logging & alerts for equipment inconsistencies

## How it works
1. User sends command via Telegram menu
2. Bot sends `/sendsms +989011349879` + command to SMS gateway
3. Farm controller responds with sensor data
4. Bot parses and shows summary + alerts

## Files
- `bot.py` — Main bot logic
- `.gitignore` — Excludes logs and settings
- `settings.json` — Local config (not tracked)

## Requirements
- Python 3.8+
- `python-telegram-bot` library
- SMS gateway connected to phone number

## Setup
1. Install dependencies:  
   ```bash
   pip install python-telegram-bot
