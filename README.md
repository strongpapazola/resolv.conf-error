```
curl: (6) Could not resolve host: domain
```

when try to edit /etc/resolv.conf
```
Error writing /etc/resolv.conf: No such file or directory
```

sollution
```
systemctl enable --now systemd-resolved.service
```

