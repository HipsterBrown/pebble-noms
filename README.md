# Noms Pebble Watch Face
_by Fazli Sapuan_

Watch face "noms" the time every minute.

[![ScreenShot](http://i.imgur.com/8EktpNe.gif)](http://imgur.com/8EktpNe)

NOTE: If you have downloaded and are using v1.3, this update is not necessary. It's exactly the same.

###[Download v1.4](https://www.dropbox.com/s/4rseffz5e083q5t/pebble-noms-1.4.pbw)

###Tips:

Feel free to tip some bitcents:

	15dYcxzVR6kfZJjYnw5GMFSGQG9nGhDBvd

###Change log:

May 10 v1.4
* Fixed custom font not unloaded on deinit (This update was a precaution and was determined to be unnecessary. See [this]( http://forums.getpebble.com/discussion/comment/35808#Comment_35808))

April 20 v1.3
* Added one more tooth to both sets of teeth
* Updated menu icon with rounded edges

April 14 v1.2
* Included menu icon

April 13 v1.1
* Change to bigger fonts

April 13 v1.0
* Initial release

## Build Instructions

Clone this repository in an appropriate directory:

	git clone https://github.com/Fuzzie360/pebble-noms.git

Set up waf:

	python ~/pebble-dev/pebble-sdk-release-001/tools/create_pebble_project.py --symlink-only ~/pebble-dev/pebble-sdk-release-001/sdk/ pebble-noms
	cd pebble-noms

Configure and build:

	./waf configure
	./waf build

Install pebble-noms.pbw in build directory

## License

Copyright (C) 2013  Fazli Sapuan

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.

You may contact the author at fazli@sapuan.org

## Contributions

* Menu icon made by [blaziken311](http://www.reddit.com/user/blaziken311)

## Fonts Used

Big Noodle Titling from Sentinel Type, designed by James Arboghast
