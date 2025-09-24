# Updating reading schedule

Due to the historical reasons, the reading schedule is generated from CSV files... Which are generated via Python scripts you can find in this folder.

Hugo has seemingly changes some of its routines since 0.6.X which was used to create this website to 0.150.X which is currently in use. To accommodate these, the actual files located here:

```
assets/
├── data
│   ├── reading2021
│   │   └── reading_group_schedule_2021.csv
│   ├── reading2022
│   │   └── reading_group_schedule_2022.csv
│   ├── reading2023
│   │   └── reading_group_schedule_2023.csv
│   └── reading2024
│       └── reading_group_schedule_2024.csv
└── reading
    └── reading_group_schedule.csv
```

...and `reading_group_schedule.csv` is symlinked under `/content/reading/` (this folder) as it's where it used to reside traditionally. You can edit either and the changes will be reflected in the build.
