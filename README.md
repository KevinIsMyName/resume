# resume

## Table of Contents
  - [Install](#install)
  - [Usage](#usage)
  - [Preview an example PDF](#preview-an-example-pdf)
  - [Disclaimer](#disclaimer)
## Install

**You must have [TeX](https://tug.org/texlive/quickinstall.html) installed!**

Windows: https://tug.org/texlive/windows.html#install

macOS:
https://tug.org/mactex/mactex-download.html

Ubuntu:

```sh
$ sudo apt-get update
$ sudo apt-get install -y texlive-xetex texlive-fonts-extra
$ sudo apt-get install -y texlive-extra-utils # Recommended for VS Code, not required
```

## Usage

```bash
$ git clone https://github.com/KevinIsMyName/resume.git
$ cd resume
$ chmod u+x build.sh
$ ./build.sh # See output file resume.pdf
```

Using VS Code? Try this [LaTeX extension by James Yu](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)!

## Preview an example PDF

![PDF](./kevin/resume.png)

## Disclaimer

I forked this repository from [https://github.com/posquit0/Awesome-CV/](https://github.com/posquit0/Awesome-CV/) and edited the template for my own purpose.
