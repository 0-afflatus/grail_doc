Sub game for the Minetest game engine [grail_test]
==========================================================

Documentation
-------------

To use this game with Minetest, insert https://github.com/0-afflatus/grail_test as
  /games/grail_test
in the Minetest Engine.

The Minetest Engine can be found in:
  https://github.com/minetest/minetest/

Compatibility
--------------
The grail_test github master HEAD is generally compatible with the latest stable version of minetest.

This version was developed on minetest 0.4.10.

Compatible mods:
---------------
Mobs Redo [<= 0.7] by tenplus1, based on PilzAdam's Simple Mobs is known to work, albeit with limited support. https://github.com/tenplus1/mobs

Mods designed for other games will probably break.

Purpose
-------

Find the Grail.

Gameplay
--------

"The theme of the Grail is the bringing of life into what is known as the wasteland." ~ Joseph Campbell. 

"You can't expect to wield supreme executive power just because some watery tart threw a sword at you." ~ Dennis, Monty Python and the Holy Grail.

"None of them had any idea where the Holy Grail really was, and I don't think any of them actually expected to find it, or would have known what to do with it if he had run across it." ~ Mark Twain, A Connecticut Yankee in King Arthur's Court.

"That rabbit's got a vicious streak a mile wide!" ~ Tim the Enchanter, Monty Python and the Holy Grail.

"But choose wisely, for while the true Grail will bring you life, the false Grail will take it from you." ~ Grail Knight, Indiana Jones and the Last Crusade.

"It begins with the king as a boy, having to spend the night alone in the forest to prove his courage so he can become king. Now while he is spending the night alone he's visited by a sacred vision. Out of the fire appears the Holy Grail, symbol of God's divine grace. And a voice said to the boy, 'You shall be keeper of the grail so that it may heal the hearts of men.' But the boy was blinded by greater visions of a life filled with power and glory and beauty. And in this state of radical amazement he felt for a brief moment not like a boy, but invincible, like God, so he reached into the fire to take the grail, and the grail vanished, leaving him with his hand in the fire to be terribly wounded. Now as this boy grew older, his wound grew deeper. Until one day, life for him lost its reason. He had no faith in any man, not even himself. He couldn't love or feel loved. He was sick with experience. He began to die. One day a fool wandered into the castle and found the king alone. And being a fool, he was simple minded, he didn't see a king. He only saw a man alone and in pain. And he asked the king, 'What ails you friend?' The king replied, 'I'm thirsty. I need some water to cool my throat'. So the fool took a cup from beside his bed, filled it with water and handed it to the king. As the king began to drink, he realized his wound was healed. He looked in his hands and there was the holy grail, that which he sought all of his life. And he turned to the fool and said with amazement, 'How can you find that which my brightest and bravest could not?' And the fool replied, 'I don't know. I only knew that you were thirsty.' It's very beautiful, isn't it?" ~ Parry, The Fisher King.

"Follow your bliss." ~ Joseph Campbell.

Development
-----------

Development of grail_test is intended to roughly follow evolution. It features a stripped-down core, which only really provides the raw elements and a bit of legacy support. Game Universe specific features have been stripped out into minerals, materials, food, tools and equipment mods. These have been re-introduced in sequence in order to get the chain of dependencies right. The projected game will provide legacy support for farming and moreores.

One of the aims of the game is increased magical pseudo-realism; that is, things like crafting recipes should be logical and believable given the fantastic nature of the game-world.

License of source code
----------------------
Copyright (C) 2014 afflatus, Tim Hall <afflatus@pathilorra.co.uk>

Based on minetest_game:
Copyright (C) 2010-2012 celeron55, Perttu Ahola <celeron55@gmail.com>
See README.txt in each mod directory for information about other authors.

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation; either version 2.1 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

License of media (textures and sounds)
--------------------------------------
menu/background.png and menu/icon.png
Copyright (C) 2014 afflatus, Tim Hall <afflatus@pathilorra.co.uk>

Based on original minetest_game media:
Copyright (C) 2010-2012 celeron55, Perttu Ahola <celeron55@gmail.com>
See README.txt in each mod directory for information about other authors.

Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)
http://creativecommons.org/licenses/by-sa/3.0/
