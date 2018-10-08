# number-format

# #number for-matter and create shortcut number description like 1000 to 1K

A small library that adds commas to numbers

## Installation

`npm install @sprakash1/number-format`

## Usage

    var numFormatter = require('@sprakash1/number-format');

    var formattedNum = numFormatter(1000);

Output should be `1K`

    var numFormatter = require('@sprakash1/number-format');

    var formattedNum = numFormatter(12600);

Output should be `12.6K`

## Tests

`npm test`
