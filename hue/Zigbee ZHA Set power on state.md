# Set the power on state of Hue bulbs in ZHA

1. Goto the ZHA devices tab and select the bulb
2. Goto `manage clusters`
3. Select the `OnOff (0x0006)` cluster
4. Select the `start_up_on_off (0x4003)` attribute
5. Set the value to `0x00 (off)`, `0x1 (warm white)`, `0xFF (restore last state)`
6. Hit set attribute
7. Hit get attribute to see if it did the change
8. Restart the bulb waiting 10 seconds and it should have changed!
