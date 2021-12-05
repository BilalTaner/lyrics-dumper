## WELCOME TO LYRICS DUMPER!

## Usage

ES5 Syntax

```js
const { getLyrics } = require("lyrics-dumper");

const main = async () => {
  const result = await getLyrics("Lil Nas X, Jack Harlow - INDUSTRY BABY");

  console.log(result); // -> { result object }
};

main();
```

ES6 Syntax

```js
import { getLyrics } from "lyrics-dumper";

const main = async () => {
  const result = await getLyrics("Lil Nas X, Jack Harlow - INDUSTRY BABY");

  console.log(result); // -> { result object }
};

main();
```

##### Example Output for Result

```json
{
  "title": 'Romantic Lover',
  "artist": 'Eyedress',
  "lyrics": "She's a killer\n" +
    'Looking at ya\n' +
    "She's my type\n" +
    'Very nice to meet ya\n' +
    '\n' +
    "She's a killer\n" +
    'One look is all it takes\n' +
    "She's a killer\n" +
    'And she took my breath away\n' +
    '\n' +
    "She's a killer\n" +
    'Romantic lover\n' +
    'There is no other\n' +
    'She is my lover\n' +
    '\n' +
    'I need her\n' +
    'I gotta see her\n' +
    "Pullin' up on you girl\n" +
    'Very nice to meet ya\n' +
    '\n' +
    "She's a killer\n" +
    'I love her features\n' +
    'A perfect picture\n' +
    'Very nice to meet ya\n' +
    '\n' +
    "I'm tryna see ya\n" +
    "I'm tryna hear ya\n" +
    "Yes, you're my lover\n" +
    'There is no other',
  "source": 'Musixmatch'
}
```

## WARNING!

If you are confronted with any problems, you can come to our discord support server below.

[Support Server](https://discord.gg/4agCuVt)
