# valkyrie-2.0.0

## Description
this project is a custum version of valkyrie 2.0.0 that works only for Qt 5
for more infos about the program please viste links bellow
- **Website**: [Visit Valkyrie Main Website](https://valgrind.org/downloads/guis.html)
- **Download Page**: [Download Valkyrie](https://sourceware.org/pub/valgrind)

## Installation
To install the dependencies, run the following command:

`sudo apt-get install qtbase5-dev qt5-qmake qtbase5-dev-tools libqt5widgets5 libqt5gui5 libqt5core5a`

after clone the project:

`git clone https://github.com/VICTORxEVO/valkyrie-2.0.0.git && cd valkyrie-2.0.0`

compile it

`qmake && make`

install it:

`sudo make install`

to verify if successfully installed run:

`valkyrie --version`

to run it:

`valkyrie`
