# wireshark-network-analysis
Wireshark-based analysis of HTTP traffic to study packet flow and unencrypted data exposure.

## 🔍 Traffic Analysis Evidence

### 📡 HTTP Packet Capture
The following screenshot shows live HTTP traffic captured in a controlled lab environment.  
It includes request/response flows, status codes, and destination servers.

![HTTP Capture](https://github.com/sidharth-w/wireshark-network-analysis/blob/3cd89ef54de0c5b02c834c70a4db155f05df0dfe/http-capture.png)

---

### 🔐 Credential Exposure via Follow TCP Stream
This screenshot demonstrates how sensitive data such as login credentials can be exposed
when applications use HTTP instead of HTTPS.

Sensitive fields were redacted for safety.

![Follow TCP Stream](screenshots/follow-tcp-stream.png)
