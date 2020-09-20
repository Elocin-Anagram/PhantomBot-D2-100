PhantomBot-D20
A simple D20 dice command for PhantomBot Created by and for Epic Duck Studios Edited by Elocin_Anagram to include other dice (d2 d4 d6 d8 d10 d12 d100)

Installation
The folder structure of this repo matches that used by PhantomBot. You just need to copy the following two files to their same-pathed location (or clone this repo directly into your PhantomBot folder).

scripts/games/d20.js
lang/english/games/games-d20.js
If you're using a language other than English, you'll need to create a suitable lang file yourself. It's only 3 lines, so the translation should be pretty trivial :)

After copying the files, you'll need to restart PhantomBot.

Usage
Channel visitors can roll a Dice by simply entering the commands !d2 !d4 !d6 !d8 !d10 !d12 !d20 or !d100. The most recent dice roll can be retrieved with !d2 last !d4 last !d6 last !d8 last last !d10 last !d12 last !d20 last or !d100 last.
