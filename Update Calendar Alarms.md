# Update Calendar Alarms

Update Calendar Alarms allows you to turn calendar events into actual alarms. It works by reading your calendar, finding events either created by you or “Accepted” by you (Events RSVP’d Maybe and No are ignored), and creating alarms with a special prefix that the start. It deletes all the existing alarms with that prefix (so alarms created by you will not be affected) and creating new alarms for the found events.

It’s recommended to run this periodically during the day using Shortcut automation, and preferably at times when you will not have any events. If the automation runs exactly at the time when an alarm for an event is about to go off, it may not ring. So the recommended settings are:

- Minutes before: 1
- Automation: 3 minutes before :00, :15, :30 etc (8:27a, 9:27a, 10:27a, 11:27a, 12:27p, 1:27p, 2:27p, 3:27p, 4:27p, 5:27p, 6:27p)

## Download

[Update Calendar Alarms.shortcut](./Update%20Calendar%20Alarms.shortcut)
