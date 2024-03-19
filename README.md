# Blasterman

A classic blaster game made with and for [Gameeky](https://github.com/tchx84/gameeky).

## Hack it

```
cd ~/Gameeky
git clone https://github.com/tchx84/Blasterman.git
```

## Install it as a Flatpak extension

```
git clone https://github.com/tchx84/Blasterman.git
cd Blasterman
flatpak --user install org.gnome.{Platform,Sdk}//45
flatpak-builder --user --force-clean --install build packaging/dev.tchx84.Gameeky.ThematicPack.Blasterman.json
```

## Credits

The [actuators](actuators), [entities](entities) and [scenes](scenes) produced by [Gameeky](https://github.com/tchx84/gameeky) are released under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. These are distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](COPYING) for more details.

The [assets](assets) used in this project belong to opengameart.org are redistributed under the allowances and limitations of each individual license:

* [Bomb Party](https://opengameart.org/content/bomb-party-the-complete-set) by Matt Hackett, Cem Kalyoncu and devurandom. Redistributed under [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/).
* [NES Sounds](https://opengameart.org/content/nes-sounds) by Sebastian Riedel. Redistributed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
* [Retro](https://opengameart.org/content/retro) by Jensan. Redistributed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
