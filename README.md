sshopen
=======

This is a simple bash script which creates a ssh tunnel to a remote server and opens a web browser to it locally.

Installation
------------

Either just download sshopen from this repo into your path, or install using npm:

```
npm install -g sshopen
```

Usage
-----

```
sshopen http://remote.server.com:6789/private-website.html
```

The above command creates an ssh connection to `remote.server.com` and sets up tunneling for remote port **6789** to a free local port. If **6789** is free locally, a browser tab will open on `http://localhost:6789/private-website.html`.

Todo
----

* Support different ssh and tunnel host. F.ex. `sshopen vpn.server.com http://private-ip/`
