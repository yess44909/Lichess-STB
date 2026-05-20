# Lichess-STB

An optimized, lightweight lichess.org client designed for Infomir Set-top boxes.

### How to install

Download the release on https://github.com/yess44909/Lichess-STB/releases/tag/v0.1

You have to use an webserver. For beginners, I recommend using XAMPP if you're on Windows.

You will absolutely **need** to create an Lichess API key before playing! Create yours at https://lichess.org/account/oauth/token

On ../lichess/api/config.php, change $token = "undefined"; by your API key which starts with LIP_...

_This is designed to run on Apache and PHP._

Copy the whole lichess folder into your environnement, like as example "C:\xampp\htdocs\lichess"

After that, wake up Apache.

On your STB, go to System settings > Servers > Portals, then change any portal by your local IP.
example: http://192.168.X.XX/lichess/index.html

After that, launch the portal and you'll see the interface.

### Notice

Lichess-STB is heavily in **alpha**. Some features may break.

Please open an issue directly on the repository issues page

## Todo list

Fix chessboard bug when playing variants

Interaction with in-menu right sidebar

Better menu interface

Add chatting

## Supported models

All builds are tested on MAG254. Lichess-STB is compatible with MAG200 - MAG544w3
