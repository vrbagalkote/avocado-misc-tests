This Program runs Direct Access Programming Library (DAPL) tests on client and server for the interfaces specified in config file (dat.conf). It runs for 5 different inputs, as specified in multiplexer file.

Inputs Needed in config file:
-----------------------------
PEER_IP	    - IP of the Peer interface to be tested
DAPL_IF1    - RDMA Interface on the Host. Can be taken from the file dat.conf (dat.conf location differs based on OS)
DAPL_IF2    - RDMA Interface on the Host. Can be taken from the file dat.conf (dat.conf location differs based on OS)

Note:
-----
1. Ensure the dat.conf has details of your dapl interface under test (refer: man dat.conf)
2. Generate sshkey for your test partner to run the test uninterrupted. 

