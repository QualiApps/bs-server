LWM2M Bootstrap server
===========
The Bootstrap Interface is used to provision essential information into the LWM2M Client 
to enable the LWM2M Client to perform the operation “Register” with one or more LWM2M Servers.

Running the daemon
-----------------

`docker run -d -p 5685:5685/udp --name bs_server qapps/bs-server`


After running BS server you can start LWM2M clients.
