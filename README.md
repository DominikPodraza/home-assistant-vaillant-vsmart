# Vaillant vSMART

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]][license]

[![pre-commit][pre-commit-shield]][pre-commit]
[![Black][black-shield]][black]

[![hacs][hacs-shield]][hacs]
[![Project Maintenance][maintainer-shield]][maintainer]

[![Community Forum][forum-shield]][forum]

**This component will set up the following platforms.**

| Platform        | Description                                |
| --------------- | ------------------------------------------ |
| `climate`       | Management of Vaillant thermostat.         |
| `switch`        | Hot water boost switch of the thermostat.  |
| `sensor`        | Battery sensor for the thermostat.         |

## Installation

### HACS (recommended)

1. Open HACS
1. Search for "Vaillant vSMART"
    1. If it doesn't exist yet, you first need to add `https://github.com/MislavMandaric/home-assistant-vaillant-vsmart` as custom repository
1. Click "Install this repository in HACS"
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Vaillant vSMART"

### Manual

1. Using the tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`)
1. If you do not have a `custom_components` directory (folder) there, you need to create it
1. In the `custom_components` directory (folder) create a new folder called `vaillant_vsmart`
1. Download _all_ the files from the `custom_components/vaillant_vsmart/` directory (folder) in this repository
1. Place the files you downloaded in the new directory (folder) you created
1. Restart Home Assistant
1. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Vaillant vSMART"

## Configuration is done in the UI

<!---->

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

## Credits

This project was generated from [@oncleben31](https://github.com/oncleben31)'s [Home Assistant Custom Component Cookiecutter](https://github.com/oncleben31/cookiecutter-homeassistant-custom-component) template.

Code template was mainly taken from [@Ludeeus](https://github.com/ludeeus)'s [integration_blueprint](https://github.com/custom-components/integration_blueprint) template

This integration is a complete rewrite of [@pjmaenh](https://github.com/pjmaenh)'s original [Vaillant integration](https://github.com/pjmaenh/home-assistant-vaillant).


[maintainer]: https://github.com/MislavMandaric
[maintainer-shield]: https://img.shields.io/badge/maintainer-%40MislavMandaric-blue.svg?style=for-the-badge

[releases]: https://github.com/MislavMandaric/home-assistant-vaillant-vsmart/releases
[releases-shield]: https://img.shields.io/github/release/MislavMandaric/home-assistant-vaillant-vsmart.svg?style=for-the-badge

[commits]: https://github.com/MislavMandaric/home-assistant-vaillant-vsmart/commits
[commits-shield]: https://img.shields.io/github/commit-activity/y/MislavMandaric/home-assistant-vaillant-vsmart.svg?style=for-the-badge

[license]: https://github.com/MislavMandaric/home-assistant-vaillant-vsmart/blob/master/LICENSE
[license-shield]: https://img.shields.io/github/license/MislavMandaric/home-assistant-vaillant-vsmart.svg?style=for-the-badge

[hacs]: https://hacs.xyz
[hacs-shield]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge

[forum]: https://community.home-assistant.io/
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge

[black]: https://github.com/psf/black
[black-shield]: https://img.shields.io/badge/code%20style-black-000000.svg?style=for-the-badge

[pre-commit]: https://github.com/pre-commit/pre-commit
[pre-commit-shield]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?style=for-the-badge
