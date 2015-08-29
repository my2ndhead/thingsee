# Thingsee App for Splunk

- **Authors**:          Mika Borner <mika.borner@gmail.com>
- **Description**:      Thingsee App for Splunk
- **Version**:          1.2.0

## Introduction
The Thingsee App for Splunk collects all Thingsee One metrics and presents them on dashboards.

## Installation

- Install Splunk >=6.2 
- Install Protocol Modular Input from  https://splunkbase.splunk.com/app/1901/
- Install TA-thingsee from https://splunkbase.splunk.com/app/2853/
- Install Thingsee App from https://splunkbase.splunk.com/app/2854/
- Restart Splunk
- Login to Splunk and go to Setting -> Data inputs -> Protocol Data Inputs
- Enable and/or adjust the thingsee input. By default, Splunk will listen to Port 8079/tcp
- Under Thingsee Creator, select your purpose, and enable the action to send events to the custom cloud URL. e.g. http://mysplunkserver.com:8079
- Now you should see the dashboards filling up in the Splunk Thingsee App
- Happy Splunking !

## Release Notes
- **v1.0.0**    /       2015-08-24
        - First Release   

- **v1.1.0**   /        2015-08-27
        - Second Release

- **v1.2.0**   /	2015-08-29
        - Third Release


## Changelog

- **v1.1.0**  
	- More of everything
	- More charts for more sensor data
        - Changed energy dashboard
        - Removed auto-refresh from panels
        - Minor bug fixes and improvements

- ** v1.2.0**
	- Use of optimized field extractions
	- Menu restructured
	- Added First Use Cases incl. configuraton docs
        - Datamodel added for Pivot
        - Minor bug fixes and improvements

## Limitations

- Currently only one Thingsee One device can be monitored.

## License

Thingsee App for Splunk and Technology Add-On for Thingsee are licensed under CC BY-NC-SA 4.0 http://creativecommons.org/licenses/by-nc-sa/4.0/
