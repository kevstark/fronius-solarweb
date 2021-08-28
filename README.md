# fronius-solarweb
Exploration of Fronius Inverter communications

Every 60 seconds, a 97 byte UDP packet is sent to `fdmp.solarweb.com:49049`

| offset | length | purpose |
| -----: | -----: | :------ |
| 0 | 3 | DataManager ID, minor component (ie, 240.**123456**)
| 4 | 1 | DataManager ID, major component (ie, **240**.123456)
