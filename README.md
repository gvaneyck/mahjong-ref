These rules and UI references are based on [Mahjong Soul](https://mahjongsoul.game.yo-star.com/)

# General Riichi Mahjong Rules

* Tiles
  * There are four of each tile
  * Each hand, there are ten tiles in the dead wall (top left) that will not be drawn
  * Suits - **Man**, **Pin**, **Sou**, valued 1 through 9
  * **Winds** - North, East, West, South
  * **Dragons** - Green, Red, White
  * **Terminals** - 1 and 9 of each suit
  * **Honors** - **Winds** & **Dragons**
  * **Yakuhai** - **Dragons** & Seat **Wind** & Prevalent **Wind**, see [Open Yaku](README-open-yaku.md)
* To win a hand, you need a **completed hand** and at least one **Yaku**
* A **completed hand** is one that has four triplets and/or sequences and a pair
  * Triplets are three of the same tile, e.g. 333 **Sou** or NNN **wind** tiles
  * Sequences can only be made from suits, e.g. 123 **Sou** or 345 **Man**
  * When you are one tile away from completing your hand, you are in **Tenpai**.  The tile(s)
    you are waiting on to complete your hand are called waits
  * You either need to draw your winning tile (**Tsumo**) or have another player discard
    it (**Ron**) when you are in **Tenpai**
  * There are some rare exceptions to hand composition, see the various **Yaku**
* A **Yaku** is some criteria on the composition of your hand to make it qualified
  * The easiest way to get a **Yaku** is to not make **calls** and keep your hand closed.
    This enables **Riichi** which is a **Yaku** on any hand in **Tenpai** regardless of exact
    composition.
    See [Closed-Only Yaku](README-closed-only-yaku.md)
  * Making **calls** may make your hand easier to complete, but reduce the value and restrict
    your **Yaku** options.  See [Open Yaku](README-open-yaku.md)
  * There are also some very lucky or difficult **Yaku** options.
    See [Lucky or Difficult Yaku](README-lucky-or-difficult-yaku.md)
* **Calls**
  * There are some **calls** you can make to take other players' discarded tiles
  * Making a **call** opens your hand (except **Concealed Kan**)
  * After making the **call**, the tiles will be set aside and revealed to all players.  They
    are locked in and cannot be changed
  * After each **call**, you will discard a tile because you chose to skip your normal draw
    to draw another player's discard
  * **Chii** - You can call this when the player to your left discards a tile that you can
    make a sequence from
  * **Pon** - You can call this when anyone discards a tile that you can make a triplet from.
    This may skip over other players
  * **Kan** - You can call this when anyone discards a tile that you can make four of a kind
    from.  After calling **Kan**, another **Dora** indicator is revealed and you draw an extra
    tile to preserve your hand size
  * **Concealed Kan** - If you draw the fourth tile, on any of your turns you can call **Kan**.
    This does not open your hand, but otherwise works like a normal **Kan**
* Once you have won your hand you receive points from your opponents based on its value
  * A rough rule of thumb is you get 1000 points for each **Han** you had
  * If other players called **Riichi**, you take their 1000 point ante.  See the red dot stick
    count in the top left under the **Dora** indicators
  * If the dealer (East seat) wins or draws, 300 point bonuses start stacking up.
    See the black dots stick count in the top left under the **Dora** indicators
  * If the dealer wins, they get an extra 50% points than the hand would normally get
  * If you win via **Tsumo**, all players pay you points with the dealer paying a larger share
  * If you win via **Ron**, the player that discarded your winning tile pays all the points
  * See [Bonus **Han**](README-bonus-han.md) for additional **Han** options
* Draws
  * If no one wins after the last tile is discarded, players in **Tenpai** split 3000 points
    from players not in **Tenpai** (**Noten**).  You do not need a **Yaku** to be in **Tenpai**
  * If all players **Riichi**, the hand is a draw
  * If all players discard the same **wind** on their first discard, the hand is a draw
  * If a player starts with nine different terminal and honor tiles, they may choose
    to reveal their hand and force a draw
  * Any **Riichi** antes stay in the pot until someone wins a hand
  * The dealer stick count will always increase for a draw
* **Furiten**
  * If one of your wait tiles has been discarded by you, you are not allowed to call **Ron**
    to win.  You'll have to either **Tsumo** or change the tiles you're waiting to win
  * If you do not claim **Ron** on one of your opponents (because you don't want to steal
    their points or are going for a more valuable wait), you have to wait until after your
    next discard before you can claim **Ron** again.  If you are in **Riichi** and do this, 
    you can never claim **Ron** and have to wait for **Tsumo**
* End of game
  * The game ends after all four players have been dealer at least once (East game,
    one round of dealers) or twice (South game, two rounds of dealers)
  * The dealer (East seat) does not change if the dealer wins the hand, is in Tenpai
    when the wall runs out of tiles, or if there is a draw
  * If after the last dealer round no players have 30000 points, play continues until
    someone does

See [General Strategies](README-general-strategies.md) for some beginner advice
