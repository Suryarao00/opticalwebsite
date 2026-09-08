# Optical Website

AI-powered optical retail platform for Kazhcha Opticals with smart product recommendations, Kazhcha AI text chat, Live Voice shopping, virtual frame try-on, prescription assistance, customer accounts, cart, orders, appointments, admin analytics, and bilingual English/Malayalam support.

Main storefront file: `optical_website.html`

## Run locally

From `vision_backend`:

```bash
python -m uvicorn main:app --host 0.0.0.0 --port 8000
```

Then open:

```text
http://127.0.0.1:8000/store
```

Create `vision_backend/.env` locally for API keys and private configuration. Do not commit secrets.
