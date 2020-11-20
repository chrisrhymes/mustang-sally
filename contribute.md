---
layout: page
title: Contribute
subtitle: Submit your own settings
description: Find out how to contribute your own Mustang LT tone preset to this site
---

This site is open to contributions from the community. Please take a read through the instructions to find out how to contribute. 

## Contribution Notes

This is a project that I will maintain in my spare time when I can, so please bear with me and be patient. 

## Developers

The source code is open source and available on [GitHub](https://github.com/chrisrhymes/mustang-sally). If you are a developer, feel free to fork the repo, create your own tone and submit a pull request with a new markdown file in the _tones directory, following the example below, and I will review the pull request as soon as I can. 

## Non Developers

Alternatively, please copy the below example into a text editor, such as notepad or VS Code, save it as a markdown file with your tone name, such as `heavy-metal.md`. Once you have finished making your changes, please email the file to csrhymes@gmail.com and I will try and add it to the site as soon as I can.

## Creating the markdown file

* Set the title to the name of your preset and the author as your name. 
* Add the date in YYYY-MM-DD format
* To include a demo video from YouTube or Instagram add the id to youtube or instagram. Please only include one. 
* There are 4 pedals and an amp, the amp is required, but pedals are not. The pedals are:
    * stompbox
    * mod
    * delay
    * reverb
* If you don't need a particular pedal then remove that section from the file
* Set the name of the pedal or amp as the name in the Fender Tone app
* Add each setting for the pedal or amp in the following format: `Name: Value` so to set the gain as 5.0 you would enter it as `Gain: 5.0`
* Add any notes or description to the bottom of the file after the last `---`

```yaml
---
layout: tone
title: Tone Name
author: Author Name
date: 2020-11-02
youtube: video_id
instagram: post_id
stompbox:
    name: Stompbox Pedal name
    settings:
        Level: 1
mod:
    name: Mod Pedal name
    settings:
        Level: 1
amp: 
    name: Amp name
    settings:
        Volume: 5
        Gain: 3
        Treble: 6.0
        Bass: 4.5
delay:
    name: Delay Pedal name
    settings:
        Level: 1
reverb:
    name: Reverb Pedal name
    settings:
        Level: 1
---

This is the notes and description for the tone.
```