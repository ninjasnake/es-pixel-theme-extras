# EmulationStation's Pixel theme extras

Script for RetroPie to install some extras for the EmulationStation's Pixel theme (Retropie menu icons, boot splashscreen and launching images).

## Instalation

```bash
cd /home/pi/
git clone https://github.com/hiulit/es-pixel-theme-extras.git
cd es-pixel-theme-extras/
sudo chmod +x es-pixel-theme-extras.sh
```

## Usage

```bash
sudo ./es-pixel-theme-extras.sh [OPTIONS]
```

## Options

* `--install`: Install extras (Retropie menu icons, boot splashscreen and launching images).
* `--uninstall`: Uninstall extras.

## Examples

### `--install`

Install extras (Retropie menu icons, boot splashscreen and launching images).

`sudo ./es-pixel-theme-extras.sh --install`

### `--uninstall`

Uninstall extras.

`sudo ./es-pixel-theme-extras.sh --uninstall`

## Changelog

See [CHANGELOG](/CHANGELOG.md).

## Authors

Me 😛[@hiulit](https://github.com/hiulit).

## License

See [MIT License](/LICENSE).
