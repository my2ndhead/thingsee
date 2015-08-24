# Thingsee App for Splunk

- **Authors**:          Mika Borner <mika.borner@gmail.com>
- **Description**:      Thingsee App for Splunk
- **Version**:          1.0.0

## Introduction
The Thingsee App for Splunk collects all Thingsee One metrics and presents them on dashboards.

## Installation

- Install Splunk >=6.2 
- Install https://splunkbase.splunk.com/app/1901/
- Download the Thingsee Technology Add-On from https://github.com/my2ndhead/TA-thingsee/archive/master.zip
- Unzip the master.zip to $SPLUNK_HOME/apps
- Rename thingsee-master to thingsee (GitHub adds "-master" suffix, we don't want that)
- Download the Thingsee App from https://github.com/my2ndhead/thingsee/archive/master.zip
- Rename TA-thingsee-master to TA-thingsee (GitHub adds a "-master" suffix, we don't want that)
- Restart Splunk
- Login to Splunk and go to Setting -> Data inputs -> Protocol Data Inputs
- Enable and/or adjust the thingsee input. By default, Splunk will listen to Port 8079/tcp
- Under Thingsee Creator, select your purpose, and enable the action to send events to the custom cloud URL. e.g. http://mysplunkserver.com:8079
- Now you should see the dashboards filling up in the Splunk Thingsee App
- Happy Splunking !

## Release Notes
- **v1.0.0**    /       2015-08-24
        - First Release   

## Limitations

- Currently only one Thingsee One device can be monitored.

## License

Thingsee App for Splunk and Technology Add-On for Thingsee are licensed under CC BY-NC-SA 4.0 http://creativecommons.org/licenses/by-nc-sa/4.0/
