This file is a mapping between the FDF Excel file and the config in GitHub.


## 6_field_config

To the sheet `6_field_config` corresponds mainly the file `submissions_rules.csv`.

From the Excel we copy the data to the csv file for the following fields:
```
field_name;type;thematic_group;traffic_light_name;chart_id;chart_data;display_condition;computed_rule;list_name
```

We also need to edit the file `field_label.csv` where we map the field name with the labels in English.
The labels are in the sheet `6_field_config` in the column `Field label in english`.
For the labels in other languages, see in the sheet `7_field_translation_option`.

## 4_traffic_light_config

To the sheet `4_traffic_light_config` corresponds the file `traffic_light_config.json`.
The name of the traffic light has been defined in `submissions_rules.csv`.

From the info provided in the sheet `4_traffic_light_config`, add/update the traffic light in `traffic_light_config.json`.


## Labels choices

The labels for the values are in the sheet `8_list_of_choices_option` (English and translation).
The name and labels from that sheets have to be copied in the sheet `Translation` of the Google Sheet.