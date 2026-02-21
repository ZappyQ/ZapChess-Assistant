# ♟️ Zap Chess Assistant

**Zap Chess Assistant** is a high-performance, real-time chess analysis tool. It bridges the gap between your web browser and the world-class Stockfish engine, providing a sleek, neon-themed dashboard to monitor your games, evaluation scores, and best move possibilities.

> **Created by ZappyQ**

---

## 🚀 Key Features

* **Live Game Sync:** Automatically extracts the board state (FEN) from Chess.com using Selenium.
* **Stockfish Integration:** Powered by the industry-standard Stockfish engine for top-tier analysis.
* **Dynamic HUD:** A modern CustomTkinter interface showing:
    * **Stockfish Eval:** Real-time centipawn or mate evaluation.
    * **Win Chance:** Percentage-based win probability.
    * **Multi-PV Analysis:** Displays the top 3 best move paths directly on the visual board.
* **Customizable Strength:** Adjust **Target ELO** (100 to 3200+) and **Calculation Depth** on the fly.
* **Neon Visuals:** High-contrast board rendering with move highlights (Blue/Pink/Yellow for top lines).

---

## 🛠️ Requirements

### For Developers (Running from Source)
* **Python 3.10+**
* **Required Libraries:** ```pip install python-chess selenium customtkinter pillow```
### Essential Binaries (Must be in the root folder)
* `stockfish.exe` (The Stockfish engine binary)
* `chromedriver.exe` (Matching your installed Chrome browser version)

---

## 📂 Project Structure

```text
.
├── ZapChess.exe         # Main application script
├── stockfish.exe        # Stockfish engine binary
├── chromedriver.exe     # Chrome WebDriver
└── chrome_profile_gui/  # (Auto-generated) Local browser session data
