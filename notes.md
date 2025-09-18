# First class
## Networks Types
wirless -> no physical socket
mobile -> can change networks without changing identification
mobile + wireless -> radio
sensor -> ??

## Cellular concept
Dn -> distance at what point we can use the same frequencies again (perhaps for a different thing) without interference
Dn = R*sqrt(3n)
n -> number of cells in the cluster (i^2 + ij + j^2)
R -> distance of one edge (side) of the cell

### examples
D3 -> 3R
D4 -> 2R * sqrt(3)
D7 -> R * sqrt(21)

## Networks
- WLAN (100m (1km)) (Wireless Local Area Network)
- WPAN (10m (1km)) (Wireless Personal Area Network)
- WMAN (a city) (Wireless Metropolitan Area Network)
- WWAN (a country) (Wireless Wide Area Network)
- WSN

biggest difference between (WLAN, WPAN, WMAN, WWAN) is size
(WLAN, WPAN, WMAN) use IEEE 802.11g (can be a, b, g or n) (celullar)

### WLAN
#### infrastructure
- ex: at home
- central access point (router)

#### ad-hoc
- ex: emergency, military
- no central access point
- any device can communicate with any device *directly*
