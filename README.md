# tgbot_db_template

для использования Редис при объявлении диспатчера передайте в качестве storage:


storage = RedisStorage2(db=5)

bot = Bot(token=TOKEN)
dp = Dispatcher(bot, storage=storage)
