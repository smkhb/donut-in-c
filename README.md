# 🍩 donut.c

A spinning 3D donut — in pure C, rendered with ASCII characters in your terminal. ✨

## 🚀 Build & Run

```bash
gcc index.c -o donut -lm
./donut
```

## 🎥 What you'll see

...but spinning. Forever. 🔁

## 🧠 How it works

- 🧮 A torus of points is rotated with trig functions (`sin`/`cos`)
- 📽️ Projected onto an 80×22 terminal grid with depth-buffering
- 🔤 Shaded using ASCII characters: `.,-~:;=!*#$@`

## 📦 Requirements

- A C compiler (gcc/clang) 🛠️
- A terminal — that's it! 💁

Based on the famous [donut math](https://www.a1k0n.net/2011/07/20/donut-math.html) by a1k0n. 🙏
