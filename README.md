# Telegram Redirect (Vercel)

Link formats (दोनों चलते हैं):
- https://YOUR.vercel.app/BotUsername/PAYLOAD
- https://YOUR.vercel.app/?bot=BotUsername&start=PAYLOAD
- https://YOUR.vercel.app/PAYLOAD  (अगर index.html में DEFAULT_BOT सेट है)

Deploy: GitHub में push -> Vercel -> Add New Project -> repo चुनें -> Framework "Other" -> Deploy.
Settings: index.html के ऊपर CONFIG ब्लॉक में।
