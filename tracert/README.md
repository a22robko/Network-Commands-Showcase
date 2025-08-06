# ✅ tracert

`tracert` (short for *Trace Route*) shows the route that packets take from your computer to a destination host (like `google.com`).  
It lists each router (hop) along the path and shows how long each one takes to respond.

---

## 🔍 What it does

- Displays the **route** packets take to reach a remote host
- Lists **each router (hop)** on the path
- Shows **response time (latency)** from each router
- Helps identify where **network issues or delays** happen

---

## 📈 What the output shows

Each line represents a **network hop**, including:
- ⏱ Latency (in milliseconds) for 3 ICMP packets
- 🌐 IP address or host name of the router
- ⚠️ Detection of slow or failing hops

This helps pinpoint **where** connection problems or delays occur in the network.

---
- ✅ `192.168.0.1` – Local router, very low latency
- ✅ `83.68.237.98` – ISP router, normal speed
- ✅ `sto-google-ark.customer.arkaden.se` – Google's entry point
- ⚠️ `125 ms` at hop 8 – A delay is visible here, possibly a bottleneck

---

## 🧠 When to use it

Use `tracert` when:
- A site is **slow or unreachable**
- You want to find **where latency or loss occurs**
- You're troubleshooting **local vs ISP vs remote issues**

---

## 🛠 Example troubleshooting

**Scenario:** A user reports slow access to a website  
**Action:** Run `tracert google.com`  
**Result:** Delay is observed at hop 8  
**Conclusion:** Bottleneck is **outside** the local network (possibly in ISP or beyond)

---

## 📷 Screenshot

<img width="1024" height="502" alt="image" src="https://github.com/user-attachments/assets/9400e0f4-6af6-4253-9ead-ae76a68e1ae8" />
