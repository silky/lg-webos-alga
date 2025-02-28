# Available commands

**Usage**:

```console
$ alga [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--install-completion`: Install completion for the current shell.
* `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
* `--help`: Show this message and exit.

**Commands**:

* `adhoc`: Send raw request to the TV
* `app`: Apps installed on the TV
* `channel`: TV channels
* `input`: HDMI and similar inputs
* `media`: Control the playing media
* `power`: Turn TV on and off
* `setup`: Pair a new TV
* `sound-output`: Audio output device
* `version`: Print Alga version
* `volume`: Audio volume

## `alga adhoc`

Send raw request to the TV

**Usage**:

```console
$ alga adhoc [OPTIONS] PATH [DATA]
```

**Arguments**:

* `PATH`: [required]
* `[DATA]`

**Options**:

* `--help`: Show this message and exit.

## `alga app`

Apps installed on the TV

**Usage**:

```console
$ alga app [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `close`: Close the provided app
* `current`: Get the current app
* `info`: Show info about specific app
* `launch`: Launch an app
* `list`: List installed apps

### `alga app close`

Close the provided app

**Usage**:

```console
$ alga app close [OPTIONS] APP_ID
```

**Arguments**:

* `APP_ID`: [required]

**Options**:

* `--help`: Show this message and exit.

### `alga app current`

Get the current app

**Usage**:

```console
$ alga app current [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga app info`

Show info about specific app

**Usage**:

```console
$ alga app info [OPTIONS] APP_ID
```

**Arguments**:

* `APP_ID`: [required]

**Options**:

* `--help`: Show this message and exit.

### `alga app launch`

Launch an app

**Usage**:

```console
$ alga app launch [OPTIONS] APP_ID [DATA]
```

**Arguments**:

* `APP_ID`: [required]
* `[DATA]`

**Options**:

* `--help`: Show this message and exit.

### `alga app list`

List installed apps

**Usage**:

```console
$ alga app list [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `alga channel`

TV channels

**Usage**:

```console
$ alga channel [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `current`: Get the current channel
* `down`: Change channel down
* `list`: List available channels
* `set`: Change to specific channel
* `up`: Change channel up

### `alga channel current`

Get the current channel

**Usage**:

```console
$ alga channel current [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga channel down`

Change channel down

**Usage**:

```console
$ alga channel down [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga channel list`

List available channels

**Usage**:

```console
$ alga channel list [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga channel set`

Change to specific channel

**Usage**:

```console
$ alga channel set [OPTIONS] VALUE
```

**Arguments**:

* `VALUE`: [required]

**Options**:

* `--help`: Show this message and exit.

### `alga channel up`

Change channel up

**Usage**:

```console
$ alga channel up [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `alga input`

HDMI and similar inputs

**Usage**:

```console
$ alga input [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `list`: List available inputs
* `set`: Switch to given input

### `alga input list`

List available inputs

**Usage**:

```console
$ alga input list [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga input set`

Switch to given input

**Usage**:

```console
$ alga input set [OPTIONS] VALUE
```

**Arguments**:

* `VALUE`: [required]

**Options**:

* `--help`: Show this message and exit.

## `alga media`

Control the playing media

**Usage**:

```console
$ alga media [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `fast-forward`: Fast forward media
* `pause`: Pause media
* `play`: Play media
* `rewind`: Rewind media
* `stop`: Stop media

### `alga media fast-forward`

Fast forward media

**Usage**:

```console
$ alga media fast-forward [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga media pause`

Pause media

**Usage**:

```console
$ alga media pause [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga media play`

Play media

**Usage**:

```console
$ alga media play [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga media rewind`

Rewind media

**Usage**:

```console
$ alga media rewind [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga media stop`

Stop media

**Usage**:

```console
$ alga media stop [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `alga power`

Turn TV on and off

**Usage**:

```console
$ alga power [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `off`: Turn TV off
* `on`: Turn TV on via Wake-on-LAN

### `alga power off`

Turn TV off

**Usage**:

```console
$ alga power off [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga power on`

Turn TV on via Wake-on-LAN

**Usage**:

```console
$ alga power on [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `alga setup`

Pair a new TV

**Usage**:

```console
$ alga setup [OPTIONS] [HOSTNAME]
```

**Arguments**:

* `[HOSTNAME]`: [default: lgwebostv]

**Options**:

* `--help`: Show this message and exit.

## `alga sound-output`

Audio output device

**Usage**:

```console
$ alga sound-output [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `get`: Show the current output device
* `set`: Change the output device

### `alga sound-output get`

Show the current output device

**Usage**:

```console
$ alga sound-output get [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga sound-output set`

Change the output device

**Usage**:

```console
$ alga sound-output set [OPTIONS] VALUE
```

**Arguments**:

* `VALUE`: [required]

**Options**:

* `--help`: Show this message and exit.

## `alga version`

Print Alga version

**Usage**:

```console
$ alga version [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `alga volume`

Audio volume

**Usage**:

```console
$ alga volume [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--help`: Show this message and exit.

**Commands**:

* `down`: Turn volume down
* `get`: Get current volume
* `mute`: Mute audio
* `set`: Set volume to specific amount
* `unmute`: Unmute audio
* `up`: Turn volume up

### `alga volume down`

Turn volume down

**Usage**:

```console
$ alga volume down [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga volume get`

Get current volume

**Usage**:

```console
$ alga volume get [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga volume mute`

Mute audio

**Usage**:

```console
$ alga volume mute [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga volume set`

Set volume to specific amount

**Usage**:

```console
$ alga volume set [OPTIONS] VALUE
```

**Arguments**:

* `VALUE`: [required]

**Options**:

* `--help`: Show this message and exit.

### `alga volume unmute`

Unmute audio

**Usage**:

```console
$ alga volume unmute [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

### `alga volume up`

Turn volume up

**Usage**:

```console
$ alga volume up [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.
