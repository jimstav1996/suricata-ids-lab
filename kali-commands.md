# 💻 Kali Commands Used in the Lab

## Installation
```bash
sudo apt update
sudo apt full-upgrade -y
sudo apt install suricata -y
```

## Rules Update
```bash
sudo suricata-update
```

## Configuration Test
```bash
sudo suricata -T -c /etc/suricata/suricata.yaml -v
```

## Interface Discovery
```bash
ip a
```

## Live Monitoring Example
```bash
sudo suricata -i wlan0 -c /etc/suricata/suricata.yaml
```

## Fast Log Monitoring
```bash
sudo tail -f /var/log/suricata/fast.log
```

## Local Rules File
```bash
sudo nano /etc/suricata/rules/local.rules
```

## Notes
These commands were used to install, validate, and prepare Suricata for IDS monitoring in a Kali Linux lab environment.
