# togglehidden
Togglehidden is a tool for easy show/hide invisible files in osx.

### Installation
You can use this in several ways:

* Install it like an usual osx app:

  ```bash
  $ git clone git@github.com:poporul/togglehidden.git /Application/togglehidden
  ```

* Or like an execution script:

  ```bash
  $ curl -fsSL http://git.io/vtJSg > /usr/local/bin/togglehidden
  $ chmod +x /usr/local/bin/togglehidden
  ```

* Or even execute it immediately:

  ```bash
  $ curl -fsSL http://git.io/vtJSg | tail -n +2 | osascript -l JavaScript
  ```

### Warnings
If you will use this tool in command-line mode you will get warning:
```bash
$ warning: failed to get scripting definition from /usr/bin/osascript; it may not be scriptable.
```
There are many threads in the internet about this warn and I think it will be fixed later.

### Tested on

MacBook Pro (Mid 2009)
OS X Yosemite 10.10.3
