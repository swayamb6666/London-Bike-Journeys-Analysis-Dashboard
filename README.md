# London Bike Journeys Dashboard

## Overview

This project is a comprehensive data visualization dashboard analyzing London's bike-sharing system usage patterns during August 2023. The dashboard provides detailed insights into user behavior, station popularity, journey trends, and bike model preferences, enabling stakeholders to understand commuting patterns and optimize bike-sharing operations.

## Key Metrics

- **Total Journeys**: 776,527 trips completed in August 2023
- **Average Journey Duration**: 26 minutes
- **Unique Stations**: 800 stations utilized
- **Unique Bikes**: 11,866 bikes in circulation
- **E-Bike Journeys**: 59,888 trips (7.7% of total)

## Features

### Dashboard Pages

**Page 1: August 2023 Summary**
- Total journeys and key performance indicators at a glance
- Daily trend visualization showing usage patterns throughout the month
- Peak hours analysis highlighting 2:00 PM and 3:00 PM as busiest times
- Top start and end stations (Hyde Park Corner and Waterloo Station dominate)
- Bike model split showing 92.3% classic bikes vs 7.7% e-bikes

**Page 2: Station & Duration Analysis**
- Interactive map displaying station locations globally
- Day of week trend analysis (higher usage mid-week)
- Average journey duration by starting station
- Total journeys by route analysis
- Top 5 routes ranked by ride count:
  - Albert Gate, Hyde Park → Albert Gate, Hyde Park (1,227 journeys)
  - Black Lion Gate, Kensington Gardens → Black Lion Gate, Kensington Gardens (1,343 journeys)
  - Hyde Park Corner → Hyde Park Corner (2,966 journeys)
  - Podium, Queen Elizabeth Olympic Park → Podium, Queen Elizabeth Olympic Park (1,813 journeys)
  - Triangle Car Park, Hyde Park → Triangle Car Park, Hyde Park (1,391 journeys)

## Key Insights

- **Peak Usage**: Wednesday, Thursday, and Tuesday show the highest demand with over 100K journeys each
- **Station Concentration**: Hyde Park and its surrounding stations are the primary hubs for bike rentals
- **Journey Duration**: Varies significantly by starting station, with Lesham Gardens averaging the longest trips (150+ minutes)
- **E-Bike Adoption**: E-bikes represent a smaller portion of usage, suggesting lower adoption rates among commuters
- **Time-Based Patterns**: Clear peak hours in early afternoon indicate leisure and post-lunch commute activities

## Technologies Used

- **Data Visualization**: Power BI
- **Data Transformation**: Power Query
- **Data Modeling & Calculations**: DAX (Data Analysis Expressions)
- **Data Source**: Transport for London (TfL) Open Data

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/london-bike-journeys.git
   ```

2. Navigate to the project directory:
   ```bash
   cd london-bike-journeys
   ```

3. If using a specific tool or framework, install dependencies:
   ```bash
   npm install
   # or
   pip install -r requirements.txt
   ```

4. Open the dashboard file in your preferred tool or start the local server:
   ```bash
   npm start
   # or open index.html in your browser
   ```

## Dataset

- **Time Period**: August 2023
- **Source**: Transport for London (TfL) Open Data
- **Records**: 776,527 bike journey records
- **Attributes**: Journey ID, Start Station, End Station, Start Time, End Time, Bike ID, User Type, etc.
- **Data Format**: CSV/JSON (specify your format)

## File Structure

```
london-bike-journeys/
├── README.md
├── data/
│   └── august_2023_journeys.csv
├── dashboards/
│   ├── page1_summary.html
│   ├── page2_analysis.html
│   └── styles/
│       └── dashboard.css
├── analysis/
│   └── data_processing.py
└── images/
    ├── dashboard_page1.png
    ├── dashboard_page2.png
```

## Usage

1. Open the dashboard files in your web browser or visualization tool
2. Use the interactive filters to explore specific stations or bike models
3. Hover over charts to view detailed information
4. Download filtered data using the export buttons (if available)

## Visualizations Included

- **Time Series Chart**: Daily journey trends
- **Bar Charts**: Top stations, routes, and average durations
- **Pie Chart**: Bike model distribution
- **Heat Maps**: Peak hours and day-of-week patterns
- **Interactive Map**: Geographic station distribution

## Limitations & Future Improvements

### Current Limitations
- Analysis limited to August 2023 data only
- Doesn't include weather or external event data that may influence usage
- Missing demographic information about users

### Planned Enhancements
- Extend analysis to multiple months for seasonal trends
- Incorporate weather data for correlation analysis
- Add user demographic insights
- Implement real-time data updates
- Create predictive models for demand forecasting
- Add station capacity and availability tracking

## Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Data Attribution

This dashboard utilizes open data from Transport for London (TfL). The original dataset is available at [TfL Open Data](https://tfl.gov.uk/corporate/publications-and-reports/open-data).

## Contact & Support

- **Author**: [Your Name]
- **Email**: [your.email@example.com]
- **GitHub**: [@yourusername](https://github.com/yourusername)

For questions or issues, please open an issue on the GitHub repository.

## Acknowledgments

- Transport for London for providing the open dataset
- Data visualization community for tools and best practices
- [Any other collaborators or resources you'd like to credit]
