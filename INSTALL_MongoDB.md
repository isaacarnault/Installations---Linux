### MongoDB

`$ mkdir mongodb` // creates a new directory<br>
`$ cd mongodb` // opens your directory<br>
`$ pwd` # gives you the path of your directory<br>
`$ curl -O https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-4.0.8.tgz` // imports the tarball<br>
`$ tar xvf mongodb-linux-x86_64-4.0.8.tgz` // opens the tarball<br>
`$ mv mongodb-linux-x86_64-4.0.8 mongodb` // adds MongoDB bin directory to PATH variable
<br>
`$ cd mongodb` // opens your directory<br>
`$ echo $PATH` // displays current path<br>
`$ export PATH=$PATH:/home/zaki/Desktop/softs/mongodb/mongodb/bin` // add MongoDB bin directory to PATH variable<br>
`$ mkdir data` // creates new directory<br>
`$ cd bin` // opens your directory<br>
`$ ./mongod --dbpath /home/zaki/Desktop/softs/mongodb/mongodb/data &` // starts MongoDB <br><br>
[![isaac-arnault-mongo-1.png](https://i.postimg.cc/0NBL2Prm/isaac-arnault-mongo-1.png)](https://postimg.cc/d7GW5M2t)
Open a new tab in your Terminal and start using `MongoDB`:<br>
`$ ps -eaf | grep mongo` // confirms MongoDB is running
`$ ./mongo` // starts MongoDB <br><br>
[![isaac-arnault-mongo-2.png](https://i.postimg.cc/d1XvXGGb/isaac-arnault-mongo-2.png)](https://postimg.cc/Fdj2kdWp)
