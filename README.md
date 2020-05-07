## Ghost

Play the road-trip game, [ghost](<https://en.wikipedia.org/wiki/Ghost_(game)>), in ruby!

The game can be played with more than two players

Start the game by setting the number of players

```ruby
game = Ghostgame(Player.new('Mike'), Player.new('Gizmo'), Player.new('breakfast'))
```

Once you have set the players, the game will begin once you enter `game.run` (or whatever you decide to call the game)

---

The game uses a file with over 35k words and references it as `dictionary.txt`

The words in the dictionary are stored using a set instead of an Array. Using a set allows us to very quickly check if the fragment is included in the dictionary. Using an array would take longer as the array got longer.

---

The words in the dictionary are only words three letters or longer (otherwise we wouldn't have a very interesting game).

_Have fun_
