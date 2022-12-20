---
title: Data Import
description: How to clean, transform, and import your data into EARLY
---

All the code needed to transform your data is on Replit. Just go [here](https://replit.com/@nmandal/EARLY-data-import?v=1), and near the right you'll see the "Fork" button. Be sure you're logged in, then click this.

Your data should be organized in the following structure for all relevant data types:

```
data/
    health/
        Export_Aggregated_2022-10-01_2022-10-24.csv
        Export_Records_Vo2Max_2022-10-01_2022-10-24.csv
    oura/
        oura_2022-10-10_2022-10-24_trends.csv
    workouts/
        Export_Workouts_2022-09-24_2022-10-24.csv
    levels/
        /logs_data.csv
    misc/
        misc.csv
```

Upload your `data` directory to Replit and hit `Run`.

After a successful run you will have a directory structure like:

```
out/
    health/
        W/
            /...
            /story.txt
        M/
            /...
            /story.txt
        Q/
            /...
            /story.txt
        Y/
            /...
            /story.txt
        master.csv
    oura/
        W/
            /...
            /story.txt
        M/
            /...
            /story.txt
        Q/
            /...
            /story.txt
        Y/
            /...
            /story.txt
        master.csv
    workouts/
        W/
            /...
            /story.txt
        M/
            /...
            /story.txt
        Q/
            /...
            /story.txt
        Y/
            /...
            /story.txt
        master.csv
    levels/
        W/
            /...
            /story.txt
        M/
            /...
            /story.txt
        Q/
            /...
            /story.txt
        Y/
            /...
            /story.txt
        master.csv
    misc/
        W/
            /...
            /story.txt
        M/
            /...
            /story.txt
        Q/
            /...
            /story.txt
        Y/
            /...
            /story.txt
        master.csv
```

You can then dowload the files as a ZIP and have the files you need to upload to EARLY. Alternatively, you can create a GitHub repository with your data to keep track of your versioned data over time.

## Upload to EARLY

- Go to [https://beearly.xyz/import](https://beearly.xyz/import)

- Select correct data source (Oura, Apple Workouts, Apple Health, Levels, Misc)

- Select CSV file

- If there is issues, use smaller file and try again
