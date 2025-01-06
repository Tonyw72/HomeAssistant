# My Energy Dashboard <!-- omit from toc -->

- [Introduction](#introduction)
- [YAML Files](#yaml-files)
	- [Automation](#automation)
	- [Customize](#customize)
	- [Sensors](#sensors)
	- [Template](#template)
	- [Triggers](#triggers)
	- [Utility](#utility)
- [Lovelace Dashboards](#lovelace-dashboards)
- [Final Thoughts](#final-thoughts)

# Introduction
I wanted to make this dashboard as easy to update as possible, so I started with [ccpk1's repo Home-Assistant-Energy-Management](https://github.com/ccpk1/Home-Assistant-Energy-Management)

I [split the configuration](https://www.home-assistant.io/docs/configuration/splitting_configuration/) using the *include_dir_merge_named* method


![File list](./../../images/energy_filelist.png)

Rather than using magic strings and searching through the entity names like Chad (ccpk1) did, I opted to use [Labels](https://www.home-assistant.io/docs/organizing/#labels) to build the [groups](https://www.home-assistant.io/integrations/group/) dynamically.

# YAML Files
## Automation

This is where I dynamically build the groups.

Using a macro in jinja
```

```


## Customize
This is no longer needed, since I switched to using the ***unique_id*** in the template sensors, and will be removed at a later date.

## Sensors
Apparently the was a change in the HomeAssistant code that removed the necessity of configuring the  *Integration Sensors* so the *energy-sensors.yaml* file has been commented out, to be removed at a later date.

## Template

## Triggers

## Utility

# Lovelace Dashboards

# Final Thoughts