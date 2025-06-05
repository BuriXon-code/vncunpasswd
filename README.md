# vncunpasswd

## About

Decodes a VNC password from the default $HOME/.vnc/passwd location, from a specified file, or from stdin

---

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

---

## Options:

+ `-h` | `--help`  : show this help
+ `-f` | `--file`  : file to read (default $HOME/.vnc/passwd)
+ `-s` | `--stdin` : read from stdin

---

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

---

## Support

### Contact me:
For any issues, suggestions, or questions, reach out via:

- **Email:** support@burixon.com.pl
- **Email:** sensei@burixon.com.pl
- **Contact form:** [Click here](https://burixon.com.pl/contact.php)

### Support me:
If you find this script useful, consider supporting my work by making a donation:

[**DONATE HERE**](https://burixon.com.pl/donate/)
