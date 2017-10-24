# peercheck

Check IOS-XR routers for BGP peering with specified ASN.

Check for direct peering with 'show bgp sum | i $peerasn"

Check for indirect (route-server) peering with 'show bgp regexp _$peerasn_'

##Usage:
python peercheck.py $peerasn

##Example:
To see if you peer with Netflix, run the following.
python peercheck.py 2906
