# Home Automation TODO

## MQTT Scheduler

- Inbound topic handlers for setting/clearing scheduled messages
- Emits MQTT messages at desired timestamp
- Allows for an ID to be set on a scheduled message to be cleared or updated

## RF433 Motion Sensor Network

- Use Sonoff RF Bridge with custom firmware (http://tinkerman.cat/hacking-sonoff-rf-bridge-433/ https://github.com/arendst/Sonoff-Tasmota/wiki/Sonoff-RF-Bridge-433)
- Use cheap RF PIR sensors

## State Modifier Service

- Prevent specific automation tasks while active, eg keep the outdoor lights on while you're outside, but use motion sensors when you're not.
- Expiring states, eg set that you're outside for 2 hours to modify the state of automation behaviour
