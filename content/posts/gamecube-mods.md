+++
title = "Modding my Gamecube"
date = "2025-09-18"
+++

I recently picked up an original GameCube so that I could replay some fantastic games in my collection. My favorites are probably [Super Smash Bros. Melee](https://en.wikipedia.org/wiki/Super_Smash_Bros._Melee), [The Legend of Zelda: The Wind Waker](https://en.wikipedia.org/wiki/The_Legend_of_Zelda:_The_Wind_Waker), [The Legend of Zelda: Twilight Princess](https://en.wikipedia.org/wiki/The_Legend_of_Zelda:_Twilight_Princess), [Mario Kart: Double Dash](https://en.wikipedia.org/wiki/Mario_Kart:_Double_Dash), and of course [Super Monkey Ball 2](https://en.wikipedia.org/wiki/Super_Monkey_Ball_2). I even had my original memory card so I could see my progress on my Zelda saves.

The GameCube is still a very capable console that holds up to this day, but it does show its age. Modern TVs really show how small the 480p resolution was. Living rooms have gotten bigger, making the original controller cable way to short and inconvenient to use comfortably. And maybe I've gotten lazier because I am less inclined to put a physical disk (carefully) into the console when I want to play a game. Luckily, I've found a couple of mods that don't require soldering and don't change the original appearance.

# GameCube Blue Retro
[https://www.laserbear.net/products/gamecube-blue-retro-internal-adapter](https://www.laserbear.net/products/gamecube-blue-retro-internal-adapter)

[https://www.laserbear.net/blogs/docs/gamecube-blue-retro-user-guide](https://www.laserbear.net/blogs/docs/gamecube-blue-retro-user-guide)

This replaces the controller port panel to allow connecting modern bluetooth controllers while still allowing original GameCube controllers to be plugged in. It supports Switch 2 GameCube controllers, but that requires installing [this beta build](https://github.com/darthcloud/BlueRetro/discussions/1261#discussioncomment-14201799).

One complaint I have is that the panel replaces the reset button which now has a distinct click rather than a linear button like in the original. Oh well, it's not like I pressed that button often anyway.

# FlippyDrive
[https://www.crowdsupply.com/team-offbroadway/flippydrive](https://www.crowdsupply.com/team-offbroadway/flippydrive)

[https://docs.flippydrive.com/](https://docs.flippydrive.com/)

This is a small chip that hijacks the data bus from the optical disk drive. Importantly, the optical drive can still function as normal. The chip has a port for a micro SD card to store ROMs that can be sent down the data bus. I haven't taken any measurements, but I've noticed loading times for Smash Bros have significantly improved. There is a mode to read an optical disk and write to the SD card. Several hours later, I had playable backups of my GameCube library, accessible from my couch.

# Usage
* To enter pairing mode, hold the reset button for 7-9 seconds and the four LEDs should blink quickly.
* On a Switch 2 GameCube controller...
  * System reset: L + R + Start + B
  * Sleep mode: L + R + Start + A
    * While in sleep mode, turn on the controller to turn on the console.
  * During boot, hold Left on the control pad to boot the GameCube normally with no mods.
  * During boot, hold X to enter the Bootloader menu.