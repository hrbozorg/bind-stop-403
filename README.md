# STOP 403 by bind:named service

```bash
wget -O /etc/boycott-zones.conf https://raw.githubusercontent.com/hrbozorg/bind-stop-403/main/etc/boycott-zones.conf
```

```
include "/etc/boycott-zones.conf";
```