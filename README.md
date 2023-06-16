# swr_mappeR
An interactive map that provides information about stations of SWR
This repository contains code for visualizing railway station data using R and Leaflet. The data includes information about railway stations, their location, managers, and other details.

## Features

- Displays railway stations on an interactive map
- Allows users to select columns to display when a station is clicked
- Colors the stations based on the division they belong to
- Filters the stations based on selected divisions

## Installation

To run the code locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository_url>
install.packages(c("leaflet", "leaflet.extras", "shiny"))
library(shiny)
runApp("app.R")
## Usage
The map displays all the railway stations as colored dots.
Click on a station to view its details in the table.
Use the dropdown to select the columns you want to display in the table.
Use the checkbox to filter stations by division.
## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
