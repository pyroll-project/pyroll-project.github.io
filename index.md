---
layout: home  
list_title: News
---

![PyRoll Banner](img/pyroll_banner.svg)

Welcome to The PyRoll Project!

PyRoll is an OpenSource rolling framework, aimed to provide a fast and extensible base for rolling simulation. The
current focus lies on groove rolling in elongation grooves. The core packages comes with a basic set of models to allow
a first estimation of forces and torques occurring in a pass sequence. There is a flexible plugin system, able to modify
and extend the model set available to describe the process.

## Official Packages

The project maintains the core package and a bunch of additional plugin packages listed in the following. If you would
like your package listed here, please [contact us](mailto:kalibrierzentrum@imf.tu-freiberg.de).

- Core package `pyroll-core`: [source](https://github.com/pyroll-project/pyroll-core)
  , [docs](https://pyroll.readthedocs.io/)
- Wusatowski spreading model
  package `pyroll-wusatowski-spreading`: [source](https://github.com/pyroll-project/pyroll-wusatowski-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-wusatowski-spreading/blob/main/docs/docs.pdf)
- Marini spreading model
  package `pyroll-marini-spreading`: [source](https://github.com/pyroll-project/pyroll-marini-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-marini-spreading/blob/main/docs/docs.pdf)
- Roux spreading model
  package `pyroll-roux-spreading`: [source](https://github.com/pyroll-project/pyroll-roux-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-roux-spreading/blob/main/docs/docs.pdf)
- Hill spreading model
  package `pyroll-hill-spreading`: [source](https://github.com/pyroll-project/pyroll-hill-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-hill-spreading/blob/main/docs/docs.pdf)
- Sander spreading model
  package `pyroll-sander-spreading`: [source](https://github.com/pyroll-project/pyroll-sander-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-sander-spreading/blob/main/docs/docs.pdf)
- Sparling spreading model
  package `pyroll-sparling-spreading`: [source](https://github.com/pyroll-project/pyroll-sparling-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-sparling-spreading/blob/main/docs/docs.pdf)
- Freiberg flow stress model
  package `pyroll-freiberg-flow-stress`: [source](https://github.com/pyroll-project/pyroll-freiberg-flow-stress)
  , [docs](modules/pyroll-freiberg-flow-stress/docs/index.md)
- Integral thermal model
  package `pyroll-integral-thermal`: [source](https://github.com/pyroll-project/pyroll-integral-thermal)
  , [docs](modules/pyroll-integral-thermal/docs/docs.md)
- Hensel Power and Labour model
  package `pyroll-hensel-power-and-labour`: [source](https://github.com/pyroll-project/pyroll-hensel-power-and-labour)
  , [docs](https://github.com/pyroll-project/pyroll-hensel-power-and-labour/blob/main/docs/docs.pdf)
- Sims Power and Labour model
  package `pyroll-sims-power-and-labour`: [source](https://github.com/pyroll-project/pyroll-sims-power-and-labour)
  , [docs](https://github.com/pyroll-project/pyroll-sims-power-and-labour/blob/main/docs/docs.pdf)
- Lendl's method for equivalent rectangle
  package `pyroll-lendl-equivalent-method`: [source](https://github.com/pyroll-project/pyroll-lendl-equivalent-method)
  , [docs](https://github.com/pyroll-project/pyroll-lendl-equivalent-method/blob/main/docs/docs.pdf)
- Hitchcock roll flattening model
  package `pyroll-hitchcock-roll-flattening`: [source](https://github.com/pyroll-project/pyroll-hitchcock-roll-flattening)
  , [docs](https://github.com/pyroll-project/pyroll-hitchcock-roll-flattening/blob/main/docs/docs.pdf)
- Zouhar contact model
  package `pyroll-zouhar-contact`: [source](https://github.com/pyroll-project/pyroll-wusatowski-spreading)
  , [docs](https://github.com/pyroll-project/pyroll-wusatowski-spreading/blob/main/docs/docs.pdf)

## The PyRolL Basic Configuration

Besides the great amount of packages we composed a "basic" configuration which can be used "out of the box" and can be
downloaded via PyPI under: `pyroll-basic`.
It consists of the following packages:

- `pyroll-core`
- `pyroll-wusatowski-spreading`
- `pyroll-integral-thermal`
- `pyroll-freiberg-flow-stress`
- `pyroll-hensel-power-and-labour`
- `pyroll-lendl-equivalent-method`
- `pyroll-zouhar-contact`
- `pyroll-hitchcock-roll-flattening`

## Contributing

For contributing please contact us via mail or preferably the issue system of the corresponding repository. If you want
to create you own plugin package, please use
the [plugin template](https://github.com/pyroll-project/pyroll-plugin-template) and follow the instructions there.