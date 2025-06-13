# alphabet trainer
A simple webpage for learning scripts, principally for Geoguessr

[https://billabob.github.io/AT/trainer.html](https://billabob.github.io/AT/trainer.html)

## How to use:

You will be prompted with a randomly selected character or string of characters. Type the Latin transliteration into the text box, then press Enter or click "OK". If you get the answer wrong, you will have to type it in correctly to proceed. Click "Reset" to reset your current scores to 0.

Click the topmost white \* to open the settings. The settings are:
Current language dropdown
Range to choose from (for example, setting it to 1 to 5 in Latin would give you the letters abcde)
How many characters should be presented per round. Setting this to 3 would generate length-3 strings like "bed". You need to get every single character right for the answer to count as correct. Best to raise this when you think you've mostly learned the alphabet and need to test yourself.

Click the bottommost white \* to open a cheat sheet displaying every character in the alphabet. You can open this whenever you want and it won't count towards the scores. It's up to you to use it however you see fit.

Currently there are 8 alphabets implemented. Contributions are welcome. I do not speak any of these languages so there are without a doubt going to be errors in my transliterations, please report these if you find any... and keep in mind keyboard-friendly transliterations, i.e. no diacritics or special characters, are always prioritised even if not strictly accurate or standard. This is more so I can read signs in Geoguessr than anything else.

## TODO list:

- More languages<br>
-- More Cyrillic options<br>
-- South Asian scripts<br>
-- SE Asian scripts<br>
-- Hangul<br>
-- Ge'ez<br>
-- Caucasus scripts<br>
-- North American scripts<br>
-- Historical scripts such as Sumerian & Akkadian<br>
-- Probably not Hanzi or Kanji<br>
- Improve Arabic implementation (vocalisation logic etc)<br>
- Spaced repetition system?<br>
- Revamp old bad code

## Changelog

### v1.2 - 2025-06-13

Some internals to make it easier to add languages<br>
More Cyrillic languages (Bulgarian, Serbian, Montenegrin, Macedonian, Belarusian, Ukrainian, Rusyn, Moldovan, Ossetic, Tajik, Kazakh, Kyrgyz, Tatar, Turkmen, Uzbek, Yakut, Tuvan, Abkhaz, Mongolian, Khabarovsk Ugede, Uilta)

### v1.1 - 2025-06-08

Added Greek (Modern & Ancient)<br>
Added European Cyrillic (Bulgarian, Serbian, Montenegrin, Macedonian, Belarusian, Ukrainian, Moldovan)<br>
Put settings in its own side modal<br>
Replaced language dropdown with a bespoke folder structure

### v1 - 2025-05-29

Initial release on Github. Hiragana, Katakana, Russian, Cyrillic Soup, Arabic Consonants.

### v0 - 2020-10-04

Made the page to teach myself Kana