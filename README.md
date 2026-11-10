# Chatbot UI template (HTML, CSS, JavaScript)

A free chatbot UI template in one file that really answers: header with avatar, chat bubbles, suggestion chips, typing dots and streaming replies. No backend, no build step.

**Live demo:** https://fengyiqicoder.github.io/chatbot-ui-template/
**Same template, restyled as a tutor:** https://fengyiqicoder.github.io/chatbot-ui-template/study-buddy.html

## Make it yours

Everything to change is marked in `index.html`:

1. **Colors**: `--brand` and `--brand-soft` in `:root`.
2. **Name, avatar, first message, suggestions**: the `header`, `#log` and `.chips` markup.
3. **What the bot does**: the `SYSTEM` line.

Then get a free key at [onetagai.com](https://onetagai.com) (1,000,000 tokens a month, no card) and put it in `data-key` on line 9.

The key in this repo is a public demo key with a small shared quota. Use your own on your site.
