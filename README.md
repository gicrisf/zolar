# Zolar

Zola theme designed to minimise the energy consumption and CO2 emissions.

It is ported from [Pelican](https://blog.getpelican.com/) theme [Solar](https://github.com/lowtechmag/solar/):
> Solar is a pelican theme designed for <https://solar.lowtechmagazine.com>. It is an attempt to radically reduce the energy use the associated with accessing our content.

[**--> DEMO <--**](https://zolar.netlify.app/)

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

## Features

### Traditionals

- [x] Dithered images (only using the [Zola fork] I specifically developed for this theme)
- [x] Extremely light
- [x] Give visitors insight into the material conditions of the hardware the website runs on
- [ ] Tags
- [ ] Custom colors for each category
- [ ] Translations
- [x] RSS/Atom feed support
- [ ] Open Graph Metadata
- [ ] Twitter Card Metadata
- [ ] Sort by date in archive
- [ ] Pagination in lists
- [ ] Pagination in posts
- [ ] Period archives (Pelican feature, not displayed, low priority)

### Additionals

- [x] Anchor links in post subtitles
- [x] Customizable menus (look at `config.toml`)
- [ ] Make solar energetic insights optional
- [ ] Pre-rendered syntax highlighting (thanks to Zola, no JS needed!)
- [ ] Better table styling
- [ ] Further image optimization using multiple sources of a single image for different screen sizes (yes, there's a fallback support for ancient browsers)
- [ ] Alternatives to dithering for image compression
- [ ] Optional external link arrows in page content
- [ ] Single author pages with bio

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

Always open an issue before sending a PR. Talk about the problem/feature that you want to fix. If it’s really a good thing you can submit your PR. If you send an PR without talking about before what it is, you may work for nothing.

<!-- ## Goal
This work comes as tribute to LTM, hoping to spread the style and the themes of the magazine.
I love both Zola and Pelican theme, but I know that Rust can be even more "resource efficient"

La mia ambizione è che the author choose this theme as the new default, but it doesn't matter if
he doesn't: se riesco a fare impiegare questo tema a più persone è già un successo.
-->

## Donate

Did you liked this theme? Buy me a coffee!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V425BFU)

<!-- support the magazine too -->

## License

Open sourced under the [MIT license](LICENSE).
