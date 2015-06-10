# Clock Skew
This library provides an API for determining the local time, given some periodic updates from a reference time. The algorithm assumes that any network latency is roughly constant, so is likely unsuitable for the wide-open Internet. However, this assumption holds true enough for a local network.

### Note
This is not an official Google product (experimental or otherwise), it is just code that happens to be owned by Google.