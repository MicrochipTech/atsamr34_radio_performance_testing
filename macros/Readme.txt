Scripts written to be used with Tera Term Macro
-----------------------------------------------

Open and connect with Serial Port
In Tera Term -> Control -> Macro -> Load .ttl file


CW Test
-------
- Connect a DUT with Tera Term
- Open Transmitter_CW_mode.ttl macro


Continuous Packets transmission Test
------------------------------------
- Open a DUT #1 with Tera Term
- Open Receiver_Continuous_Rx_mode.ttl macro

- Open a DUT #2 with Tera Term
- Open Transmitter_Continuous_Packets_mode.ttl macro


PER Test
--------
- Connect DUT #1 with Tera Term
- Open Receiver_narrowBand.ttl macro

- Connect DUT #2 with Tera Term
- Open Transmitter_Packets_mode.ttl macro


PEER TO PEER
------------
- Connect DUT #1 with Tera Term
- Open Peer_to_peer.ttl macro
- Select Transmitter role

- Connect DUT #2 with Tera Term
- Open Peer_to_peer.ttl macro
- Select Receiver role