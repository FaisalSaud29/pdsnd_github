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

## Contributing

We welcome contributions to improve the US Bikeshare Data Analysis Program! Here's how you can help:

### Getting Started

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Test your changes thoroughly
5. Commit your changes (`git commit -am 'Add new feature'`)
6. Push to the branch (`git push origin feature/improvement`)
7. Create a Pull Request

### Areas for Contribution

#### Beginner-Friendly Issues

- Improving documentation and comments
- Adding input validation
- Enhancing error messages
- Writing test cases
- Adding data sanitation checks

#### Intermediate Features

- Creating data visualizations
- Adding export functionality for analysis results
- Implementing additional statistical analyses
- Creating a command-line interface
- Adding support for different date ranges

#### Advanced Improvements

- Building a web interface
- Adding real-time data processing capabilities
- Implementing database integration
- Creating data caching mechanisms
- Adding machine learning predictions for bike usage

### Code Style

- Follow PEP 8 guidelines
- Include docstrings for new functions
- Add comments for complex logic
- Maintain consistent naming conventions

### Testing

- Add unit tests for new features
- Ensure existing tests pass
- Include edge cases in test scenarios
- Test across different Python versions

### Reporting Issues

- Use the issue tracker to report bugs
- Include detailed steps to reproduce issues
- Add screenshots if applicable
- Specify your operating system and Python version

### Code Review Process

1. All contributions require a pull request
2. Maintainers will review your code
3. Address any requested changes
4. Once approved, your code will be merged

### Questions or Suggestions?

Feel free to open an issue for:

- Feature requests
- Bug reports
- Documentation improvements
- General questions

We appreciate your interest in improving this project!
