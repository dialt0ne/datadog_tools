Datadog Tools
-------------

## Setup credentials:

* create `datadog_creds.py` with the format:

```
options = {
    'api_key': 'thequcikbrownfoxjumpedoverthelazydog',
    'app_key': 'thefiveboxingwizardsjumpedquickly'
}
```

## Edit timeboards

* `get-timeboard` will download a timeboard to standard out

```
$ ./get-timeboard -h
usage: get-timeboard [-h] (-t TITLE | -i ID)

optional arguments:
  -h, --help            show this help message and exit
  -t TITLE, --title TITLE
                        title of timeboard to get
  -i ID, --id ID        id of screenboard to get
```

* `put-timeboard` will read in a previously downloaded timeboard and update it

```
$ ./put-timeboard -h
usage: put-timeboard [-h] -f FILENAME

optional arguments:
  -h, --help            show this help message and exit
  -f FILENAME, --filename FILENAME
                        filename of previously exported timeboard
```

## Edit screenboards

* `get-screenboard` will download a screenboard to standard out

```
$ ./get-screenboard -h
usage: get-screenboard [-h] (-t TITLE | -i ID)

optional arguments:
  -h, --help            show this help message and exit
  -t TITLE, --title TITLE
                        title of screenboard to get
  -i ID, --id ID        id of screenboard to get
```

* `put-screenboard` will read in a previously downloaded screenboard and update it

```
$ ./put-screenboard -h
usage: put-screenboard [-h] -f FILENAME

optional arguments:
  -h, --help            show this help message and exit
  -f FILENAME, --filename FILENAME
                        filename of previously exported screenboard
```

## Edit monitors

* `get-monitor` will download a monitor to standard out

```
$ ./get-monitor -h
usage: get-montior [-h] (-n NAME | -i ID)

optional arguments:
  -h, --help            show this help message and exit
  -n NAME, --name NAME  name of montior to get
  -i ID, --id ID        id of montior to get
```

* `put-monitor` will read in a previously downloaded monitor and update it

```
$ ./put-monitor -h
usage: put-monitor [-h] -f FILENAME

optional arguments:
  -h, --help            show this help message and exit
  -f FILENAME, --filename FILENAME
                        filename of previously exported monitor
```
