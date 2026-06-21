# Entity worksheet

Open **Home Assistant → Developer Tools → States** and copy the exact entity IDs. Do not guess them.

## Whole-home entities

```text
Presence tracker: person.resident
Heating mode helper: input_select.heating_presence_mode
Away tracking boolean: input_boolean.resident_away_tracking_active
Departure timestamp: input_datetime.resident_left_home
```

## Repeat for every zone

```text
Zone name:
Floor/group:
Climate entity or entities:
Primary temperature sensor:
Additional temperature sensors:
Door/window contacts:
Morning helper:
Midday helper:
Evening helper:
Night helper:
Manual lockout helper:
Automatic lockout helper, if used:
Floor-temperature sensor, if used:
Desired away temperature:
Special behavior or limits:
```

Use the **filter entities** field in Developer Tools to search for `climate.`, `sensor.`, `binary_sensor.`, `input_number.`, `input_boolean.` and `person.`.
