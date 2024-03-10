## Data Acquisition from STM32F407VGT6 Sensors

This project focuses on acquiring data from temperature, humidity, and gas sensors connected to an STM32F407VGT6 microcontroller. The acquired data is then displayed on a custom chart and tables on a website.

### HTML Structure

The HTML file (`index.html`) includes Bootstrap for styling, ECharts for chart visualization, and Tabulator for table functionality. It contains sections for displaying charts and tables.

### JavaScript Files

- **chart.js**: Contains the script for the main chart, which visualizes temperature data.
- **chart2.js**: Contains the script for the second chart, which visualizes humidity data.
- **chart3.js**: Contains the script for the third chart, which visualizes gas sensor data.
- **tables.js**: Contains scripts for generating tables to display the acquired data.

### Usage

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Ensure that the necessary libraries are properly linked.
4. The charts and tables should be populated with data acquired from the STM32F407VGT6 sensors.

### Note

- Make sure to have the JSON data files (`parsedData.json`, `parsedData1.json`, `parsedData2.json`) available and correctly referenced in the JavaScript files.
- Customize the styling and layout of the HTML file as needed.
- Ensure that the paths to JavaScript files are correctly set within the HTML file.

### Contributors

- [Your Name]
- [Contributor 2]
- [Contributor 3]

### License

[MIT License ]
