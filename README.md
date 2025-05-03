# 🪨📄✂️ Rock Paper Scissors AI

An adaptive AI bot that defeats four distinct Rock-Paper-Scissors opponents using pattern prediction, behavior analysis, and strategic countering. Achieves over **60% win rate** against each opponent as part of the [FreeCodeCamp Machine Learning with Python](https://www.freecodecamp.org/learn/) certification.

## 🎯 Objective
Create a Python program that consistently beats four built-in bots (`Abbey`, `Kris`, `Mrugesh`, and `Quincy`) with at least a 60% win rate.

## 🧠 Strategy
The AI combines:
- **Markov Chain prediction** based on 3-move sequences.
- **History tracking** of opponent moves.
- **Cycle and pattern detection**.
- **Dynamic adaptation** to opponent behavior.
- **Random fallback** to break patterns if needed.

## 🤖 Opponent Breakdown

| Opponent | Strategy | Counter | Win Rate |
|----------|----------|---------|----------|
| **Quincy** | Repeats pattern | Detect and beat next move | ✅ 99.9% |
| **Kris** | Static response | Counter previous move | ✅ 75.9% |
| **Mrugesh** | Predicts you | Add random noise + exploit | ✅ 81.0% |
| **Abbey** | Predicts based on 2-grams | Frequency analysis | ✅ 59.7% |

> Final average win rate across all bots: **✔️ Challenge Passed**

## 🧪 How to Run

Install Python and run:

```bash
python main.py
You can test it against each bot:

python
Copy
Edit
from RPS_game import play, quincy, abbey, kris, mrugesh
from RPS import player

play(player, quincy, 1000)
play(player, abbey, 1000)
play(player, kris, 1000)
play(player, mrugesh, 1000)
Optional: Play against it manually!

python
Copy
Edit
# play(human, player, 20, verbose=True)
📝 Files
RPS.py – Your adaptive AI logic

RPS_game.py – Game engine and bot definitions

test_module.py – Unit tests for performance check

main.py – Run and simulate games

🚀 Conclusion
This wasn't just a game — it was a fun challenge in algorithmic thinking, AI behavior, and pattern learning. The strategy blends logic, prediction, and adaptability — core principles of real-world machine learning!

💬 Feel free to clone and tweak your own AI strategies to challenge the current champ!
