# Troubleshooting

## Group Policy Failure

### Problem

gpupdate /force failed with LDAP authentication errors.

### Cause

Domain controller and client times were not synchronized, causing Kerberos authentication failures.

### Resolution

Corrected time synchronization settings and verified successful Group Policy processing.

---

## DNS Registration

### Problem

The domain controller retained outdated DNS records following migration to a new subnet.

### Resolution

Used:

```cmd
ipconfig /registerdns
```

and verified updated DNS records.

---

## Windows Network Profile

### Problem

Windows 11 detected the network as Public following subnet migration.

### Resolution

Restarted Windows and verified the system correctly detected the domain network.