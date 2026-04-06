# ⚙️ Setup and Validation

## Environment
- Operating System: Kali Linux
- Tool: Suricata 8.x
- Mode: IDS

## Installation Process
Suricata was installed in Kali Linux using the package manager. During setup, repository issues were resolved by updating the Kali source list and refreshing package indexes.

## Validation
After installation, Suricata was tested in validation mode using the main configuration file.

### Validation Command
```bash
sudo suricata -T -c /etc/suricata/suricata.yaml -v

Validation Result

The configuration loaded successfully and Suricata processed more than 49,000 rules with no failures.

Key Outcome
- Configuration loaded successfully
- Rule files were processed correctly
- Suricata was ready for IDS monitoring and alert logging

## Notes
This step is important because it confirms that the IDS engine, configuration, and rules are functional before monitoring live traffic or pcap files.
