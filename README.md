# Lichess-STB

An optimized, lightweight lichess.org client designed for Infomir Set-top boxes.

### How to install

Download the release on https://github.com/yess44909/Lichess-STB/releases/tag/v0.3

You have to use an webserver. For beginners, I recommend using [Apache Friends XAMPP](https://www.apachefriends.org/) if you have no experience with webservers.

You will absolutely **need** to create an Lichess API key before playing! Create yours at https://lichess.org/account/oauth/token

On ../lichess/api/config.php, change $token = "undefined"; by your API key which starts with lip_...

You can also configure which theme you want with config.php

Copy the whole lichess folder into your environnement, like as example "C:\xampp\htdocs\lichess"

After that, wake up Apache.

On your STB, go to System settings > Servers > Portals, then change any portal by your local IP.
example: http://192.168.X.XX/lichess/index.html

After that, launch the portal and you'll see the interface.


## Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c1545452-94a0-4790-b1eb-f48343124d40" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1d32c8fc-496e-4f03-89b3-27e106e03225" />

### Notice

Lichess-STB is in **beta**. It's not stable.

Please open an issue directly on the repository issues page

## Pros

Playable lichess.org matches

Faithful in-game experience

Move sidebar

Quick playing

Challenging your friends

Creating bot matches

Cursor box to help navigation

Viewing tournament list

SFX/audio played through the STB Player

## Cons

Bullet,UltraBullet matches are not playable due to the Lichess Board API prohibits utilization for fair play

Kinda buggy

Some lower resolutions may look odd or scuffed

No analysis

Tournaments are not joinable

Most complex variants have unexpected behavior

Correspendence matches make a in-game continous loop, so make sure to not have alot of ongoing matches

## Todos

Better chessboard maintenance

More menus

More variant support

Chatting

ChessTV (you get it)

Enchanced resolution compability

Spectating your friends

Viewing your profile user in-menu

Viewing your ELO in-game

Adding background themes

## Compability

All builds are tested on my MAG254. Lichess-STB is compatible with MAG200 - MAG544w3

Android Set-top boxes are supported.
You'll need a STB Emulator such as StbEmu (from Play Store)

## Currently mapped keys

BACK = Exit in-game
HOME = Exit the application
F1 = Resign (automatically)
F2 = Draw (status won't update)
