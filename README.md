# Synaptics touchpad one finger scrolling

A CLI utility make it possible to scroll with one finger. Execellent combination with ThinkPad TrackPoint.

Unfortunately, not supported under Wayland.

## Prerequisites

- Xorg
- Synaptics input driver
    - `synclient` CLI command

## Getting started

Toggle one/two finger scrolling:

```sh
$ ./synaptics-one-finger -t
```

See help (`-h` option) for more details.

## Configuration

Edit `synaptics-one-finger.conf` directly.
