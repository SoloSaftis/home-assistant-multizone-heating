# Manual customization

1. Merge `snippets/shared_helpers.yaml` into `configuration.yaml`. If a top-level key already exists, merge its children instead of declaring the key twice.
2. Replace `person.resident` with your tracker from **Developer Tools → States**.
3. Add `automations/presence_away_tracking.example.yaml` to your automations.
4. Copy the closest zone example and replace every `example_zone` entity with real entities from your worksheet.
5. Create four `input_number` helpers per zone for morning, midday, evening and night.
6. Add each customized zone to the dashboard `zones` array.
7. Run **Developer Tools → YAML → Check configuration** before restarting.
8. Test one zone, one window contact and all three presence modes before enabling the rest.
