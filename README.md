# block-evinced
tinyproxy homebrew setup: https://formulae.brew.sh/formula/tinyproxy

man pages & setup: https://tinyproxy.github.io

## Example
Using the conf file and filter.txt provided.
```
mdobeck@maxbook ~ % tinyproxy -d -c tinyproxy.conf 
NOTICE    May 14 12:43:22.966 [24517]: Initializing tinyproxy ...
NOTICE    May 14 12:43:22.967 [24517]: Reloading config file (tinyproxy.conf)
INFO      May 14 12:43:22.967 [24517]: Added address [127.0.0.1] to listen addresses.
INFO      May 14 12:43:22.967 [24517]: Adding Port [443] to the list allowed by CONNECT
NOTICE    May 14 12:43:22.967 [24517]: Reloading config file finished
INFO      May 14 12:43:22.967 [24517]: listen_sock called with addr = '127.0.0.1'
INFO      May 14 12:43:22.967 [24517]: trying to listen on host[127.0.0.1], family[2], socktype[1], proto[6]
INFO      May 14 12:43:22.967 [24517]: listening on fd [3]
INFO      May 14 12:43:22.967 [24517]: Not running as root, so not changing UID/GID.
INFO      May 14 12:43:22.967 [24517]: Setting the various signals.
INFO      May 14 12:43:22.967 [24517]: Starting main loop. Accepting connections.
```


### License(s)
[tinyproxy](https://github.com/tinyproxy/tinyproxy.github.io/blob/master/LICENSE)
