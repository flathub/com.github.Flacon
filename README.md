# com.github.Flacon

## Main website
https://flacon.github.io/

## Main project
https://github.com/flacon/flacon

## Flatpak specific details
Flacon only has access to ~/Downloads/ and ~/Music/ by default. If you have music CDs in other locations, then you'll have to adjust Flatpak permissions accordingly:
```
flatpak override com.github.Flacon --user --filesystem=/OTHER/LOCATION/WITH/MUSIC
```
