This is an extension for Drive Badger. It provides `exclude.list` file, containing a list of exclusions compatible with popular `rsync` program.

The purpose of these exclusions is to decrease the amount of data to be exfiltrated by Drive Badger, and thus to speed up the attack,
by eliminating files and directories, that are not valuable in any way to the attacker:

- image/audio/video recording/editing/streaming software - excluding:
   - image/audio/video players (eg. IrfanView, VLC)
   - video codecs (eg. K-Lite)
   - OEM preinstalled software (see https://github.com/drivebadger/exclude-oem repository)
   - Windows Live video editing software (see https://github.com/drivebadger/exclude-windows repository)
   - multimedia files (see https://github.com/drivebadger/exclude-user repository)

### Installing

Clone this repository as `/opt/drivebadger/config/exclude-digital` directory on your Drive Badger persistent partition.

### More information

- [Drive Badger main repository](https://github.com/drivebadger/drivebadger)
- [Drive Badger wiki](https://github.com/drivebadger/drivebadger/wiki)
- [description, how configuration repositories work](https://github.com/drivebadger/drivebadger/wiki/Configuration-repositories)
