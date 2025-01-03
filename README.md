**Instructions**

![alt](/images/1.png)

![alt](/images/2.png)

To import these configurations, you need to install python and python-pipx.

**Debian and Ubuntu**

```
sudo apt install python3 pipx
```

**Fedora**

```
sudo dnf install python3 pipx
```

**Arch**

```
sudo pacman -S python python-pipx
```

Download and install Konsave using pipx package manager.

```
pipx install konsave
pipx inject konsave setuptools
```

Make sure that your “.local/bin” directory is in your current user’s PATH variable:

```
echo "PATH=$PATH:.local/bin" >> ~/.bashrc && bash
```

Download my Konsave file
https://mega.nz/file/DV9FSBjS#QFIfWHFVCorLAbSN1o8iU47mEWwbm70llS3oNgoLWxs

Import the .knsv file

```
konsave -i ./my-kde-desktop.knsv
```

Load the imported Konsave file

```
konsave -a my-kde-desktop
```

Relogin to apply the settings.
