# **Network Connectivity Troubleshooting and Diagnostics**

### **1\. Objective**

Assess network connectivity, packet loss, DNS resolution, routing, and HTTPS accessibility on a Windows 11 laptop.

### **2\. Tools Used**

* `ipconfig` — Examined network configuration.  
* `ping` — Tested connectivity, latency, and packet loss.  
* `nslookup` — Verified DNS resolution.  
* `tracert` — Examined the network route to an external server.  
* `curl` — Tested HTTPS connectivity.

### **3\. Investigation and Findings**

| Test | Result |
| ----- | ----- |
| Local network connectivity | Successfully communicated with the default gateway. |
| External connectivity | Successfully reached 8.8.8.8. |
| Packet loss | 0% packet loss across 50 requests. |
| Network latency | Average response time of 17 ms to 8.8.8.8. |
| DNS resolution | Successfully resolved google.com using both default and public DNS servers. |
| Network routing | Successfully traced the route to 8.8.8.8. |
| HTTPS connectivity | Received HTTP 301 response from google.com, indicating a successful HTTPS request and redirect. |

### **4\. Conclusion**

No network connectivity faults were identified during testing.

The laptop successfully communicated with the local gateway and external servers. DNS resolution, routing, and HTTPS connectivity were functioning correctly.

**No corrective action was required.**

