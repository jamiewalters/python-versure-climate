This component is a fork from https://github.com/jamiewalters/python-verisure-climate. It seems like he is no longer active on this component, but there is an active pull-request waiting for him. For time beeing my version is the only active, and fully working, version of this custom component.

# Access Verisure HeatPumps in HomeAssistant

After HA Climate 1.0-change refactoring work had to be done.

This is a custom component made by https://github.com/jamiewalters/ for exposing heatpumps through Verisure as climate components in homeassistant.
This is based on the vsure python lib developed at: https://github.com/persandstrom/python-verisure

## Installation 

To install this component:

- Copy the files in this repository to your /config/custom_components/verisureclimate
- Add verisureclimate to HASS configuration as shown:
    <pre>climate:
      - platform: verisureclimate
        username: *username*
        password: *password*
    </pre>
- Restart homeassistant


### Legal Disclaimer
This software is not affiliated with Verisure Holding AB and the developers take no legal responsibility for the functionality or security of your Verisure Alarms and devices.
