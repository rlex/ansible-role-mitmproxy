Simple role for installing mitmproxy and launching mitmweb  
mitmproxy is installed using pip instead of system packages   
Works only with debian-based systems with systemd


Default parameters (refer to official docs for possible options):

```
mitmproxy_mitmweb_mode: regular
mitmproxy_mitmweb_web_port: 8080
mitmproxy_mitmweb_web_iface: 0.0.0.0
mitmproxy_mitmweb_listen_host: 0.0.0.0
mitmproxy_mitmweb_listen_port: 8088
mitmproxy_mitmweb_proxy_auth: user:password
mitmproxy_mitmweb_additional_args:
  - --ssl-insecure
```