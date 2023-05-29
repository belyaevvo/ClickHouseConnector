# Power BI ClickHouseConnector

This project allows Power BI to connect and query data from ClickHouse in DirectQuery mode.

Without custom connector, you can only import data from ClickHouse to Power BI using ODBC driver. This is impossible to DirectQuery ClickHouse database.

# Install
Download and install ClickHouse ODBC driver from https://github.com/ClickHouse/clickhouse-odbc

Create a [Documents]\Power BI Desktop\Custom Connectors directory.

Download ClickHouseConnector.mez and place it in that directory.

Open Power BI Desktop and enable loading unsigned connectors (File > Options and settings > Options > Security > Data Extensions > Allow any extension to load without warning or validation)

Restart Power BI Desktop

Read the PBI documentation if you have any trouble.
