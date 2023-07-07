# aws-cf-det-upgrade

| Option | Description |
| --- | ---|
| `--salt` | optional hashing salt argument, defaults to `None` if not provided. (see Anonymization Strategy section below) |
| `--input` | optional path to input SQL file, defaults to `stdin` if not provided |
| `--output` | optional path to output SQL file, defaults to `stdout` if not provided |
| `--log` | optional path to log file. defaults to `stdout` unless `--output` is also `stdout`, then it writes to the file `anonymize.log` |
| `--quiet` | silences the script from printing out message logs to `--log` |
| `--help` | prints out all the available script options |
