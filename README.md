# Big Data and Data Science - Tools installation (Linux)

[![Project Status: Concept – Minimal or no implementation has been done yet, or the repository is only intended to be a limited example, demo, or proof-of-concept.](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept)

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
`$  sudo add-apt-repository ppa:webupd8team/java*` // adds PPA repository<br>
`$  sudo apt update // installs java8 installer` // updates your environment<br>
`$ sudo apt install oracle-java8-installer*` // installs java8 installer<br><br>
[![java-8.png](https://i.postimg.cc/yNvqZ0dM/java-8.png)](https://postimg.cc/cKg5qgfh)<br>
`$  javac -version` // shows your new java version

## Author

* **Isaac Arnault** - Suggesting installations of major Big Data tools.
