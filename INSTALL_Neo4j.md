### Neo4J
Before you start installing `Neo4j`, perform as follows:<br><br>
`$ javac -version` // make sure you have Oracle `jdk` is installed. I recommend `java 1.8.0`. See[Prerequisites](https://gist.github.com/isaacarnault/19979a97be64192bb15b7b5e2e351889#prerequisites) for install<br>
`$ wget -O - https://debian.neo4j.org/neotechnology.gpg.key | sudo apt-key add` - // fetching package and adding a key<br>
`$ echo 'deb http://debian.neo4j.org/repo stable/' >/tmp/neo4j.list` - // echoing to the repository<br>
`$ sudo mv /tmp/neo4j.list /etc/apt/sources.list.d` - // moving the package<br>
`$ sudo apt-get update` - // updates all dependencies<br>
Now, you are ready to install `Neo4j`.<br>
`$ mkdir neo4j` // creates a new directory<br>
`$ cd neo4j` // opens your directory<br>
`$ pwd` # gives you the path of your directory<br>
`$ sudo apt-get install neo4j=3.1.4` // stable version I am using - community edition<br>
`$ sudo service neo4j restart` // restarts the service<br>
You can access `Neo4j` from the following url: http://localhost:7474/browser/<br><br>
[![isaac-arnault-neo4j.png](https://i.postimg.cc/cLq2v07G/isaac-arnault-neo4j.png)](https://postimg.cc/qzLjYfZ1)
