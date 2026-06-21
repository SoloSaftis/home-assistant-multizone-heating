# Troubleshooting

* **Entity unavailable:** verify its exact ID in Developer Tools → States.
* **Duplicate top-level YAML key:** merge sections instead of adding a second `template:`, `input_boolean:` or `input_select:` block.
* **Force Home still shows 15 °C:** confirm zone automations use `binary_sensor.heating_away_mode_active`, not the raw physical-away sensor.
* **Dashboard is blank:** check the base URL, token and browser console.
* **Window lockout reversed:** verify whether your contact reports `on` when open.
