# darktx

Current support is only for MacOS. Future versions will allow one to go dark on MacOS, Windows, and Linux.

## Usage

```

darktx - Kill your transmissions quickly

Usage: darktx [OPTION]

 OPTIONS:

  -o | --on      Turn on all network services
  -x | --off     Turn off all network services
  -h | --help    Displays this information

```

## MacOS Commands

**Note:** All of the following commands must be executed as `sudo`

```

# List All Network Services

networksetup -listallnetworkservices


# Switch Apple USB Ethernet Adapter On/Off

networksetup -setnetworkserviceenabled "Apple USB Ethernet Adapter" on | off


# Switch Wi-fi On/Off

sudo networksetup -setnetworkserviceenabled "Wi-Fi" off


```

