## 🏓 `ping`

The `ping` command is used to test the reachability of a host on an IP network and measure the round-trip time for messages sent from the source to a destination.

### 🔍 What it shows

- Checks if a device (usually a server or another computer) is reachable over the network.
- Displays response time and packet loss (if any).
- Measures **latency** between your computer and the destination.

### 💡 When to use it

- ✅ To test internet or local network connectivity.
- 🌐 To check if a DNS or IP address is responding.
- 🛠️ When troubleshooting slow or dropped connections.

---

### 📌 Example 1 – Successful ping

<img width="628" height="769" alt="ping-success" src="https://github.com/user-attachments/assets/975d1a08-c158-40cc-99ca-3d9b745d5e04" />

> In this example, the user pings **8.8.8.8** (Google DNS).  
> All 4 packets were received with no packet loss, and response times were shown.

---

### 📌 Example 2 – Failed ping

<img width="540" height="347" alt="ping-fail" src="https://github.com/user-attachments/assets/441f9bea-c99d-495b-89e9-8a897599b052" />

> Here, the same IP address is unreachable.  
> All requests timed out, showing 100% packet loss. This could be due to firewall rules, internet issues, or DNS resolution problems.
