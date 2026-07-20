# Skyrim Conky – Parchment Edition and Vanilla+ Edition
<img width="1920" height="1080" alt="Screenshot_20260719_220545" src="https://github.com/user-attachments/assets/00a65f56-e9b5-4b1b-8b24-400172ba965f" />
<img width="1920" height="1080" alt="Screenshot_20260716_150541" src="https://github.com/user-attachments/assets/1359d1bb-5e92-40e2-9abe-fe2138f59956" />
<img width="1920" height="1080" alt="Screenshot_20260716_150205" src="https://github.com/user-attachments/assets/4d5e1e5f-c5c2-4fa6-85d8-2fe70f29d5c1" />

Bring the look of **Skyrim** to your Linux desktop with a Vanilla Skyrim-style Conky theme inspired by the game's UI.

The theme displays useful system information in a lore-friendly design, including:

* CPU, RAM, storage, and network usage
* Weather and date
* Moon phases
* Dragon Word display
* Skyrim-inspired animations and icons

Everything is designed to blend naturally with Skyrim's interface while remaining lightweight and easy to use.

## Installation

1. Extract **dovakiinstatusv2.tar.gz**.
2. Put the files in ~/.config/conky folder.
3. Run

If you want local weather, edit:

```
~/.conky/skyrim_weather.sh
```
Enter your city or, for the U.S City+State. EX: Cincinnati+OH, New+York+NY, London. Use a + for spaces.

## Installation of Vanilla+

1. Extract **Skyrim-conky-vanilla+.tar.gz**.
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
Enter your city or, for the U.S City+State. EX: Cincinnati+OH, New+York+NY, London. Use a + for spaces.

Vanilla+ is almost completely compatible with the Parchment Edition. The only thing it is not compatible with is the parchment layout. 
I chose to do it this way to have 3 experiences: Skyrim modded feeling, a vanilla feeling, and a tinkering feeling.  

[Check the Parchment Edition here](https://github.com/bobbycomet/Skyrim-conky-parchment-)

Finally, start Conky and/or add it to your startup applications

Enjoy your new Skyrim-inspired desktop!
