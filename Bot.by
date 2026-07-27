import os
import json
from telegram import Bot

TOKEN = os.getenv("BOT_TOKEN")

bot = Bot(token=TOKEN)

with open("hadiths.json", "r", encoding="utf-8") as f:
    hadiths = json.load(f)

print(f"تعداد احادیث: {len(hadiths)}")
