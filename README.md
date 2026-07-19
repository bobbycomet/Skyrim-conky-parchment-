# Skyrim Conky – Rustic Parchment Edition

<img width="1920" height="1080" alt="Screenshot_20260718_192950" src="https://github.com/user-attachments/assets/84629a1a-b450-458d-b879-1722ec85a78e" />

Bring the look of **Skyrim** to your Linux desktop with a parchment-style Conky theme inspired by the game's journal.

The theme displays useful system information in a lore-friendly design, including:

* CPU, RAM, storage, and network usage (bars drain as usage gets higher)
* Weather and date
* Moon phases
* Dragon Word display
* Skyrim-inspired animations and icons

Everything is designed to blend naturally with Skyrim's interface while remaining lightweight and easy to use.

## Installation

1. Extract **Skyrim-conky-parchment.tar.gz**.
2. Put the files in ~/.config/conky folder.
3. Run:

```bash
./install.sh
```

The installer will:

* Copy the theme to the correct location.
* Install the required fonts.
* Create a weather configuration file.

If you want local weather, edit:

```text
~/.conky/location.conf
```

Enter your city, or leave it blank to let the theme detect your location automatically.

Finally, start Conky and/or add it to startup applications.

Enjoy your new Skyrim-inspired desktop!
