# NetMapper
Using NetworkX, SNMP and flask to build a network mapping application that can either scan through ranges blindly or use SNMP to pull valid routes.

## Overview:
Netmapper is intended to be a python based application with a flask front end, that can run as a microservice with an API or web interface. In the back end it uses mysql for data and config storage. Visualisations are provided by Plotly.

## Components:
- Flask - User Interface and RESTful API
- MySQL - Config and data storage
- NetworkX - Network mapping and graph creation
- Nmap - Node scanning
- Pysnmp - SNMP polling
- Python - Programming language
- Plotly - Visualisation of graph information

## Use Cases
1. NetMapper is provided with a single or multiple ranges

2. NetMapper is provided with a seed router and SNMP information

3. NetMapper is provided with a spreadsheet of nodes
