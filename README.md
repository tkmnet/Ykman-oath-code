# Ykman-oath-code
ykman oath code getter command wrapper with clipboard

You can copy OTP that registered in your Yubikey, to the clipboard of X Window System.

## Usage
```sh
$ Ykman-oath-code  # Maybe it will be suggested Y<Tab>.
1       Amazon  012345
2       GitHub  123456
Select number to set clipboard:  # OTP is set to the clipboard by typing the number on the left.
```

## Requirements
+ yubikey-manager
+ xclip

## Installation
Put `Ykman-oath-code` on a directory included PATH which likes `/usr/local/bin`.
```sh
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/tkmnet/Ykman-oath-code/main/Ykman-oath-code
sudo chmod a+x Ykman-oath-code
```
