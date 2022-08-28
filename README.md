# usage  
1. push file `pppd` and `chat` to `/usr/bin`
2. push file `quectel-ppp`,`quectel-chat-connect`,`quectel-chat-disconnect` to `/etc/ppp/peers/`. The dialer profile is for China Unicom.
3. Use order `pppd call quectel-ppp` to connect the internet