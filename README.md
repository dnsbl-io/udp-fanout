# udp-fanout

Forwards incoming UDP packets to multiple targets.
Useful to distribute statsd packets to multiple services.

## Usage
 
    udp-fanout [<ip>:]<port> <target:port> [<target:port>, ...]
    
    Listens on ip (default: 127.0.01) and sends incoming UDP packets to all targets.

## Similar projects

* https://github.com/sleinen/samplicator
* https://github.com/vlovich/udp-fanout
 
