# Subnetting4

Tramite il subnetting a 4 abbiamo diviso una rete, la quale subnet è `255.255.255.0` e che permette l'entrata di 254 host, in 4 sottoreti la quale ognuna permette l'entrata di 64 host.
+ **254** $\rightarrow$ Perchè l'host 0 è occupato dall'**ID di rete** e l'host 255 come **broadcast** (Volendo 253 host perchè il router occupa l'host 254).
+ **64** $\rightarrow$ Perchè gli host per la rete da `172.130.20.0` si dividono in 4, e la subnet di ogni sottorete diventerà `255.255.255.192`

Le 4 sottoreti :
+ **172.130.20.0** $\rightarrow$ Avrà come range di host `172.130.20.1` a `172.130.20.62` dove `172.130.20.63` sarà utilizzato come broadcast.
+ **172.130.20.64** $\rightarrow$ Avrà come range di host `172.130.20.65` a `172.130.20.126` dove `172.130.20.127` sarà utilizzato come broadcast.
+ **172.130.20.128** $\rightarrow$ Avrà come range di host `172.130.20.129` a `172.130.20.190` dove `172.130.20.191` sarà utilizzato come broadcast.
+ **172.130.20.192** $\rightarrow$ Avrà come range di host `172.130.20.193` a `172.130.20.253` dove `172.130.20.254` sarà utilizzato come broadcast.
