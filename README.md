Konzol és telnet kapcsolatok jelszavainak megadása:
(config)#line con 0
(config-line)#password cisco
(config-line)#login
(config-line)#exit
(config)#line vty 0 5
(config-line)#password cisco
(config-line)#login
(config-line)#exit 

GYOR-RTR (config) #line con O
GYOR-RTR (config-line) #pas consolepassword
GYOR-RIR (config-line) #login
GYOR-RTR (config-line) #exit
GYOR-RIR (config) #ser pas
GYOR-RIR (config) #enable secret secretpassword


GYOR-RIR (config) #line con
GYOR.- RIR(config-line) #pas consolepassword
GYOR-RIR (config-line) #login
GYOR-RIR (config-line) #exit
GYOR-FIR (config) #ser pas
GYOR- RTR (config) tenable secret secretpassword
GYOR-ROR (config) #ip route 0.0.0.0 0.0.0.0 s0/1/1

#ip ssh ver 2
GYOR-RIR (config)#user gyoradmin secret remotepassword

GYOR-RTR (config) #line vty 0 15
GYOR-RIR (config-line) #login local
GYOR-RIR (config-line) #transport input ssh
(GYOR-RIR (config-line) #

SECOND (config) #ip ssh ver 2
SECOND (config) #line vty 0 15
SECOND (config-line) #pas sshfirstpass
SECOND (config line) #login
SECOND (config-line) fexit
SECOND (config) †username Wellfargo pass NorthBridge
SECOND (config) tenable pas privat123
SECOND (config) #

FIRST (config) #line con 0
FIRST (config-line) #pas konzolfirst
FIRST (config-line) #login
FIRST (config-line) #exit
FIRST (config) #ser pas
EIRST (config) #
FIRST (config) #ip route 0.0.0.0 0.0.0.0 s0/0/0
Default route without gateway, if not a point-to-point interface, perfocance
FIRST (config) #ip route 172.16.0.0 255.255.255.192s 0/0/1
FIRST (config) #ip route 172.16.1.240 255.255.255.240 s 0/0/1
EIRST (config) #

R1#copy running-config tftp:
