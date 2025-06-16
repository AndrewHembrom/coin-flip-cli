# 🪙 Coinflip CLI

A fun and simple command-line tool that animates a coin flip with beautiful ASCII art — and lands on HEADS or TAILS randomly.

https://github.com/AndrewHembrom/coin-flip-cli

---

## 📦 Features

- Spinning coin animation using ASCII art
- Random result: HEADS or TAILS
- Lightweight and fast (pure Bash)
- Easy to install and use
- Works on most Unix-like systems (Linux, macOS, WSL)

---

## 🛠️ Installation

### Option 1: Install from `.deb` package

```bash
wget https://github.com/AndrewHembrom/coin-flip-cli/releases/download/v1.0/coin-flip-1.0.deb
sudo dpkg -i coin-flip-1.0.deb
```

### Option 2: Install from source

```bash
git clone https://github.com/AndrewHembrom/coinflip-cli.git
cd coin-flip-cli
chmod +x coin-flip
sudo cp coin-flip /usr/local/bin/
```

Now just run:

```bash
coinflip
```

## 📖 Usage
```bash
coinflip
```

Flags (coming soon):
- -h, --help — show usage help
- -q, --quiet — no animation, only result

## 📚 Man Page

After installing, you can access the manual:
```bash
man coinflip
```
(Nothing in there yet though right now.)

## 📂 Project Structure

```bash
coinflip-cli/
├── coinflip              # Main Bash script
├── README.md
├── man/
│   └── coinflip.1.gz     # Man page
├── deb/
│   └── coinflip-1.0.deb  # Pre-built Debian package
└── LICENSE
```

## 📝 License
This project is licensed under the [MIT License](LICENSE).

## 👤 Author
Andrew Hembrom
Built with 💛 and Bash in India 🇮🇳

## ⭐️ Show your support
If you like this project, please consider starring ⭐ the repository!
