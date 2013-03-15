#Bingo Board Generator

This is a working scaffold that you can use to generate 5x5 bingo boards. Each board takes 24 inputs + text for the center free space spot. Each of the 24 inputs are randomly shuffled and placed the board. This means that user can generate a set of unique boards. The boards are totally plain, so styling is up to you using css. 

## Divs

There are only 3 basic div elements: 
- .board for each bing board
- .header for the board title
- .square for each square on each board
- There are also nth-child styled elements for the 1st and 5th row

## Local Storage

This uses local storage caching to access the data on the second page