# torro

Small program for managing multiple [Tor](https://www.torproject.org/)
instances on local machine.

## Installation

Make sure you have installed
[newLISP](http://www.newlisp.org/). Simply running:

```sh
./torro
```

will give you these options:

```
Usage: torro [options]
Start multiple Tor servers and manage them.
Options:
  start N - Starts N servers
  stop    - Stop all running servers
  logs    - Tail all logs
  cleanup - Remove *all* content of data folder.
  help    - Show this help
```

which are self-explanatory.

## License

Copyright (c) 2016 Sanel Zukan.
