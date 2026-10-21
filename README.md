# guezwhoz for Pi AI agent

![GitHub Release](https://img.shields.io/github/v/release/egorlem/guezwhoz.pi?style=for-the-badge&color=7CD996&labelColor=212121)
![Static Badge](https://img.shields.io/badge/License-WTFPL-blue?style=for-the-badge&labelColor=212121&color=59D9D0&link=https%3A%2F%2Fgithub.com%2Fegorlem%2Fguezwhoz.pi%2Fblob%2Fmaster%2FLICENSE)

## What's Inside?

A dark theme for π with a cool pastel palette and a green axis.
Built for long sessions: soft colors and a symmetric background hierarchy.

More Pi resources may be added to this package over time.

![guezwhoz theme preview](https://raw.githubusercontent.com/egorlem/ultima.workspace/9fd678e50feb9af3b8d5b93260bbfb5d2746d35b/demos/pi-theme-v-0.1.1.png)

## Install

```bash
pi install npm:guezwhoz-pi
```

## Enable

Open `/settings`, choose **Theme**, and select `guezwhoz`. For a single run:

```bash
pi --use-theme guezwhoz
```

The theme is dark-only. If Pi follows the terminal appearance, select
`guezwhoz` as the dark theme in `/settings`.

## Palette

| Role | Color |
| --- | --- |
| Background | `#1D1D1D` |
| Panels | `#212121` |
| Text | `#D9D9D9` |
| Muted text | `#808080` |
| Cyan accent | `#58D6CE` |
| Blue | `#5AA0D6` |
| Green | `#7AD694` |
| Violet | `#9A90E0` |
| Yellow | `#B7D074` |
| Pink | `#E85181` |

## Accessibility

The palette targets WCAG 2.1 AA. One deliberate exception is muted text
`#808080` at 4.3:1 against the background instead of 4.5:1: it should recede
into the background and not compete with useful information.

## License

**WTFPL Ver. III.** See [LICENSE](https://github.com/egorlem/guezwhoz.pi/blob/master/LICENSE) for details.

Maintained by [Egor Lem](https://egorlem.com/).
