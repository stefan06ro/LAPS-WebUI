# LAPS-WebUI
A nice and simple Web Interface for LAPS (Local Administrator Password Solution)

## Setup Preqesites

- A working Active Directory with Microsoft LAPS installed
- A .NET Core compatible Host (Linux or Windows)

## Setup:

- Download the latest Release for your Platform
- Unzip Archive
- Copy `settings.json.example` and renamed it to `settings.json`
- Adjust settings.json and run LAPS WebUI

## Usage:
- Navigate with your WebBrowser to the LAPS WebUI Page (Default: http://127.0.0.1:8080 )
- Login with any Active Directory User which can access the LAPS LDAP Properties
- Type any Computername in the Searchbox and click a result to view the LAPS Password.
