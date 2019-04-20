### Nifi
Before you start installing `Nifi`, perform as follows:<br><br>
`$ javac -version` // make sure you have Oracle `jdk` is installed.<br>I recommend `java 1.8.0`. See [Prerequisites](https://gist.github.com/isaacarnault/19979a97be64192bb15b7b5e2e351889#prerequisites) for install<br>
Now, you are ready to install `Nifi`.<br>
`$ mkdir nifi` // creates a new directory<br>
`$ cd nifi` // opens your directory<br>
`$ pwd` // gives you the path of your directory<br>
`$ wget http://apache.mirrors.ovh.net/ftp.apache.org/dist/nifi/1.9.1/nifi-1.9.1-bin.tar.gz` // downloads the tarball<br>
`$  tar -xvf /home/zaki/Desktop/softs/nifi/nifi-1.9.1-bin.tar.gz` // extracts the tarball<br>
`$ bin/nifi.sh run` // runs the service<br><br>
[![isaac-arnault-nifi-1.png](https://i.postimg.cc/GhrrfFNy/isaac-arnault-nifi-1.png)](https://postimg.cc/G9MZ8ybL)<br><br>
You can access `Nifi` from the following url: http://localhost:8080/nifi // wait 2 minutes and refresh the page<br><br>
[![isaac-arnault-nifi-2.png](https://i.postimg.cc/T2nfQ7kx/isaac-arnault-nifi-2.png)](https://postimg.cc/Th2z39MN)
<br>
`$ bin/nifi.sh status` // status of the service - run it in another tab<br>
`$ bin/nifi.sh stop` // stops the service - run it in another tab<br>
`$ bin/nifi.sh restart` // restarts the service - run it in another tab<br>
