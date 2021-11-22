# Minecraft Java installation!

#### Java 8
```linux
sudo apt-get install openjdk-8-jdk -y
```

#### Java 11
```linux
sudo apt-get install openjdk-11-jdk -y
```

####  Java 16
```linux
sudo add-apt-repository ppa:linuxuprising/java -y
sudo apt update
sudo apt-get install oracle-java16-installer
```

#### Java 17
```linux
sudo add-apt-repository ppa:linuxuprising/java -y
sudo apt update
sudo apt-get install oracle-java16-installer
```

#### Check the java version 
```linux
java -version
```

#### If the java version is not correct, type and set the specify version
```linux 
sudo update-alternatives --config java
```

# Uninstalling all Java version from server
```linux
sudo apt purge java-common -y
sudo apt autoremove -y
```


# Custom Java distributions!

#### Amazon Corretto
```linux
sudo apt update -y
sudo apt install software-properties-common -y
wget -O- https://apt.corretto.aws/corretto.key | sudo apt-key add -
sudo add-apt-repository 'deb https://apt.corretto.aws stable main'
sudo apt update
```

#### Amazon Corretto 8
```linux
sudo apt install java-8-amazon-corretto-jdk -y
```

#### Amazon Corretto 11
```linux
sudo apt install java-11-amazon-corretto-jdk -y
```

#### Amazon Corretto 16
```linux
sudo apt install java-16-amazon-corretto-jdk -y
```

#### Amazon Corretto 17
```linux
sudo apt install java-17-amazon-corretto-jdk -y
```

#### Amazon Corretton Check the java version 
```linux
java -version
```
