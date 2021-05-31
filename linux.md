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


## PiHole

|What                |How                          |
|----------------|-------------------------------|
|Show live log| `pihole -t` |
|Show chronometer| `pihole -c` |
