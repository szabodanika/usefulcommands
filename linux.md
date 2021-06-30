## General

|What                |How                          |
|----------------|-------------------------------|
|Find process using port| `netstat -ltnp \| grep -w ':[PORT]'`            |
|Kill process          | `kill [PID]`            |
|List processes          | `htop` |

## Immortal

|What                |How                          |
|----------------|-------------------------------|
|Start immortal process| `immortal [command]`            |
|List running processes managed by immortal          | `immortalctl`            |
|Kill all immortal processes          | `immortalctl halt "*"` |

## PiVPN

|What                |How                          |
|----------------|-------------------------------|
|Add client| `pivpn add` |
|Show QR for client| `pivpn qr` |
|Connected Clients| `pivpn -c` |
|All Clients| `pivpn -l` |


## PiHole

|What                |How                          |
|----------------|-------------------------------|
|Show live log| `pihole -t` |
|Show chronometer| `pihole -c` |

## SSH to access Duplicatii web interface
`ssh -f user@host.ip -L 12345:localhost:8200 -N`
