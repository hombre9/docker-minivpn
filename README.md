## docker-minivpn

have your openvpn config/keys etc somewhere (/data/openvpn used below)

run with

> docker run -d -t -i -p 1194:1194 -v /data/openvpn:/etc/openvpn --cap-add=NET_ADMIN aussiede/minivpn
