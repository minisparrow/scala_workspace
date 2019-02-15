
#SBT INSTALL 

## sbt linux deb

```bash
echo "deb https://dl.bintray.com/sbt/debian /" | sudo tee -a /etc/apt/sources.list.d/sbt.list
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 2EE0EA64E40A89B84B2DF73499E82A75642AC823
sudo apt-get update
sudo apt-get install sbt
```

#download sbt 

https://www.scala-sbt.org/download.html

## sbt path

export SBT_HOME="/home/ubuntu/sbt"

export PATH=$SBT_HOME/bin:$PATH



