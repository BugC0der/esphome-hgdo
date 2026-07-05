# esphome-hgdo

## Prerequisites
```bash
pip install esphome
```

## Compile & Upload (USB)
Connect via USB. Use `--device` to specify your serial port:

* **Windows:** `esphome run esphome-hgdo.yaml --device COM3`
* **Linux/macOS:** `esphome run esphome-hgdo.yaml --device /dev/ttyUSB0`

*(Tip: Find your exact port in Device Manager or via `ls /dev/tty*`)*

## Compile & Upload (OTA)
```bash
esphome run esphome-hgdo.yaml --device 192.168.1.50
```

## Separate Commands
* **Compile only:** `esphome compile esphome-hgdo.yaml`
* **Upload only (USB):** `esphome upload esphome-hgdo.yaml --device COM3`
* **Upload only (OTA):** `esphome upload esphome-hgdo.yaml --device 192.168.1.50`
