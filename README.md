# RFID Dashboard for Power Plant Access

This repository contains the source code for the RFID Dashboard used to monitor and manage RFID-based access control for people entering the Urja Thermal Power Plant. The dashboard displays real-time RFID data, such as who has entered or exited the facility, providing security and operational oversight.

The dashboard is designed to be lightweight and easy to integrate with the RFID readers used at the plant's entry points.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Clone the Repository](#clone-the-repository)
  - [Open the Dashboard](#open-the-dashboard)
- [Usage](#usage)
- [Key Features](#key-features)
- [License](#license)
- [Contact](#contact)

## Overview

The RFID Dashboard provides a simple interface to display and monitor access logs of individuals entering or exiting the power plant using RFID tags. It receives data from the RFID readers located at the plant’s entrance, showing real-time status of entries and exits.

This system helps improve security and ensures that only authorized personnel are allowed to enter the facility. The dashboard is designed to be used by security staff, allowing them to easily track who is inside the power plant at any given time.

## Features
- **Real-Time Entry Logs**: Displays live records of who is entering or exiting the facility.
- **Visitor Tracking**: Monitor the RFID tags of authorized personnel and contractors.
- **Simple Interface**: Easy-to-use dashboard built using HTML, CSS.
- **Data Logging**: Keep track of entry and exit times for security and reporting purposes.
- **Security Alerts**: Alert security if unauthorized access attempts are detected.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **RFID Integration**: Integration with RFID reader data via API or directly from hardware.
- **Visualization**: Real-time logs and tables for displaying access data

## Installation

### Prerequisites
This dashboard is a web application. You’ll need the following:

- A web browser (Google Chrome, Firefox, Safari, etc.)
- An RFID reader that outputs entry/exit logs (either via API or directly into a file)

### Clone the Repository
Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/urjathermal/rfid.git
cd rfid
```
### Open the Dashboard
Simply open the index.html file in a web browser to access the dashboard:

```bash
open index.html
```
Alternatively, you can host the HTML files on any local or remote web server if needed.

## Usage
Once the dashboard is open in your browser, you’ll be able to view the real-time logs of RFID entries and exits. The system works by displaying who entered the facility, the time of entry, and whether the individual is authorized.

## Key Features:
- **Access Log Display**: View a list of all RFID entries and exits.
- **Live Updates**: The dashboard can be updated in real-time (using JavaScript or WebSocket for live data).
- **Search and Filter**: Easily search for specific RFID tags or individuals and filter by time or status.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code under the terms of the license.

## Contact
For any questions or support, feel free to reach out:

- **GitHub Repository**: https://github.com/urjathermal/rfid
- **Email**: contact@urjathermal.com

  
