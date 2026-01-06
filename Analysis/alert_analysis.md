# Alert Analysis – SOC Task 2

## Log Source
- Sample SOC logs provided by the task

## Identified Suspicious Activities

### 1. Multiple Failed Login Attempts
- Repeated authentication failures from the same IP
- Possible brute-force attack

### 2. Unusual IP Address Access
- Login attempts from unfamiliar or foreign IPs
- Indicates potential unauthorized access

### 3. Malware Detection Alerts
- Malware signatures detected by security system
- High-risk activity

### 4. Repeated Access to Restricted Resources
- Attempts to access admin or restricted endpoints
- Privilege escalation attempt

## Severity Classification
| Alert Type | Severity |
|----------|---------|
| Brute-force login | Medium |
| Unusual IP access | Medium |
| Malware detection | High |
| Privilege escalation | High |

## Conclusion
The logs indicate multiple security incidents requiring immediate investigation and response.
