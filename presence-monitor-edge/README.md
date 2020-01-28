# Bluetooth Presence Monitor

[![GitHub Release][release-shield]][release]
![Project Stage][project-stage-shield]
![Project Maintenance](https://img.shields.io/badge/maintainer-Andrey%20Khrolenok%20%40Limych-blue.svg)

[![GitHub pull requests](https://img.shields.io/github/issues-pr/Limych/addon-presence-monitor?style=popout)](https://github.com/Limych/addon-presence-monitor/pulls)
[![Bugs](https://img.shields.io/github/issues/Limych/addon-presence-monitor/bug.svg?colorB=red&label=bugs&style=popout)](https://github.com/Limych/addon-presence-monitor/issues?q=is%3Aopen+is%3Aissue+label%3Abug)

Passive Bluetooth presence detection of beacons, cell phones, and other Bluetooth devices.

## WARNING! THIS IS AN EDGE VERSION!

Edge builds add-ons are based upon the latest development version.

- It may not work at all.
- It might stop working at any time.
- It could have a negative impact on your system.

This release was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/Limych/hassio-addons>


## About

This add-on actually is a usage convenient shell for launching [the Andrew J Freyer's monitor script](https://github.com/andrewjfreyer/monitor) on the same machine where the Home Assistant itself works.
This script useful for MQTT-based home automation, especially when the script runs on multiple devices, distributed throughout a property.

You can combine add-on and common versions of this presence monitor script in any combinations.

[Click here for the full documentation][docs]


[docs]: https://github.com/Limych/addon-presence-monitor/blob/369fbd8/README.md
[project-stage-shield]: https://img.shields.io/badge/project%20stage-beta-yellow.svg
<!-- [project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg -->
[release-shield]: https://img.shields.io/badge/version-369fbd8-blue.svg
[release]: https://github.com/Limych/addon-presence-monitor/tree/369fbd8