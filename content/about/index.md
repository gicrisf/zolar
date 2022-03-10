+++
title = "about"
path = "about"

[extra]
date = 2019-03-21
+++

Zolar is a theme designed to minimise the energy consumption and CO2 emissions.
It should work perfectly for any solar-powered magazine like [LowTechMag](https://solar.lowtechmagazine.com/).
This theme is a port of LowTechMag's one, originally written for [Pelican](https://blog.getpelican.com/) (theme [Solar](https://github.com/lowtechmag/solar/)).

> Solar is a pelican theme designed for <https://solar.lowtechmagazine.com>. It is an attempt to radically reduce the energy use the associated with accessing our content.

## Install

Download this theme to your themes directory:

```bash
$ cd website/themes
$ git clone https://github.com/gicrisf/zolar.git
```

Or install as a submodule, if your project is in a git repository:

```bash
$ cd website/themes
$ git submodule add https://github.com/gicrisf/zolar.git
```

## Configurations

Enable the theme in your config file:

```toml
theme = "zolar"
```

Set your preferred date format and timezone:

```toml
[extra]
timeformat = "%B %Y"
timezone = "UTC"
```

## Contributing

Look the [GitHub Page](https://github.com/gicrisf/zolar)!

## Donate

Did you liked this theme? Buy me a coffee!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V425BFU)

<!-- support the magazine too -->

## License

Open sourced under the [MIT license](LICENSE).
