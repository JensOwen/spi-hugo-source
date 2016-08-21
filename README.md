# spi-hugo-source
Directions for how the SPI Hugo-based website is setup and managed.

## My Setup (OSX)
- Download Hugo binary from www.gohugo.io
 - first version: https://github.com/spf13/hugo/releases/download/v0.16/hugo_0.16_osx-64bit.tgz
- Install Hugo binary
```
$ tar xzvf hugo_0.16_osx-64bit.tgz
$ sudo cp hugo /usr/local/bin
```
- Create Local Website Folder
```
$ cd ~/spi
$ mkdir website
```

## Checkout Source and GitHub Pages Content
```
$ cd ~/spi/website
$ git clone https://github.com/stormpeakinnovations/spi-hugo-source.git
$ git clone https://github.com/stormpeakinnovations/stormpeakinnovations.github.io.git
```

## Regenerate Site
```
$ cd ~/spi/website/spi-hugo-source
$ hugo -d ../stormpeakinnovations.github.io --theme=grid-side
```
