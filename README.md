# esphome-hgdo

## Prerequisites
```bash
pip install esphome
```

## Compile & Upload (USB)
Connect your device via USB, then run:
```bash
esphome run esphome-hgdo.yaml
```

## Compile & Upload (OTA)
If the device is already connected to your network:
```bash
esphome run esphome-hgdo.yaml --device <IP_ADDRESS>
```

## Separate Commands
If you need to split the process:
* **Compile only:** `esphome compile esphome-hgdo.yaml`
* **Upload only:** `esphome upload esphome-hgdo.yaml`
