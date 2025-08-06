## 📡 `arp -a`

The `arp -a` command displays the Address Resolution Protocol (ARP) table for all network interfaces on your system. It shows mappings between **IP addresses** and **MAC (physical) addresses** that your computer has recently communicated with.

---

### 🔍 What the command shows

- **Internet Address** – The IP address of another device on the network  
- **Physical Address** – The MAC address associated with that IP  
- **Type** – Whether the entry was learned dynamically or is static

---

### 🧠 When to use it

Use `arp -a` to:

- 🔍 Troubleshoot local network connectivity  
- 🔄 See which devices your computer has talked to recently  
- 🧱 Detect duplicate IPs or spoofing (same MAC address for multiple IPs)

---

### 📌 Example interpretation

| IP Address        | MAC Address          | Type     | Meaning                          |
|------------------|----------------------|----------|----------------------------------|
| `192.168.0.1`     | `d8-44-89-e1-8a-54`   | dynamic  | Your local router                |
| `192.168.0.196`   | `34-e6-e6-5c-b4-ea`   | dynamic  | Another active device on LAN     |
| `239.255.255.250` | `01-00-5e-7f-ff-fa`   | static   | A multicast address              |

You can also identify **static broadcast/multicast addresses** and **multiple interfaces**, as seen below.

---

### 🖼 Example output
<img width="615" height="754" alt="image" src="https://github.com/user-attachments/assets/e4101e12-ca74-401b-ae97-83bc5c2cc2e8" />


---


