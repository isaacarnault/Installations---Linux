# Big Data and Data Science - Tools installation (Linux)

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

I'd like to provide some effective directions regarding installations you may need to perform to try `Big Data` major tools.<br>
The following gist is exclusively intended to `Linux` users.<br>
I performed my installations on `Ubuntu 18.04.2 LTS`.<br>
To check your OS version, execute `$ lsb_release -a` in your Terminal.

## Installations
1. MongoDB - done
2. Neo4j - done
3. Apache Nifi - done
4. Apache Zeppelin- done
5. Talend - upcoming
6. Apache Cassandra - upcoming
...

### Prerequisites

First, make sure Oracle `jdk` is installed. I recommend `java 1.8.0`<br>
To uninstall effectively your current `jdk`, perform this:<br>
`$ sudo apt-get remove openjdk*`<br>
`$ sudo apt-get remove --auto-remove openjdk*`<br>
`$ sudo apt-get purge openjdk*`<br>
`$ sudo apt-get purge --auto-remove openjdk*`<br>

To install `java 1.8.0`, Open Terminal `Ctrl+Alt+T` and run the command:<br>
`$  sudo add-apt-repository ppa:webupd8team/java` // adds PPA repository<br>
`$  sudo apt-get update` // updates package list<br>
`$  sudo apt-get install openjdk-8-jdk` // installs openjdk<br><br>
[![java-8.png](https://i.postimg.cc/yNvqZ0dM/java-8.png)](https://postimg.cc/cKg5qgfh)<br>
`$  javac -version` // shows your new java version

## Author

* **Isaac Arnault** - Suggesting installations of major Big Data tools.
