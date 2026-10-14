# mathcode-uptime

Verifica `https://mathcode.com.br/`, `/links` e `/api/health` a cada 10 minutos. Se algum falhar duas vezes seguidas, abre uma issue com o rótulo `incidente` e avisa no Telegram; quando volta, fecha a issue e avisa de novo. Segredos: `TELEGRAM_BOT_TOKEN`, `TELEGRAM_CHAT_ID`.
