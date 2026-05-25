NOTE: Set the `KCONFIG_CONFIG` to [kconfig](kconfig) when making klipper

or

```bash
docker compose --profile tools run --rm tools "make && scripts/flash-sdcard.sh /dev/serial/by-id/usb-Klipper_stm32f446xx_43001C00115053424E363620-if00 btt-octopus-f446-v1"
```
