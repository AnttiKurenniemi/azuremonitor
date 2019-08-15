# Azuremonitor
This repository contains some handy queries for Azure Monitor; things that I've found useful myself.

## Files in this repo

### DiskSizeFree

This query renders a chart displaying free disk size, for all disks. Relatively simple and easy to modify, for example add a specific computer to monitor, if you have monitoring agents in multiple computers.

Requires **LogicalDisk/Free Megabytes** performance counter to be monitored.
