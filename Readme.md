# HabenWirNochImpfstoff
forked by berlin-vac-checker by Pita
https://github.com/Pita/berlin-vac-appointment-checker 

Small node.js script that checks in short periods if Doctolib has a vaccination appointment available. If so, immediately opens a browser window for you so you can book quickly. This script worked mid of May 2021. If Doctolib changes their API, it might stop working. Only tested on intel Mac OS X.


# Usage
Have Node installed. If not google Node.JS and install.
Open Terminal and change directory to this repository folder.
Type in following commands
```
npm install
npm run start
```
The program will check the following Doctolib places for appointments:
https://www.doctolib.de/praxis/muenchen/hausarztpraxis-muenchen
https://www.doctolib.de/praxis/muenchen/dr-med-weier-praxis-am-goetheplatz
https://www.doctolib.de/praxis/muenchen/kardiologie-am-promenadeplatz
https://www.doctolib.de/praxis/muenchen/hausarztpraxis-dr-grassl

Feel free to add more places!
