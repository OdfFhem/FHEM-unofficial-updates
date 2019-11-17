# FHEM-additional-updates
Unofficial updates for FHEM and FTUI and ...

There are different controlfiles
--------------------------------
- If you want to update all unofficial files
  --> controlfile: controls_unofficial.txt
- If you want to update only all unofficial files for FTUI
  --> controlfile: controls_unofficial_ftui.txt

Downloading all files from a controlfile you can do the following operations:
-----------------------------------------------------------------------------
maybe --> update add https://raw.githubusercontent.com/OdfFhem/FHEM-unofficial-updates/master/<controlfile>
          update check https://raw.githubusercontent.com/OdfFhem/FHEM-unofficial-updates/master/<controlfile>
          update all https://raw.githubusercontent.com/OdfFhem/FHEM-unofficial-updates/master/<controlfile>
maybe --> update delete https://raw.githubusercontent.com/OdfFhem/FHEM-unofficial-updates/master/<controlfile>

Downloading single files
------------------------
- with controlfile:
  update <singlefile> https://raw.githubusercontent.com/OdfFhem/FHEM-unofficial-updates/master/<controlfile>
- without controlfile:
  use the GitHub possibilities
