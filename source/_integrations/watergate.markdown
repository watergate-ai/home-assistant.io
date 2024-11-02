---
title: Watergate
description: Instructions on how to integrate Watergate within Home Assistant.
ha_category:
  - Sensor
  - Valve
  - Binary Sensor
  - Number
  - Water management
ha_release: '2024.11'
ha_iot_class: Local Push
ha_config_flow: true
ha_codeowners:
  - '@watergate-ai'
ha_domain: watergate
ha_platforms:
  - diagnostics
  - sensor
  - valve
  - binary_sensor
  - number
---

The **Watergate** {% term integration %} integrates your Watergate Devices (currently Sonic) to your Home Assistant.
With this integration you are able to:

- control your valve
- configure auto shut off parameters
- gather auto shut off parameters
- check diagnostics of the device

## Prerequisites

- You need to have Sonic device
- Local API feature must be enabled in application
- Network Traffic between Home Assistant Server and Sonic must be unlocked in both ways.

{% important %}
Go to Watergate application and enable Local API in specific device's settings.
{% endimportant %}

{% include integrations/config_flow.md %}