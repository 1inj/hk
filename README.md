$ wget -q -O - archive.kali.org/archive-key.asc | sudo  apt-key add
$ sudo apt update && sudo apt upgrade
$ sudo apt-get install git
$ sudo apt-get install python
$ sudo git clone https://github.com/LionSec/katoolin.git
$ sudo cp katoolin/katoolin.py /usr/bin/katoolin
$ sudo chmod +x /usr/bin/katoolin
