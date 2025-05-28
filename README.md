# Nova - Cyberpunk AI Chatbot

Nova is a glitchcore cyberpunk AI chatbot built with Flask and Groq’s LLM API. Inspired by the neon-lit worlds of *Neuromancer* and *Cyberpunk 2077*, Nova delivers snappy, edgy, and tech-laced responses in a visually immersive web UI.

**Version:** `Nova.vX1.9.4.r5`

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, Tailwind CSS, custom CSS (cyberpunk theme)
- **AI Model:** Groq Llama 3 API
- **Other:** JavaScript (vanilla, for chat logic)

## Features

- **Cyberpunk UI:** Neon grid, glitch effects, and immersive styling.
- **LLM-powered:** Uses Groq’s Llama 3 model for chat responses.
- **Custom Persona:** Nova speaks in a unique, cyberpunk-inspired voice and knows her name/version (`Nova.vX1.9.4.r5`) and creator (`Alan Cyril Sunny`).
- **Responsive Design:** Works on desktop and mobile.

## Quickstart

1. **Clone the repo and install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

2. **Set your Groq API key:**
    - Copy `.env.example` to `.env` and add your `GROQ_API_KEY`, or edit `.env` directly.

3. **Run the app:**
    ```sh
    python app.py
    ```
    The app will be available at [http://localhost:5000](http://localhost:5000).

## Project Structure

```
nova-chatbot/
  app.py
  requirements.txt
  .env
  static/
    style.css
  templates/
    index.html
```

- [`app.py`](nova-chatbot/app.py): Flask backend, handles chat and LLM API.
- [`templates/index.html`](nova-chatbot/templates/index.html): Main UI, cyberpunk-styled.
- [`static/style.css`](nova-chatbot/static/style.css): Custom CSS for neon/glitch effects.

## Customization

- **Persona:** Edit the `system_prompt` in [`app.py`](nova-chatbot/app.py) to change Nova’s style.
- **UI:** Tweak CSS in [`static/style.css`](nova-chatbot/static/style.css) or HTML in [`templates/index.html`](nova-chatbot/templates/index.html).

## Credits

- **Developed by:** Alan Cyril Sunny
- **LLM API:** [Groq](https://groq.com/)
- **UI Inspiration:** Cyberpunk 2077, Neuromancer

---

© 2077 Nova Systems