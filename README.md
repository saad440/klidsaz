# Klidsaz
Klidsaz is a tool to create and install your own custom keyboard layouts in GNU/Linux.
Most current GNU/Linux distributions handle keyboard layouts through xkeyboard-config. The layouts are plain text files mapping keys to the desired characters. To make them available to common desktop environments (or "install" them), an entry has to be made in XKB rules. Klidsaz aims to automate both these tasks of creating and installing custom keyboard layouts.

# Usage
Run klidsaz. Select a key. An input box will appear. Enter the desired character or its Unicode value.
Press "Generate File" to simply get your keyboard layout file. Or "Install Keyboard" if you want to install it.

# Homepage
https://github.com/saad440/klidsaz

# License
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

# Contributors
Muhammad Saad <muhammad.saad3@gmail.com>  (original author)

# Features
* Create a keyboard layout file for XKB
* Install the layout by making an entry in evdev.xml

# To Do
* Streamline the installation process
* Make it create an entry in base.lst. Not sure if it will be necessary, though.
* Add translations
