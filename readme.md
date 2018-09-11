# sslcheck

A simple php script to check the expiry of SSL certificates - Windows Version.

<a href="https://asciinema.org/a/105703" target="_blank"><img src="https://asciinema.org/a/105703.png" width="480"/></a>

### Requirements

* PHP (Including CLI support).
* OpenSSL

This script has been tested only on Windows 10 Pro using PHP7.

### Usage

1. Clone this repo or simply download the `sslcheck.bat` and `ssl` files.
2. Add the path where your `sslcheck.bat` to the `PATH` environment variable.
3. Execute the script `sslcheck www.example.com`.

If you can't execute the script directly you may need to envoke the script via php (`php ssl www.example.com`);

You can check mutiple domains by listing them all out when running the script:

```
sslcheck www.google.com www.example.com www.github.com
```

#### Usage via Email

TODO: I don't need this yet. But since the original author has written it, it would be nice to have this in the future.

### Credits
- [Dan Brown](https://github.com/ssddanbrown) for the Ubuntu version
