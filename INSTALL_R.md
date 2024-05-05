### Step 1: Installing R Package in Linux
First of all, we need to install the R package, which is available in the default repository of RHEL/CentOS and Ubuntu.

Run the command below if you are using an RHEL based OS.

```
# yum install R
```

Those using Ubuntu can use the apt-get command as below.

```
# apt-get install r-base
```

![image](https://github.com/lucasnuic/Installations---Linux/assets/165694895/da472706-8cd9-47c8-9acb-62e6fd36ebc5)

Once the installation is complete, check its version using the command as shown below.

```
# R --version
```

### Step 2: Using R in Linux

R is a command-line utility as discussed above for data analysis. To get a list of command-line options, run this command:

```
# R --help
```

Using the R in your terminal, you will be directed to its R console where you will be able to run its commands as per your own use as shown in the above command’s output.

```
$ R

```

### Step 3: Installing R-Studio in Linux
Let’s start the installation of RStudio, which is an Integrated Development Environment for working with R using its web console.

Download the RStudio Free Version for your OS from their official web link which is https://www.rstudio.com/products/rstudio/download/
![image](https://github.com/lucasnuic/Installations---Linux/assets/165694895/8f3accbb-6ffc-43c4-8577-ca75cf1bcff6)

Get it on your system whether upload or use the below command to download on your system.

```
# cd /tmp
# wget https://download1.rstudio.org/desktop/centos7/x86_64/rstudio-1.4.1717-x86_64.rpm
# wget https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.4.1717-amd64.deb
```

Make sure to choose the right package for the system you are using.
```
# rpm -ivh rstudio-1.4.1717-x86_64.rpm
# dpkg -i rstudio-1.4.1717-amd64.deb
```

### Step 4: Starting RStudio Services in Linux
Now we have installed RStudio on our system, next we need to make sure that its service is up and running so that we can access it and start using it.

To do so, run the command below to start the RStudio service.

```
# systemctl start rstudio-server
# systemctl enable rstudio-server
# systemctl status rstudio-server
```

![image](https://github.com/lucasnuic/Installations---Linux/assets/165694895/a3624dcc-4cd7-42cd-8bae-ab8720e1dae1)

RStudio service listens on port 8787, so make sure its its allowed in your firewall.

To allow the port run the command below on your RHEL-7/RHEL-8 system.

```
# firewall-cmd --permanent --zone=public --add-port=8787/tcp
# firewall-cmd –reload
```



Once downloaded, install it using the ‘rpm’ command in the case of RHEL based OS and use ‘dpkg’ if you are using Ubuntu.




