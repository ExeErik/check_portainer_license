# check_zammad_monitoring
This script checks the validity period of the current Portainer license and issues a Critical if it is less than 30 days.

```
usage: check_portainer_license.py [-h] -H HOST -t TOKEN [-k | --insecure | --no-insecure]

check_portainer_license

optional arguments:
  -h, --help                       show this help message and exit
  -H HOST, --host HOST             The portainer monitoring url with http:// | https:// and port
  -t TOKEN, --token TOKEN          The token to use, found in Webfrontend
  -k, --insecure, --no-insecure    Dont verify the ssl-certificate (default: False)
```
