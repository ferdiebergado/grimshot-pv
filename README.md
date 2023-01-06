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
echo -e "active\nscreen\noutput\narea\nwindow" | bemenu | xargs -r grimshot --notify save
```
