# Data Guide

The assignment uses one dataset: `data`. (The `palmer_penguin_species.tsv` file in the same folder came with Activity 7 and is not used.)

## Consumer Reports Cars, 1990 (`car_sample_data.csv`)

This data comes from *Consumer Reports* (April 1990). Each row is one car model sold in the US in 1990, and prices are in 1990 US dollars.

**Shape:** 60 rows × 9 columns, comma-separated, with a header row. Load it with `d3.csv`, as the starter already does.

| Column | Meaning | Used in the assignment |
|---|---|---|
| `Model` | Make, model and engine | Shown in the list (Part 3) |
| `Price` | Price in USD (1990) | x-axis, plot 1 |
| `Country` | Country of origin (USA, Japan, Korea, Germany, France, Mexico, Sweden) | Colour and legend (Part 5) |
| `Reliability` | 1 (worst) to 5 (best), `NA` if missing | Not used |
| `MPG` | Fuel economy, miles per gallon | y-axis, both plots |
| `Type` | Small, Sporty, Compact, Medium, Large, Van | Shown in the list (Part 3) |
| `Weight` | Weight in pounds | Circle size, both plots |
| `EngineSizeCI` | Engine size in cubic inches | x-axis, plot 2 (Part 1) |
| `HP` | Horsepower | Not used |

**Note:** `d3.csv` reads every value as a string. The starter's brush code converts values with `+d[xCol]`, so you do not need to convert them yourself.
