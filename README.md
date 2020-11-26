# Convert-Numbers-to-Japanese
Converts Arabic numerals, or 'western' style numbers to a Japanese context.

![Python 3x](https://img.shields.io/badge/python-3.x-blue.svg)

## Usage:
``` bash
Convert(number,type)
``` 
**Types;** "kanji", "hiragana", "romaji", "all"\
"all" will return a list of kanji, hiragana and romaji conversions

Can also convert Kanji to 'western' number using:
``` bash
ConvertKanji(kanji)
``` 

### Examples:
``` bash
Convert(20.8,"romaji")
Convert(2000,"hiragana")
Convert(458,"kanji")
Convert("458222","kanji")
Convert(31400,"all")
``` 

``` bash
ConvertKanji("二十点五")
ConvertKanji("二十五")
``` 

Online version available here: https://www.japanesenumberconverter.com/
