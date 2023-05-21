# Home Assistant Config and Blueprints
Some basic but hopefully helpful config that I use with Home Assistant
for home automation tasks.

## Usage
All code here is free to use in any way. No gaurantees or warranty
is provided for any content and you use it at your own risk.

Much of this is built on the work of many others.

## Blueprints

### Schedule Reminders to iOS App
Built from the excellent medication_reminder_ios by Aohzan.

Create two Helpers, one Schedule and one Boolean then use the blueprint
to create an automation that will send you a notification on your iOS
device when the schedule goes from "off" to "on" state.

A long press on the iOS notification will then provide options to update
the automation state including new reminders. A "done" action will
update the boolean helper that can be used for additional triggers 
and state tracking.