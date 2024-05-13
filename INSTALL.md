# Installation

Installation process work for Debian, Arch Linux and there derivatives.

## download packages

In order to run this program, you need the following packages to be
installed.

[Notice]{.underline}: *First commands are for **Debian and its
derivatives** and the second ones are for **Arch Linux and its
derivatives**.*

-   python

``` bash
sudo apt install python3 python3-venv
sudo pacman -S python3
```

-   git

``` bash
sudo apt install git
sudo pacman -S git
```

## clone repository

Open your terminal and execute this:

``` bash
git clone "https://gitlab.com/rootminusone8004/bsc_thesis"
```

## virtual environment

First make a python virtual environment. **It is recommended.**

``` bash
make env
```

Install all the requirements.

``` bash
make install
```

## additional softwares

You need [ganache](https://archive.trufflesuite.com/ganache/) installed.
In Arch Linux, you can easily install it with
[AUR](https://aur.archlinux.org/packages/ganache-bin)
