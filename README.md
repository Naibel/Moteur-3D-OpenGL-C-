# musIMAC

Project realised in IMAC Engineering School, in November and December 2015

**Collaborators :**

- [Dorian BELHAJ]
- [Charlotte CASEAU]
- [Sophie COGNY]

**Supported OS (require OpenGL 3+)**

- Linux Ubuntu
- Mac OSX


## How to use it

#### Clone the project

	git clone git@github.com:[...]
	
#### Build

	cd projet-opengl/build
	cmake ../project
	make
	
#### Run

	./template/game

##Prior installation

###For Mac users, install brew, a really cool package manager

    $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

###You need CMake

Linux :

    $ sudo apt-get install cmake

Mac OSX :

    $ brew install cmake
    

###You need some libs

####GLEW

Linux :

    $ sudo apt-get install glew

Mac OSX :
    $ brew install glew

####SDL2

Linux :

    $ sudo apt-get install libsdl2-dev

Mac OSX :

    $ brew install sdl2

####SDL2 MIXER

Linux :

    $ sudo apt-get install libsdl2-mixer-dev

Mac OSX :

    $ brew install sdl2_mixer
