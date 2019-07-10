# nginx-cf

## Usage (Cronjob)

```bash
30	6	*	*	*	rm -rf /etc/nginx/conf.d/archiveorg.conf && wget -O /etc/nginx/conf.d/archiveorg.conf https://git.lelux.fi/theel0ja/ip-blocklists/raw/branch/master/archiveorg.conf > /dev/null
30	6	*	*	*	rm -rf /etc/nginx/conf.d/domaintools.conf && wget -O /etc/nginx/conf.d/domaintools.conf https://git.lelux.fi/theel0ja/ip-blocklists/raw/branch/master/domaintools.conf > /dev/null
```
