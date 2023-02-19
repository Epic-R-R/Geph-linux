# Geph linux

## Steps

### 1. Install Flatpak:

> To install Flatpak on Ubuntu 18.10 (Cosmic Cuttlefish) or later, simply run:

```
$ sudo apt install flatpak
```

> With older Ubuntu versions, the official Flatpak PPA is the recommended way to install Flatpak. To install it, run the following in a terminal:

```
$ sudo add-apt-repository ppa:flatpak/stable
$ sudo apt update
$ sudo apt install flatpak
```

### 2. Install the Software Flatpak plugin

> The Flatpak plugin for the Software app makes it possible to install apps without needing the command line. To install, run:

```
$ sudo apt install gnome-software-plugin-flatpak
```

> `Note: `the Software app is distributed as a Snap since Ubuntu 20.04 and does not support graphical installation of Flatpak apps. Installing the Flatpak plugin will also install a deb version of Software and result in two Software apps being installed at the same time.

### 3. Add the Flathub repository

> Flathub is the best place to get Flatpak apps. To enable it, run:

```
$ flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

### 4. `To complete Setup, restart your system.`

<br/>

### 5. Install Geph with flatpak

```
$ curl -o Geph-x86_64.flatpak -L https://3.ly/aocQL && flatpak install Geph-x86_64.flatpak
```

### 6. Run Geph

```
$ flatpak run io.geph.GephGui
```

## Enjoy free internet
