# vncunpasswd

## About

Decodes a VNC password from the default $HOME/.vnc/passwd location, from a specified file, or from stdin

## Installation

To install script execute:

```
git clone https://github.com/BuriXon-code/vncunpasswd
cd vncunpasswd
chmod +x vncunpasswd
```

If you want to add it permanently to the system use:

```
sudo cp vncunpasswd /usr/bin/
```

or in Termux:

```
cp vncunpasswd $PREFIX/bin/
```

## Usage:

+ reads password file from the deafult location i. e. $USER/.vnc/passwd: 
```
vncunpasswd
```

+ reads password file from CLI argument:

```
vncunpasswd -f some-password-file
```

+ reads password from standard input through pipe:

```
echo 123456 | vncpasswd -f | vncunpasswd -s
```

