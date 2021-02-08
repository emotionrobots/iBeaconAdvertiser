# iBeaconAdvertiser
Python3 iBeacon Advertiser

# Usage
```
from iBeaconAdvertiser import iBeaconAdvertiser

uuid = "2f234454-cf6d-4a0f-adf2-f4911ba9ffa6"
major = 42 
minor = 3987 
tx_power = -59
advertiser = IBeaconAdvertiser(uuid, major, minor, tx_power)
advertiser.start()
```
