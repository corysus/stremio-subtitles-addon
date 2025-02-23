# Stremio Subtitles Addon v3.0.0 (Community)

## Description

This addon will provide subtitles for movies and series from the portal titlovi.com. The subtitle languages supported by titlovi.com are Bosnian, Croatian, Serbian, Macedonian, Slovenian and English.

## What is new in version 3.0.0

- In this version, users now have the ability to choose the languages they want to use. Also, if a user chooses Bosnian, Serbian, or Croatian additional Cyrillic subtitles will be included (It will be shown as Serbian), but they will be converted to Latin or remain Cyrillic if the user selects "Use Cyrillic where possible?" on the configuration page. For other languages Slovenian, Macedonian and English subtitles will be retained in their original form.
- All languages will be converted from their original encoding to UTF-8 because Stremio only supports this encoding.
- This version also improves the retrieval of subtitles from titlovi.com where in the previous version only .zip files with .srt subtitles were processed. Now, the addon also parses .rar files and all common subtitle formats, such as sub, ssa, ass, and txt which are automatically converted to the .srt format supported by Stremio.
- Subtitles are sorted from highest to lowest rating and number of downloads.
- Now the user inside the subtitle window in Stremio can see that the subtitle comes from [titlovi.com] and for which release the subtitle is.
- Now the user has a unique generated config URL that can be used to register the addon with Stremio.

### Other updates

- Better user session and subtitle download management.
- Cache subtitles for a better response.
- The configuration URL UI has been refreshed to match a modern look and feel.
- Correct language mapping (languages now displayed correctly inside Stremio).

> Note: It's possible that some subtitles are not processed correctly and will be displayed as "??????" or similiar (this usually happens with Cyrillic).

## How to use

1. Open this URL: [https://subtitles.mooo.com/configuration](https://subtitles.mooo.com/configuration)
2. Enter your username and password that you use on the titlovi.com portal.
3. Choose the languages that you want to show in Stremio.
4. Click the Login button, and if everything is finished correctly, you will get a new screen with your unique Stremio addon URL and a button that you can click to install this addon.

You can also install an addon by opening Stremio, then navigating to Addon settings, and then copying and pasting your unique URL inside the "Search addons" box.

## Ideas/Bugs

For new ideas and bugs, please open new issues on this repository.

<br>
<br>

--| CoRySus Development 2025 |--
