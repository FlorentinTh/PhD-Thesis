# PhD-Thesis

[![Build](https://img.shields.io/circleci/build/github/FlorentinTh/PhD-Thesis/master?style=flat-square&token=0fdc873e50de49d6e9868ff847d740d20813f3bd)](https://circleci.com/gh/FlorentinTh/PhD-Thesis) [![Last Commit](https://img.shields.io/github/last-commit/FlorentinTh/PhD-Thesis?style=flat-square)](https://github.com/FlorentinTh/PhD-Thesis/commits/master) [![License](https://img.shields.io/github/license/FlorentinTh/PhD-Thesis?style=flat-square)](https://github.com/FlorentinTh/PhD-Thesis/blob/master/LICENSE)

[![Release Version](https://img.shields.io/github/release/FlorentinTh/PhD-Thesis?style=flat-square)](https://github.com/FlorentinTh/PhD-Thesis/releases) ![Release Date](https://img.shields.io/github/release-date/FlorentinTh/PhD-Thesis?style=flat-square)

This repository contains all the sources related to my Ph. D. thesis manuscript, as well as the source file of the slides.

## Authors

**[Florentin Thullier](https://github.com/florentinth)** - _2019_

_**Contact :** [florentin.thullier1@uqac.ca](florentin.thullier1@uqa.ca)_

## Requirements

- [Docker](https://www.docker.com/get-started)
- [Visual Studio Code](https://code.visualstudio.com/)

## Usage

- Clone the repository :

```sh
$ git clone https://github.com/FlorentinTh/PhD-Thesis.git
```

- Open the project with VSCode :

```sh
$ cd PhD-Thesis
$ code .
```

- Generate the PDF file for the first time :

```
$ docker-compose -f "docker-compose.yml" up -d --build
```

> The first time you try to generate the PDF file it may take some time (depending on your hardware). Don't worry, it's totally normal and next tries will be a lot faster.

- Generate the PDF file following times :

```sh
$ docker start latex
```

> If you're not familiar with LaTeX, you can [download](https://github.com/FlorentinTh/PhD-Thesis/archive/master.zip) the sources of this repository, extract the archive and upload the content of the ```src``` folder on [Overleaf](https://overleaf.com/).

## Licence

This project is licensed under MIT License - see the [LICENSE](LICENSE) file for details.
