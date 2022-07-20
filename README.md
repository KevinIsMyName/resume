# resume

## Install

**You must have [TeX](https://tug.org/texlive/quickinstall.html) installed!**

Windows: Install [TeXLive](https://tug.org/texlive/windows.html#install) with install-tl-windows.exe

macOS: Install [MacTeX](https://tug.org/mactex/)

```sh
$ sudo tlmgr option repository ctan
$ sudo tlmgr update --self
$ sudo tlmgr install fontawesome
```

Ubuntu:

```sh
$ sudo apt-get update
$ sudo apt-get install -y texlive-xetex texlive-fonts-extra
$ sudo apt-get install -y texlive-extra-utils # Recommended for VS Code, not required
```

## Usage

```sh
$ git clone https://github.com/KevinIsMyName/resume.git
$ cd resume
$ xelatex resume.tex # Windows and Ubuntu ONLY
$ lualatex resume.tex # macOS ONLY
```

Once the command terminates cleanly, you should see a PDF file called `resume.pdf` in the current directory.

Editing on VS Code? Try this [LaTeX extension by James Yu](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)!

## Preview an example PDF

![PDF](./kevin/resume.png)

## Disclaimer

I forked this repository from [https://github.com/posquit0/Awesome-CV/](https://github.com/posquit0/Awesome-CV/) and edited the template to my own needs.
