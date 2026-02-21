# ⚡ Gace AI

**Write a function. Ship an AI plugin.**

Welcome to the Gace AI GitHub organization. We're building the fastest, most frictionless way for developers to give AI models real-world capabilities.

Without plugins, AI is just a text box. With Gace, you can write a single TypeScript function and turn it into a universal AI tool—instantly accessible, zero configuration required.

---

### 🚀 Our Vision

We believe building AI tools shouldn't require managing infrastructure, wrestling with complex JSON schemas, or handling boilerplate auth. If you can write a function, you can ship an AI plugin.

Our ecosystem is designed around a radically simplified developer experience:

* **Zero Boilerplate:** One `@Tool` decorator and you're done.
* **Instant Dev Environments:** Run `npm run dev` and get a live, hot-reloading remote URL instantly. No Docker, no ngrok, no API keys.
* **One-Click Distribution:** Deploy directly to the Gace Marketplace where any user can install your capability with a single click.

---

### 🛠️ The Gace SDK

We provide a comprehensive, built-in SDK so you can focus strictly on your plugin's logic. Everything you need is injected right into your function:

* 🌐 **`sdk.http`**: Make requests to external APIs with ease.
* 💾 **`sdk.storage`**: Built-in, persistent key-value storage scoped per user. No database setup required.
* 🎨 **`sdk.ui`**: Return React components from your backend to render interactive, rich UIs inside chatbot conversations.
* 🧠 **`sdk.ai`**: Call LLMs directly from your plugin without bringing your own API keys.
* 💻 **`sdk.computer`**: (With permission) interact with the desktop filesystem, clipboard, and system info.

---

### ⚖️ Why Gace? (vs. MCP)

If you've played with the Model Context Protocol (MCP), you know the pain of self-hosting, manual configurations, and sharing localhost URLs. We built Gace to be the fully managed, zero-config alternative. We handle the hosting, the auth, and the marketplace distribution—**free for developers, forever.**

---

### 🌍 Join the Beta

We're currently in Public Beta, rapidly expanding our capabilities and unlocking new ways for LLMs to interact with the world.

* **Website:** [gace.dev](https://gace.dev)
* **Docs:** [gace.dev/docs](https://gace.dev/docs) (Coming soon)
