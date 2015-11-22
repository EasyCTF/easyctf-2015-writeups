# Teach Me How to Write Like This (30)

## Problem

My friend Michelle found this cool new site, but you have to pay to read and she doesn't have money. Can you help her read the [fics](https://www.easyctf.com/static/problems/fandoms/index.html) anyways?

## Hint

Where can you find out what files are in a server?

## Writeup

Using inspect element, we can remove the div pay and class blur. Then we can read the fic (which is just brilliant by the way).

![](screenshots/fanfic.png)

The flag is hidden in the story text.

## Flag

`easyctf{geico_geck0s}`

## External Writeups

* https://github.com/ztaylor54/CTF/blob/master/EasyCTF%202015/teach_me_how_to_write_like_this.md
* https://github.com/1lastBr3ath/EasyCTF-2015-Writeup/blob/master/web.md
