# crusade-hex-map

Scipt for a hex-tile grid map with interactivity for tracking warhammer crusade campaign maps.

This script can be added to a Google Site Embed Tile.

It renders a 2D hex-tile grid map with some basic interactivity.

The purpose of this is to display data from warhammer 40k crusade campaigns where territories are involved.

## Tile Data

There is no data storage involved here so the tile data is kept as a dictionary in the script.

This dictionary is generated through a Google Sheet + formula.

To update tile data, all changes must be made in the google sheet, then a formula will convert each row into the same format as the dictionary in this script.

## Functionality

The script is basic for now. The following functionality is available:
- Clicking on a tile displays information from the tile data dictionary related to the tile at that position
- Resource level tile data is summed for each team and displayed in corner
- Feedback features like tile colour change on hover or click

## Next Steps

- Add some data storage layer
- Add the ability to change territory owner by clicking a tile and selecting an option (overwriting the tile data)
- Add more stats to the panel on the right side
- Make it look prettier
