# terminal-programs

Mostly terminal eyecandy programs @w@

---

## aplayloop

Play a file in an infinite loop

### Usage

Just run the program like aplay:

```
aplayloop file.wav
```

Use **Ctrl + Z** to exit

---

## backlight

Change the backlight brightness

### Usage

By just running:

```
backlight
```

it sets the backlight brightness to 255

By passing a number between 0-255 you set the backlight brightness accordingly

**\-\-get** to get the backlight brightness

---

## clock

timedatectl but for non-systemd systems

### Usage

```
clock
```

**-c/\-\-color** to change the output color. Colors: blue, cyan, green, purple, red, yellow (default: blue)

**-f/\-\-format** to change the time format in [strftime](https://strftime.org) (default: %A %Y-%m-%d %H:%M:%S)

**-r/\-\-refresh** to change the refresh time in seconds, giving this a lower value will minimise the time offset between prints, one second will introduce some offset but is a good middle ground between time offset and performance (default: 1)
