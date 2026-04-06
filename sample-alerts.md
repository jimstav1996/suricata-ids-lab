# 🚨 Sample Alerts and Monitoring

## Alert Monitoring Workflow
Once Suricata was validated, alerts could be monitored through the fast log output.

### Log Monitoring Command
```bash
sudo tail -f /var/log/suricata/fast.log
```

## Example Detection Use Cases
- Suspicious HTTP activity
- DNS request visibility
- SSH connection monitoring
- Rule-triggered alert testing

## Why This Matters
Monitoring alerts is a core part of SOC analyst work. It helps identify suspicious activity, validate detections, and support incident triage.

## Example Output Location
- `/var/log/suricata/fast.log`
- `/var/log/suricata/eve.json`
- `/var/log/suricata/stats.log`

## Notes
This lab focused on validating that Suricata could load rules and produce alert-ready output for security monitoring workflows.
