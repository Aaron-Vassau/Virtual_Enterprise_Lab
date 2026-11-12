# Network Architecture

## Network Segments

| Network | Subnet | Gateway |
|----------|----------|----------|
| IT | 10.0.10.0/24 | 10.0.10.1 |
| HR | 10.0.20.0/24 | 10.0.20.1 |
| Accounting | 10.0.30.0/24 | 10.0.30.1 |
| Servers | 10.0.99.0/24 | 10.0.99.1 |

## Devices

| Device | IP Address |
|----------|----------|
| Windows 11 | 10.0.10.10 |
| Alpine Linux | 10.0.20.20 |
| DC01 | 10.0.99.10 |
| Ubuntu Services | 10.0.99.20 |

## Router Interfaces

| Interface | IP Address |
|----------|----------|
| ens38 | 10.0.10.1 |
| ens39 | 10.0.20.1 |
| ens40 | 10.0.30.1 |
| ens41 | 10.0.99.1 |