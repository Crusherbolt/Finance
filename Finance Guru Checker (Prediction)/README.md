# 🎥 YouTube Guru Analyzer 📊

[![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Analyze **finance guru predictions** from YouTube videos, extract their stock/market calls with **Google Gemini AI**, and measure accuracy against **real market data** using Yahoo Finance.

---

## ✨ Features

✅ Extracts **guru name** + **background**  
✅ Identifies predictions:
- 📈 Stock picks & price targets  
- 🏦 Macro forecasts (interest rates, recessions)  
- 📊 Index/sector calls  
- ⚡ Event-driven forecasts (earnings, policies)  

✅ Auto-fetches **historical prices** from Yahoo Finance  
✅ Displays **metrics & performance vs. prediction**  
✅ Interactive charts with **Altair**  
✅ Built with **Streamlit** → easy & fast UI  

---

## 🖼️ Demo Screenshot

<p align="center">
  <img width="1873" height="881" alt="image" src="https://github.com/user-attachments/assets/f05fa581-926a-441d-a8cc-ae88c209bf54" />
</p>

---

## 🛠️ Tech Stack

- 🎨 [Streamlit](https://streamlit.io/) – interactive app  
- 🤖 [Google Gemini AI](https://ai.google.dev/) – extracting structured predictions  
- 🎥 [yt-dlp](https://github.com/yt-dlp/yt-dlp) – YouTube video metadata  
- 💹 [yfinance](https://github.com/ranaroussi/yfinance) – stock history  
- 📊 [Altair](https://altair-viz.github.io/) – charts  
- 🧩 [Pydantic](https://docs.pydantic.dev/) – structured parsing  
- 🔐 [python-dotenv](https://pypi.org/project/python-dotenv/) – secrets  

---

## ⚙️ Installation

Clone this repo and set up dependencies:

```bash
git clone https://github.com/your-username/youtube-guru-analyzer.git
cd youtube-guru-analyzer

# Create virtual environment
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
```
---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit a PR.  

1. 🍴 Fork the project  
2. 🌱 Create your feature branch (`git checkout -b feature/AmazingFeature`)  
3. 💾 Commit your changes (`git commit -m 'Add AmazingFeature'`)  
4. 🚀 Push to the branch (`git push origin feature/AmazingFeature`)  
5. 🔁 Open a Pull Request  

---

## 🙌 Acknowledgements

- 🎥 [yt-dlp](https://github.com/yt-dlp/yt-dlp) for YouTube scraping  
- 💹 [yfinance](https://github.com/ranaroussi/yfinance) for stock data  
- 🎨 [Streamlit](https://streamlit.io/) for the UI framework  
- 🤖 [Google Gemini AI](https://ai.google.dev/) for predictions parsing  

---

