LWM2M Bootstrap server
===========
The Bootstrap Interface is used to provision essential information into the LWM2M Client 
to enable the LWM2M Client to perform the operation “Register” with one or more LWM2M Servers.

Running the daemon
-----------------

`docker run -d -p 5685:5685/udp --name qapps/bs_server [params]`


####available params:

    [-f  path to the bootstrap ini file]

After running BS server you can start LWM2M clients.
