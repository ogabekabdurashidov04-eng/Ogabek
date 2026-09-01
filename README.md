# Ogabek
Oahhdhbdbebsh
import os
import asyncio
from aiogram import Bot, Dispatcher
from aiogram.filters import CommandStart

TOKEN = os.getenv(8911604514:AAFoO_MPqWNLZUmhjaeJpHnVhjmdE8Ydz9c)

bot = Bot(8911604514:AAFoO_MPqWNLZUmhjaeJpHnVhjmdE8Ydz9c)
dp = Dispatcher()

@dp.message(CommandStart())
async def start(message):
    await message.answer("✅ Bot ishlayapti!")

async def main():
    await dp.start_polling(bot)

asyncio.run(main())
