---
title: Schlage
description: Instructions on how to integrate Schlage WiFi smart locks into Home Assistant.
ha_category:
  - Lock
  - Sensor
  - Switch
ha_release: 2023.9
ha_iot_class: Cloud Polling
ha_config_flow: true
ha_codeowners:
  - '@dknowles2'
ha_platforms:
  - lock
  - sensor
  - switch
ha_integration_type: integration
---

The Schlage integration provides connectivity with Schlage WiFi smart locks through Schlage's cloud API.

{% include integrations/config_flow.md %}

There is currently support for the following device types within Home Assistant:

- Lock
- Sensor
- Switch

## Sensor

Once you have enabled the Schlage integration, you should see the following sensors:

- Lock Battery

## Switch

Once you have enabled the Schlage integration, you should see the following switches:

- **1-Touch Locking** - When enabled, locks the lock with a press of the Schlage button.
- **Keypress Beep** - Controls whether the lock will emit beeping tones on use.
