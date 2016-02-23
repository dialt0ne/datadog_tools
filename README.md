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

* `get-timeboard` will download a timeboard to standard out

```
$ ./get-timeboard -h
usage: get-timeboard [-h] -t TITLE

optional arguments:
  -h, --help            show this help message and exit
  -t TITLE, --title TITLE
                        title of timeboard to get
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
