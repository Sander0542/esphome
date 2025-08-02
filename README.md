# ESPHome
ESPHome configurations

## Development

### Local

Configure a Python Virtual Environment and activate

```python
python -m venv .venv
```

Install ESPHome

```shell
pip install esphome
```

Run run the ESPHome configuration to the device

```shell
esphome run --device COM5 ESP32-S3-4848S040/device.yaml
```
