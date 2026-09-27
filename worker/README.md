# matchmybot-chat (Cloudflare Worker)

Backup copy of the code that runs the "Ask the matchmaker" chat on matchmybot.com.

- **Live copy:** Cloudflare dashboard → Workers & Pages → `matchmybot-chat`
  (https://matchmybot-chat.denise-rena-frank.workers.dev/)
- **Editing this file does NOT change the live chat.** Make the change in Cloudflare
  (Edit code → Deploy), then update this copy to match.
- The Anthropic API key is stored in Cloudflare as `ANTHROPIC_API_KEY` and is never in this code.
  API account: https://platform.claude.com/dashboard
