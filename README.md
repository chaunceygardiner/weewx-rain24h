# weewx-rain24h
*Open source plugin for WeeWX software.

Copyright (C)2020 by John A Kline (john@johnkline.com)

**This extension requires Python 3.7 or later and WeeWX 4.**


## Description

Rain24h is a WeeWX service that inserts 24 hour rainfall totals into loop packets.
The 24-hour rainfall is available in reports as `$current.rain24h`
It's also available via the
[weewx-loopdata plugin](https://github.com/chaunceygardiner/weewx-loopdata), as `current.rain24h`


## Why require Python 3.7 or later?

Rain24h code includes type annotation which do not work with Python 2, nor in
earlier versions of Python 3.


## Licensing

weewx-rain24h is licensed under the GNU Public License v3.
