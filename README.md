# BatteryDan
![](logo.png)

A simple script to display the battery status for your Mac.

## Setup
To install:

```shell
git clone git://github.com/heliomass/BatteryDan.git
```

## Usage
To see the full range of commands:

```shell
battery_dan --help
```

Basic invocation:

```shell
$ battery_dan
◉ 96%
```

If you want to round up to 100% when your Mac is plugged in and almost charged:

```shell
$ battery_dan --round_up
◉ 100%
```