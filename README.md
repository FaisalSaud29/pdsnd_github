# US Bikeshare Data Analysis Project

## Description

This Python script analyzes bike share system usage data from three major US cities: Chicago, New York City, and Washington. It provides interactive filtering options and displays various statistics about bikeshare usage patterns.

## Features

- Interactive data filtering by:
  - City (Chicago, New York City, Washington)
  - Month (January through June)
  - Day of the week
- Statistical analysis including:
  - Most frequent times of travel (month, day, hour)
  - Popular stations and trip routes
  - Trip duration information
  - User statistics

## Dependencies

- Python 3
- pandas
- numpy
- time

## Data Files Required

The script expects the following CSV files in the same directory:

- chicago.csv
- new_york_city.csv
- washington.csv

## Usage

1. Run the script using Python:

   ```
   python bikeshare.py
   ```

2. Follow the interactive prompts to:
   - Select a city
   - Choose filtering options (month, day, both, or none)
   - View statistical results
   - Optionally view raw data in 5-row increments

## Data Statistics Provided

- Time Statistics:
  - Most common month
  - Most common day of the week
  - Most common start hour

- Station Statistics:
  - Most popular start station
  - Most popular end station
  - Most frequent combination of start and end stations

- Trip Duration Statistics:
  - Total travel time
  - Average travel time

- User Statistics:
  - User type counts
  - Gender distribution (Chicago and NYC only)
  - Birth year statistics (Chicago and NYC only)

## Notes

- Gender and birth year statistics are only available for Chicago and New York City
- Data can be filtered by month (January to June only)
- Day selection is done using integers (1-7)
- Raw data viewing is optional and displayed in 5-row increments

## Error Handling

The script includes input validation to handle:

- Invalid city names
- Invalid filter choices
- Invalid month selections
- Invalid day selections