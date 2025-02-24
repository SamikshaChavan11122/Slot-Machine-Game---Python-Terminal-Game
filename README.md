## 🎰 Slot Machine Game - Python Terminal Game

### 📜 Description

This is a simple **slot machine game** that runs in the **Python terminal**. The game allows players to:

- **Deposit money** before playing.
- **Choose the number of lines** they want to bet on.
- **Set their bet amount** within the allowed limits.
- **Spin the slot machine** and try to win based on randomly generated symbols.
- **Continue playing until they decide to quit or run out of balance.**

The game includes:

- Randomized slot results.
- Different symbol values.
- Winning line detection.
- User-friendly inputs with validation.

---

## 📖 How to Play

1. **Run the script** using Python:
   ```bash
   python slot_machine.py
   ```
2. **Deposit money** when prompted.
3. **Choose the number of lines** to bet on (1-3).
4. **Enter your bet amount** (between $1 and $100).
5. **Spin the machine** and check if you win.
6. Repeat **until you decide to quit** or run out of balance.

---

## 🔧 Features

✅ Simple console-based game  
✅ Randomized slot machine outcomes  
✅ Winning line detection  
✅ Balance management  
✅ Safe input handling

---

## 🏆 Winning Criteria

- Symbols appear in **rows**, and if all columns in a row match, you win!
- Each symbol has a different value:
  - **"A" → 5x bet**
  - **"B" → 4x bet**
  - **"C" → 3x bet**
  - **"D" → 2x bet**

Example Output:

```
Current balance: $100
Press enter to play (q to quit):
You are betting $10 on 2 lines. Total bet: $20
A | B | C
B | B | B  <- (Winning Line!)
D | C | A
You won $40
You won on lines: 2
```

---

## 🚀 Future Improvements

- Add **animation effects** using ASCII art.
- Allow **multi-symbol winnings**.
- Introduce **bonuses** and **jackpots**.

---

This game is a fun way to learn **Python, loops, functions, and randomness** while enjoying a simple gambling simulation! 🎰💰
