# indesign-sinhala
Enable full Sinhala Unicode support in Indesign


##Set Up

###CS5 CS5.5 CS6

####MacOS

- Copy files and folder `si_LK` to `/Library/Application Support/Adobe/Linguistics/6.0/Providers/Plugins2/AdobeHunspellPlugin.bundle/Contents`

- Replace `Info.plist` file in `/Library/Application Support/Adobe/Linguistics/6.0/Providers/Plugins2/AdobeHunspellPlugin.bundle/Contents` with provided `Info.plist` file.

For CS4 5, 5.5
- Copy `enable-world-ready.jsx` into `/Applications/Adobe InDesign CS5.5/Scripts/Scripts Panel`


####Windows

- Copy files and folders in `contents` to `%ProgramFiles%\Common Files\Adobe\Linguistics\6.0\Providers\Plugins2\AdobeHunspellPlugin\Dictionaries `

- Replace `Info.plist` file in `%ProgramFiles%\Common Files\Adobe\Linguistics\6.0\Providers\Plugins2\AdobeHunspellPlugin` with provided `Info.plist` file.

For CS4 5, 5.5
-TODO-


###CC

####MacOS

-TODO-


####Windows

-TODO-


***

##License

LICENSE : GPLv3

This software is a syntax checker for Sinhala(si) language.
Copyright (C) <2010>  Laknath Semage <blaknath [at] gmail [dot] com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
