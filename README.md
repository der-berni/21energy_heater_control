
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)

# 21energy Heater Control integration for Home Assistant

![logo](https://github.com/der-berni/21energy_heater_control/raw/main/icon.png)

This Home Assistant integration is providing information and functions to control the Device from 21energy GmbH.

## Disclaimer:

🚨 **This custom component is an independent project and is not affiliated with 21energy GmbH. It has been developed to provide Home Assistant users with tools to integrate the devices (Heater) of 21energy GmbH into their smart home. ** 🚨

Please note that I am developing this integration to the best of my knowledge and belief, but cannot give any guarantee. Therefore, use this integration **at your own risk**.

## This component will set up the following platforms

| Platform        | Description                                          |
|-----------------|------------------------------------------------------|
| `binary_sensor` | Show something `True` or `False`.                    |
| `sensor`        | Show info from Heater.                               |
| `switch`        | Switch the Heater on / off.                          |
| `select`        | Select fan mode.                                     |
| `number`        | adjustable Fan / Power target                        |


## Setup / Installation

### Step 1: Install the integration

#### Option 1: via HACS
[![Open your Home Assistant instance and adding repository to HACS.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=der-berni&repository=21energy_heater_control&category=integration)

- Install [Home Assistant Community Store (HACS)](https://hacs.xyz/)
- Add integration repository (search for `"21energy Heater Control"` in "Explore & Download Repositories")
- Use the 3-dots at the right of the list entry to download / install the custom integration.
- After you presses download and the process has completed, you must __restart Home Assistant__ to install all dependencies
- Setup the custom integration as described below (see _Step 2: Adding or enabling the integration_)

#### Option 2: manual steps

- Copy all files from `custom_components/21energy_heater_control/` to `custom_components/21energy_heater_control/` inside your config directory in Home Assistant.
- Restart Home Assistant to install all dependencies

### Step 2: Adding or enabling the integration

__You must have installed the integration (manually or via HACS before)!__

#### Option 1: My Home Assistant

Just click the following Button to start the configuration automatically (for the rest see _Option 2: Manually steps by step_):

[![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=21energy_heater_control)

#### Option 2: Manually steps by step

Use the following steps for a manual configuration by adding the custom integration using the web interface and follow instruction on screen:

- Go to `Configuration -> Integrations` and add `"21 Heater Control"` integration
- Provide the IP-Address (or Hostname) of your Heater

#### General additional notes

Please note, that some of the available sensors are __not__ enabled by default.

## Showing Your Appreciation

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/derberni)

If you like this project, please give it a ⭐ on [GitHub](https://github.com/der-berni/21energy_heater_control)

