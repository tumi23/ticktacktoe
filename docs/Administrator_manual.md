#Administrator manual 

## Getting Started
To play Tic Tac Toe on your computer, you have to do the following: 

-
#### Java JDK
You need to have Java runtime enviroment on your computer. 

##### On Windows
Go to [Oracle](http://www.oracle.com/technetwork/java/javase/downloads/jre7u9-downloads-1859586.html) and follow the install instructions. 

##### On Mac/Linux 
Go to [Homebrew](http://brew.sh) and copy the Url and run in the Terminal. Do the following in the Terminal:

 - brew tap caskroom/cask
 - brew install brew-cask
 - brew cask install java

-
#### Git
If you don't have git installed on your computer, go to [Git](http://git-scm.com/download/win "Download and install it from here")

####Gradle
If you don't have gradle in your computer, do the following:

###### On Windows
Download, unzip and setup Gradle [Instructions]( https://docs.gradle.org/current/userguide/installation.html "Follow these instructions"). 
   
- Remember to:
    - Add GRADLE_HOME/bin to your PATH environment variable
    - Add a valid JDK to the environment variable JAVA_HOME.

###### On Unix/Linux 
Go to [Homebrew](http://brew.sh) and copy the Url and run in the Terminal. Do the following in the Terminal:

- brew install gradle

-
#### Running Tic Tac Toe on your computer

Go to [GitHub](https://github.com/Hubar/ticktacktoe) and download the project as .zip/.tar.gz

###### On Unix/Linux 
Open the command prompt and navigate the folder location. Write the following, to run the game:

	./bin/deploy

###### On Unix/Linux 
Open the terminal and navigate the folder location. Write the following, to run the game:

	sh .\bin\deploy

-
#### Heroku
If you don't have Heroku installed on your computer you have to sign up on [Heroku](Heroku.com) and the set up the [Heroku Toolbelt](https://toolbelt.heroku.com). Then open cmd/terminal and sign in using Heroku Toolbelt:

	Heroku login
	
Go to [Heroku](https://afternoon-brook-4846.herokuapp.com) to play our game on the web. 

-
### .jar
When you have run the game on your computer, a .jar file will be saved in the root of your computer in a directory name jar. Go in the jar directory and then you can just run this command to play the game as a console project. 

	java -jar ticktacktoe.jar

-
### How to play the game 

##### Console Project
This is the starting position

![TicTacToe Board](https://github.com/Hubar/ticktacktoe/blob/master/docs/image/1.png)

For an example player can type in number 1 to 9 and then press Enter. Player 1 types in 3, then **X** will come in place 3 instead of the number 3. The board will look like that: 

![TicTacToe Board](https://github.com/Hubar/ticktacktoe/blob/master/docs/image/2.png)

Then there is players 2 turn to play. He will type in 7, and the place 7 will now be **O**.

![TicTacToe Board](https://github.com/Hubar/ticktacktoe/blob/master/docs/image/3.png)

The first one to get 3 in a row wins the game. 

##### Web project

[Play game here!] (https://afternoon-brook-4846.herokuapp.com)

-
