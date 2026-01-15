# ESPHome Emulator

Pretend to be an ESPHome device with a Python script.

## Why?

Just for fun and to learn protobuf and sockets in Python.

## Installation

```console
python3 -m pipx install git+https://github.com/aarongorka/esphome_emulator.git
esphome_emulator install # or alternatively, set up the systemd service yourself
systemctl daemon-reload --user && systemctl enable --user --now esphome_emulator
```

## Limitations

  * ~No encryption~
  * ~No authentication~
  * ~No discovery~
  * ~Doesn't handle multiple clients~
  * ~Doesn't integrate with ESPHome dashboard/server, only Home Assistant~
  * ~Only implements sending of sensor data~
  * Limited sensor implementation
  * Spaghetti codebase
