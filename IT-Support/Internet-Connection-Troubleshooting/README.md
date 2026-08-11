# Internet Connection Troubleshooting

## 📌 Scenario

A user reports that their computer cannot access the internet.

The computer is connected to the network, but websites are not loading.

## 🎯 Objective

Identify the cause of the connectivity problem and restore internet access.

## 🔍 Troubleshooting Process

### 1. Check the network connection

First, confirm whether the computer is connected to Wi-Fi or Ethernet.

### 2. Check IP configuration

On Windows, run:

```cmd
ipconfig /all
```
Result:

Active Wi-Fi adapter identified
IPv4 address assigned
Default gateway configured
DNS server configured
DHCP enabled

Status: ✅ Passed

Test 2: Local Network Connectivity

Command used:
```cmd
ping <default-gateway>
```
Result:

4 packets sent
4 packets received
0% packet loss
Average response time: approximately 2 ms

Status: ✅ Passed

Test 3: Internet Connectivity

Command used:
```cmd
ping 8.8.8.8
```
Result:

4 packets sent
4 packets received
0% packet loss
Average response time: approximately 3 ms

Status: ✅ Passed

Test 4: DNS Resolution

Command used:
```cmd
nslookup google.com
```
Result:

DNS server responded
google.com successfully resolved to IP addresses

Status: ✅ Passed

📊 Final Assessment

All network connectivity tests passed successfully.

The computer had:

Valid IP configuration
Working connection to the local gateway
Working internet connectivity
Working DNS resolution

No network connectivity issue was identified during this test.
