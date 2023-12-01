# poleclient

## config 
```
{
    "endpoint":"wss://x.x.x.x:443",
    "skipVerifySSL":true,
    "user":"user",
    "password":"password",
    "sni":"www.apple.com",
    "use_remote_route":true,
    "use_remote_dns":true,
    "route_networks":["10.8.0.0/16"],
    "proxy_domains":[]
}
```

## windows client allow inbound traffic
* Windows Firewall-> Enable or Disable -> Disable Firewall (or configure firewall rules)
