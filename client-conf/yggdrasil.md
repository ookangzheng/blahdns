## DNS-over-TLS for Yggdrasil (IPv6 only)

**Unbound conf**

```
forward-zone:
    name: "."
    forward-tls-upstream: yes
    # Yggdrasil
    forward-addr: 200:1b2c:591b:68fd:7374:b33f:46c9:55fc@853#dot-sg.blahdns.com
    forward-addr: 200:40cd:f219:b894:c0a4:728f:7849:7e37@853#dot-de.blahdns.com
    forward-addr: 204:fa25:8213:ca51:1e9b:c973:edc0:63fd@853#dot-fi.blahdns.com
    forward-addr: 202:f97c:46c8:d7b4:71f1:7e8b:2e64:353d@853#dot-jp.blahdns.com
    forward-addr: 201:bec2:6bf3:dd52:dc7f:71ff:71:53a3@853#dot-ch.blahdns.com
    
```

**Server IPv6**
```
Singapore: 200:1b2c:591b:68fd:7374:b33f:46c9:55fc
Japan: 202:f97c:46c8:d7b4:71f1:7e8b:2e64:353d 
Germany: 200:40cd:f219:b894:c0a4:728f:7849:7e37
Finland: 204:fa25:8213:ca51:1e9b:c973:edc0:63fd
Switzerland: 201:bec2:6bf3:dd52:dc7f:71ff:71:53a3
```
