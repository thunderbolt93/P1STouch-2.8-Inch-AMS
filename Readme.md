

TODO- Proper readme

Changes from original version:
- Show which color is in which slot (AMS or External) and which slot is currently loaded
- Fetch current time and Show ETA (currently german timezone, can be changed via timezones.json in SDcard Root, https://github.com/nayarsystems/posix_tz_db/blob/master/zones.csv)
- Fix bug when switchting to and from printer control screen
- Check machine homing before doing manual movements
- Show Filament type in AMS slots an enable Load/Unload of AMS slots (currelty only for 5" version)
- Enable AndroidOTA for firmware-updates via WiFi

based on the excellent work of
https://github.com/xperiments-in/xtouch/forks

Example Timezones file:

```
{
  "ntp_server":"de.pool.ntp.org",
  "timezone":"CET-1CEST,M3.5.0,M10.5.0/3",
  "12hFormat":0
}
```