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


