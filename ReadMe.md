Yet another load test tool by invoking curl command.

Inspired by ab (ApacheBench), loadtest in js and hey in golang.

Tested on Windows/Linux/macOS.

### Requirment

* Python2/3
* curl

### Usage

```python
$ ./ab.py
usage: ab.py [-h] [-t TIMEOUT] [-u URL] [-n TOTAL_ATTACKS]
             [-c MAX_ATTACK_AT_ONCE] [-H HEADER] [-v] [-j JSONFILE] [-p BODY]

optional arguments:
  -h, --help            show this help message and exit
  -t TIMEOUT, --timeout TIMEOUT
                        Set timeout (default: 1.5)
  -u URL, --url URL     Set URL (default: http://www.example.com)
  -n TOTAL_ATTACKS, --number TOTAL_ATTACKS
                        Set numbers of attacks (default: 100)
  -c MAX_ATTACK_AT_ONCE, --concurrent MAX_ATTACK_AT_ONCE
                        Set numbers of concurrent attacks (default: 10)
  -H HEADER, --header HEADER
                        Set headers (default: Content-Type:
                        application/json;User-Agent: Mozilla/5.0 (X11; Linux
                        x86_64; rv:59.0) Gecko/20100101 Firefox/59.0)
  -v, --verbose
  -j JSONFILE, --jsonfile JSONFILE
                        Set a json file as post body (default: None)
  -p BODY, --body BODY  Set headers (default: a long test string about
                        stock...)
```
