# grimshot-pv

Fork of swaywm's grimshot script with added screenshot preview on the notification

## REQUIREMENTS

- imagemagick

## USAGE

### Standalone

```bash
grimshot --notify save|copy active|screen|output|area|window
```

### With demenu/bemenu

```bash
echo -e "active\nscreen\noutput\narea\nwindow" | bemenu -p '   Select region:' --tf \#0ffff0 --hb \#0ffff0 --hf \#000000 | xargs -r ~/Scripts/grimshot --notify save
```
