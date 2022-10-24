---
title: Data Import
description: How to clean, transform, and import your data into EARLY
---

All the code needed to handle your data is on Replit. Just go [here](https://replit.com/@nmandal/early-import?v=1), and near the right you'll see the "Fork" button. Be sure you're logged in, then click this.

Organize your downloaded data into the following structure for all relevant data types

```
data/
    /health/
        /Export_Aggregated_2022-10-01_2022-10-24.csv
        /Export_Records_Vo2Max_2022-10-01_2022-10-24.csv
    /oura/
        /oura_2022-10-10_2022-10-24_trends.csv
    /workouts/
        /Export_Workouts_2022-09-24_2022-10-24.csv
    /levels/
        /logs_data.csv
    /misc/
        /misc.csv
```

Upload the `data` directory to Replit and hit `Run`.

After a successful run you will have a directory structure like:

```
out/
    /health
        /W
            /...
            /story.txt
        /M
            /...
            /story.txt
        /Q
            /...
            /story.txt
        /Y
            /...
            /story.txt
        master.csv
    /oura
        /W
            /...
            /story.txt
        /M
            /...
            /story.txt
        /Q
            /...
            /story.txt
        /Y
            /...
            /story.txt
        master.csv
    /workouts
        /W
            /...
            /story.txt
        /M
            /...
            /story.txt
        /Q
            /...
            /story.txt
        /Y
            /...
            /story.txt
        master.csv
    /levels
        /W
            /...
            /story.txt
        /M
            /...
            /story.txt
        /Q
            /...
            /story.txt
        /Y
            /...
            /story.txt
        master.csv
    /misc
        /W
            /...
            /story.txt
        /M
            /...
            /story.txt
        /Q
            /...
            /story.txt
        /Y
            /...
            /story.txt
        master.csv
```

You can then dowload the files as a ZIP and have the files you need to upload to EARLY.

## Upload to EARLY

- https://earlydao.vercel.app/import
  - Select correct data source
  - drop CSV
  - If there is issues, use smaller file
