# 🌦️ Weather Agent with OpenWeather API (Async Python)

This project is a simple weather assistant powered by an agent that responds to user queries about city weather. It uses the `weatherapi.com` API to fetch real-time weather data and formats responses based on user input.

## 🚀 Features

- Asynchronous agent using a tool to fetch weather
- Fetches current weather for any city
- Provides a natural-language response
- Rejects unrelated (non-weather) queries
- Designed to work in notebooks (via `nest_asyncio`)

---

## 🧱 Tech Stack

- Python 3.11+
- `asyncio` & `nest_asyncio`
- `requests` (for API calls)
- Custom agent framework with tool calling

---

## 📦 Requirements

Install the required Python packages:

```bash
pip install requests nest_asyncio typing_extensions
