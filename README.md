# 🕹️ PingPong – C++ / Raylib

A clean, high-performance Pong clone written in C++ using Raylib. Features:

- HD gameplay with smooth animations 🎯  
- Dynamic ball speed increasing with score  
- Smart CPU paddle for engaging combat  

---

## 🎮 Gameplay Demo

https://github.com/user-attachments/assets/040a981a-cb57-48d4-a8f2-0354fce21bb4

---

## 🚀 Setup & Build

1. Install Raylib:
   ```bash
   # Ubuntu
   sudo apt install libraylib-dev
   ```

2. Clone & build:
   ```bash
   git clone https://github.com/dakshjain2005/PingPong.git
   cd PingPong
   mkdir build && cd build
   cmake ..
   make
   ```

3. Run the game:
   ```bash
   ./PingPong
   ```

Alternatively, compile directly:
```bash
g++ src/main.cpp -o PingPong -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./PingPong
```

---

## 🧩 Project Structure

- `assets/` — media files (video, images)  
- `src/` — source code  
- `README.md` — project overview & usage

---

## ✅ Contributing

Feel free to fork, open issues, or submit PRs for:

- Sound or visual effects  
- Enhanced AI difficulty modes  
- Gamepad or multiplayer support  
- Animations, menus, score streaks

---

## 🧠 Developer Notes

Keep `main.cpp` clean and modular:

```cpp
#include <raylib.h>
// ... your full code here ...
```

---

> “PingPong is a fast-paced, responsive Pong game – smooth physics, evolving difficulty, and smart CPU make it addictive and fun!”

---

## 📄 License

MIT License © 2025 Daksh Jain
