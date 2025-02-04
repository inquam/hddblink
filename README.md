# hddblink
A small shell script used to make the activity led of a drive blink so you can identify it in a chassi with multiple drive bays. The script requires smartmontools

## Installation

Copy the file

```cp hddblink /usr/sbin/hddblink```

Make it executable

```chmod  +x /usr/sbin/hddblink```

## Usage

```hddblind /dev/sda```

The activity light associated with the device will blink once every second.

## How to install smartmontools

### Ubuntu/Debian-based systems
Run the following command to install `smartmontools`:
```bash
sudo apt update && sudo apt install smartmontools
```

### RHEL/CentOS/Fedora
For RHEL/CentOS:
```bash
sudo yum install smartmontools
```
For Fedora:
```bash
sudo dnf install smartmontools
```

### Arch Linux
Install using the package manager:
```bash
sudo pacman -S smartmontools
```
