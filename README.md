# 96well_platefiller_orAnyPlateSize
A simple plate filler script that takes any vector and converts it into a 96-, 72-, and 384-well plate


## Script Overview
This R script distributes biological or chemical data across multiple well plate formats (96-well, 72-well, and 384-well), facilitates their organization, and exports the setup to CSV files. It is ideal for laboratory environments where data accuracy and plate configuration are critical.

This script allows you to import a list of sample names or a list of names in .csv, and it fills plates (96-well, 72-well, and 384-well) from A1 to B1 to C1... Helpful experimental planning saves time copying and pasting and is more accurate

## Features
Supports Multiple Plate Sizes: Configures and handles 96-well, 72-well, and 384-well plates.
Automated Data Distribution: Automatically fills wells based on the input data sequence.
CSV Output: Exports plate configurations into individual CSV files for each plate type.

## Functionality
Load Data: Load data that is arranged row-wise. Sample 1 = row 1, Sample 2 = row 2...
Initialize Plates: Sets up different plate types with specific row and column configurations.
Data Assignment: Distributes data sequentially across the wells of each plate.
Export Results: Saves the filled plate layouts to CSV files, maintaining the format and data integrity.
