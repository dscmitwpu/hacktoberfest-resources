# Installation

## On Windows

### Git CLI
Just go to [git bash][] and the download will start automatically.
Run the exe, select options according to your pref and voila

### Github CLI
Download latest msi installer from [releases page][].
Run the exe, select options according to your pref and voila

## On Linux

### Git CLI
If you’re on a Debian-based distribution, such as Ubuntu, try apt:
```bash
sudo apt install git
```

### Github CLI
If you’re on a Debian-based distribution, such as Ubuntu, download .deb from [releases page][].
Install it using 
```bash
sudo dpkg -i <filename>.deb
(Example: sudo dpkg -i gh_1.1.0_linux_amd64.deb , latest one at the time of writing)
```

## On MacOS

### Git CLI
There are several ways to install Git on a Mac. The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time.

```bash
git --version
```
If you don’t have it installed already, it will prompt you to install it.

### Github CLI
`gh` is available via [Homebrew][], [MacPorts][], and as a downloadable binary from the [releases page][].

#### Homebrew

| Install:          | Upgrade:          |
| ----------------- | ----------------- |
| `brew install gh` | `brew upgrade gh` |

#### MacPorts

| Install:               | Upgrade:                                       |
| ---------------------- | ---------------------------------------------- |
| `sudo port install gh` | `sudo port selfupdate && sudo port upgrade gh` |

[releases page]: https://github.com/cli/cli/releases/latest
[git bash]: https://git-scm.com/download/win
[hub]: https://github.com/github/hub
[manual]: https://cli.github.com/manual/
[Homebrew]: https://brew.sh
[MacPorts]: https://www.macports.org