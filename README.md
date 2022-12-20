# dns
Small example of Bind9 as cache, forwarding and local resolver


docker run --it --rm --entrypoint /bin/sh internetsystemsconsortium/bind9:9.19


## Folders structure

- "./data/config:/etc/bind"       # Configuration folder
- "./data/cache:/var/cache/bind"  # Cache
- "./data/zones:/var/lib/bind"    # secondary zones
- "./data/log:/var/log"           # Logs