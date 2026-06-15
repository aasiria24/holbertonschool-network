# Networking Basics #1

Bash scripts covering localhost, network interfaces, and port listening.

## Topics Covered

- localhost and 127.0.0.1
- What is 0.0.0.0
- The /etc/hosts file
- Active network interfaces

## Files

| File | Description |
|------|-------------|
| `0-change_your_home_IP` | Configures localhost to resolve to 127.0.0.2 and facebook.com to 8.8.8.8 |
| `1-show_attached_IPs` | Displays all active IPv4 IPs on the machine |
| `2-port_listening_on_localhost` | Listens on port 98 on localhost |

## Usage

### 0-change_your_home_IP
```bash
sudo ./0-change_your_home_IP
```
> ⚠️ Revert localhost after use: `sed -i 's/127.0.0.2 localhost/127.0.0.1 localhost/' /etc/hosts`

### 1-show_attached_IPs
```bash
./1-show_attached_IPs
```

### 2-port_listening_on_localhost
```bash
sudo ./2-port_listening_on_localhost
```

## Author
**Amaal Asiri**, Holberton School Student
