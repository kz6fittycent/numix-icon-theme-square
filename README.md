[![numix-icon-theme-square](https://snapcraft.io/numix-icon-theme-square/badge.svg)](https://snapcraft.io/numix-icon-theme-square) [![🧪 Snap Builds](https://github.com/kz6fittycent/numix-icon-theme-square/actions/workflows/test-snap-can-build.yml/badge.svg)](https://github.com/kz6fittycent/numix-icon-theme-square/actions/workflows/test-snap-can-build.yml)

# numix-icon-theme-square

A snap for the [Numix square icon theme](https://github.com/numixproject/numix-icon-theme-square/).

## Install the snap

`sudo snap install numix-icon-theme-square`

## Connect the icon theme 

```
for i in $(snap connections | grep gtk-common-themes:icon-themes | awk '{print $2}'); do sudo snap connect $i numix-icon-theme-square:icon-themes; done
```
