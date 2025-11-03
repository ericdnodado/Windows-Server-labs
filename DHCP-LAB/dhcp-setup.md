
# Windows Server DHCP Lab

## Objective
Set up and configure a DHCP server on Windows Server 2022 to automatically assign IP addresses to clients in a test environment.


## Lab Environment

Server: Windows Server 2022
Role installed: DHCP Server
Domain: legazpidomain.com
IP range: 192.168.100.0/24
DHCP Scope: 192.168.100.1 - 192.168.100.254
Router: 192.168.100.1
DNS Server: 192.168.100.56


## Configuration steps

### 1. Install DHCP Role
### 2. Create a scope
### 3. Authorize DHCP Server in AD
### 4. Configure Default Gateway and DNS
### 5. Verify Lease assignment


## Testing
  - Connect a Windows 11 client to the same subnet
  - Ensure it obtains an IP via DHCP
  - Run ipconfig/all to verify IP configuration
