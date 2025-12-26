# Qwirkle Bot

The goal of this project is to create a bot which plays the boardgame Qwirkle.

This is also a chance for me to learn a bit of Rust.

## The Game

Qwirkle is a tile-based game for two to four players, designed by Susan McKinley Ross and published by MindWare in 2006.

### Equipment

Qwirkle comes with 108 wooden tiles. Each tile is painted with one of six shapes (clover, four-point star, eight-point star, square, circle and diamond) in one of six colors (red, orange, yellow, green, blue and purple); there are three of each of the 36 tile color and shape combinations.

### Play

The game begins with all the tiles being placed in the bag and mixed thoroughly. Each player then draws six random tiles; each player's tiles are not displayed to the other players. All players declare the largest number of tiles of their initial set in one shape or one color, not including duplicates. Play starts with the player who can place the most tiles with their initial draw. After the first player's turn, play proceeds clockwise.

During their turn, a player may either:

* place one or several tiles on the table; or
* instead of playing tiles, or if none of the tiles held can be played, exchange one or more tiles in their hand for random tiles in the draw bag.

At least one of the tiles being placed must continue either the shape or color from at least one tile already laid down. For example: if there are three stars placed down on the grid (one green, one blue, and one purple), then the player can put down another star that is red, orange or yellow next to one of the tiles already laid down. In addition, all of the tiles laid down in a turn must be played in one line, although they do not need to touch other tiles being placed in that turn.

Players are responsible for tallying and tracking their score at the end of their turn. A player must always end a turn with six tiles, so, if they place tiles during a turn, they draw random tiles to build their hand back up to six.

If the player chooses to exchange tiles instead of placing, replacement tiles are drawn from the bag and the discarded tiles are mixed back into the bag afterward. The player scores no points following an exchanged-tiles turn.

Play continues until one person uses all of their available tiles and there are no more tiles to be drawn.


### Scoring

Players score one point for each tile placed within a line, including existing tiles within the line.

Six bonus points are scored for completing a Qwirkle, which is a continuous line that has all six colors of one shape, or all six shapes of one color. For example: red, orange, yellow, green, blue, and purple circle tiles placed in a single line.

At the end of the game, once there are no more tiles to be drawn to replenish one's hand, the first person to play all of their tiles gains an extra six point bonus, at which point the game ends, and the player who has the highest score wins.
