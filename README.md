<div align="center">
<h1>HDD Tools Hass.io Add-on</h1>
</div>

## General

This add-on provides information about HDD Temperature from S.M.A.R.T using smartmontools.
Temperature is visible in Home-Assistant via sensor sensor.hdd_temp.

## Installation

Add the repository URL under **Supervisor (Hass.io) → Add-on Store** in your Home Assistant front-end:

    https://github.com/Draggon/hassio-hdd-tools


## Configuration

Configure the add-on via your Home Assistant front-end under **Supervisor (Hass.io) → Dashboard → HDD Tools**.

The configuration:

1. hdd_path - path to drive to monitor

2. check_period - interval in minutes / how often to read temperature

3. output_file - log file

## Notes

Addon reguires Protection Mode to be disabled to access S.M.A.R.T data

## Credits

- https://www.smartmontools.org/