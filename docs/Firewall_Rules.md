
- IT -> HR
- HR -> IT

## Example Rules

```bash
iptables -A FORWARD -s 10.0.10.0/24 -d 10.0.20.0/24 -j DROP
iptables -A FORWARD -s 10.0.20.0/24 -d 10.0.10.0/24 -j DROP
```