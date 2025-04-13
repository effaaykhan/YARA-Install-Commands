# YARA-Install-Commands
This repo contains the commands to Install YARA &amp; YARA Rules on Ubuntu &amp; Windows

## Install YARA Ubuntu/Debian
```
apt-get install automake libtool make gcc pkg-config
```

```
sudo apt install libmagic-dev
```

```
sudo apt install libjansson-dev
```

```
sudo apt install -y libssl-dev
```

```
apt-get install flex bison
```

```
wget https://github.com/VirusTotal/yara/archive/refs/tags/v4.5.2.tar.gz
```

```
tar xzvf v4.5.2.tar.gz
```
```
cd yara-4.5.2
```

```
./bootstrap.sh
```

```
./configure --enable-cuckoo --enable-magic --enable-dotnet
```

```
make
make install
make check
```

## Install YARA Windows
```
https://github.com/VirusTotal/yara/releases/download/v4.1.0/yara-v4.1.0-1612-win64.zip
```

```
Unzip and run the exe
```

## Yara Rules

- cd *into your diectroy where you installed yara
```
git clone https://github.com/Yara-Rules/rules.git
```
