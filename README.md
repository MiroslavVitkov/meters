# meters
Text mode taskbar. Intended for tiling managers.

Each field is enabled/disabled by (un)commenting it's invocation in the end of the file.

Fields implemented this far:
- clock - depends on locale
- laptop battery - features visual alarm when low
- laptop screen brightness
- output volume at the ALSA level
- load averages for the past 1, 5, and 15 minutes
- CPU temperature
- amount of unused(even for caching) RAM
- bluetooth device battery level - requires action: see the comment on print_blue_bat(), auto hides
