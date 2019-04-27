## corectl measure properties

Print the properties of the generic measure

### Synopsis

Print the properties of the generic measure

```
corectl measure properties <measure-id> [flags]
```

### Examples

```
corectl measure properties MEASURE-ID
```

### Options

```
  -h, --help      help for properties
      --minimum   Only print properties required by engine
```

### Options inherited from parent commands

```
  -a, --app string               Name or identifier of the app
  -c, --config string            path/to/config.yml where parameters can be set instead of on the command line
  -e, --engine string            URL to the Qlik Associative Engine (default "localhost:9076")
      --headers stringToString   Http headers to use when connecting to Qlik Associative Engine (default [])
      --json                     Returns output in JSON format if possible, disables verbose and traffic output
      --no-data                  Open app without data
  -t, --traffic                  Log JSON websocket traffic to stdout
      --ttl string               Qlik Associative Engine session time to live in seconds (default "0")
  -v, --verbose                  Log extra information
```

### SEE ALSO

* [corectl measure](corectl_measure.md)	 - Explore and manage measures
