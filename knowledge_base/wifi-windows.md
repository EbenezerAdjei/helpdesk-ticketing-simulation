# Fix: Wi-Fi not connecting — Windows

Summary / TL;DR
If a Windows 10/11 device cannot connect to Wi-Fi, follow these steps to check adapter status, reset the connection, and restore network access.


## Symptoms

* Wi-Fi icon shows “No internet” or “Cannot connect to this network”.

* User reports slow or no connectivity despite being connected to SSID.

* Unable to browse websites or resolve domain names.



## Causes

### Common reasons include:

* Disabled or faulty Wi-Fi adapter.

* Incorrect saved network configuration.

* DHCP not assigning IP address.

* Outdated drivers.

* Firewall or VPN interference.


## Step-by-step Resolution

### 1. Restart network connection

* Turn Wi-Fi off and on again from the taskbar.

* Restart the PC if still not working.

### 2. Check Wi-Fi adapter status

* Open Device Manager → Network adapters.

* Ensure the adapter is enabled (no red X).

* If yellow warning sign is visible, right-click → Update driver.

### 3. Forget and reconnect to the network

* Go to Settings → Network & Internet → Wi-Fi → Manage known networks.

* Select the affected SSID → Forget.

* Reconnect and re-enter the correct password.

### 4. Verify IP configuration

* Open Command Prompt (Run as Administrator).

#### Run:

* ipconfig /all
* ping 8.8.8.8
* nslookup www.google.com

* If IP address is 169.254.x.x → DHCP issue. Ask IT/network team to check DHCP server.

### 5. Check firewall/VPN

* Temporarily disable VPN and test.

* Turn off local firewall (Windows Defender Firewall) to rule out blocking.

### 6. Update Wi-Fi driver

* Download the latest driver from the manufacturer’s website.

* Install and restart the PC.

## Validation / Expected result

* User reconnects to Wi-Fi successfully.

* ping 8.8.8.8 and nslookup www.google.com succeed.

* Web browsing works without error.

## Rollback (if applicable)

* Reinstall previous Wi-Fi driver if new driver fails.

* Re-enable firewall after troubleshooting.

* Restore VPN settings if disabled.

---
