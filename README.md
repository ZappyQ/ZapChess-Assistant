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
```

## 🚦 How to Use (User Guide)

1.  **Setup Files**: Ensure `stockfish.exe` and `chromedriver.exe` are located in the same directory as the executable.
2.  **Launch the App**: Run `ZapChess.exe` in your terminal or simply open `ZapChess.exe`.
3.  **Configuration**:
    * In the ZapChess GUI, select your side (**White** or **Black**).
    * Set your desired **Target ELO** (e.g., 2500) and **Depth** (e.g., 14).
4.  **Activation**: Click the **START ENGINE** button. The analysis log will confirm: `Browser ready. New Stockfish engine started!`.
5.  **Browser Setup**: A Chrome window will open automatically. Log in to your Chess.com account and navigate to a live game.
6.  **Real-Time Analysis**: As you or your opponent move on Chess.com, the ZapChess board will sync instantly. Follow the colored neon highlights for the best suggested moves.

---

## ⚠️ Disclaimer

This tool is intended for **educational purposes and post-game analysis only**. Using chess assistants during live matchmaking against other players is a strict violation of Chess.com's Terms of Service and will result in a permanent account ban. **Use responsibly.**
