# New official my-PV Home Assistant integration.

Dear users, [my-PV GmbH](https://www.my-pv.com) has released an [official my-PV Home Assistant integration](https://github.com/my-PV/home-assistant-integration) that replaces this and other forks of the integration by [@EldarKarahasanovic](https://github.com/EldarKarahasanovic) and [@zaubererty](https://github.com/zaubererty).

The following devices are supported by the new integration:
- AC ELWA 2
- AC•THOR range
- HEA•THOR IoT
- SOL•THOR

The WiFi Meter is not supported.

Click the following button to open the integration directly on the HACS integration page.

[![Install my-PV from HACS.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=my-PV&repository=home-assistant-integration&category=integration)

You are invited to install the new integration, we are looking forward to your experience with the new integration.

## Old "unofficial" my-PV Home Assistant integration

**This repository will no longer be maintained but will stay working while it lasts.**

The myPVHomeAssistant Integration is used to integrate with the devices of [my-PV GmbH](https://www.my-pv.com). Supported devices are ACTHOR, ELWA, ELWA2 and WiFi-Meter.

This repo is forked from <a href="https://github.com/EldarKarahasanovic/myPVHomeAssistant" target="_blank">@EldarKarahasanovic</a> and <a href="https://github.com/zaubererty/homeassistant-mvpv" target="_blank">@zaubererty</a>.

### Installation

Copy this folder to `config/custom_components/mypv/`.

### Removal Instructions

After removing the devices in Home Assistant remove the `config/custom_components/mypv/` directory and restart Home Assistant.
