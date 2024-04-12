# ntrip-client
The client for connect ntripcaster https://github.com/dxhbiz/ntrip-client improved with `react-native-tcp-socket` and `ntrip-decoder-source-table`

# Demo
```
const { NtripClient } = require('../index');

const options = {
  host: 'caster.centipede.fr',
  port: 2101,
  mountpoint: 'TEST',
  username: 'centipede',
  password: 'centipede',
  userAgent: 'NTRIP',
  xyz: [-1983430.2365, -4937492.4088, 3505683.7925],
  interval: 2000
};

const client = new NtripClient(options);

client.run();
```
