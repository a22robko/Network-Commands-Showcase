# ✅ pathping

`pathping` is a combination of `ping` and `tracert`.  
It traces the route to a target and then measures packet loss and latency at each hop along the way.  
It’s a powerful tool for identifying **network delays** or **packet loss** on specific parts of a network path.

---

## 🔍 What it does

- Traces the path to a remote host (like `google.com`)
- Sends multiple pings to each hop
- Shows **packet loss** and **latency** per hop
- Helps identify where network issues are happening

---

## 📈 What the output shows

- Each line represents a **hop** (router or network point)
- Hostnames and IP addresses along the route
- Final stats show:
  - % **packet loss**
  - **Average round-trip time**
  - Which hop may be causing slowdowns

---

## 🧠 When to use it

Use `pathping` when:
- You suspect **intermittent packet loss**
- You want more detailed data than `ping` or `tracert` provide
- You're troubleshooting network quality issues (e.g. gaming, VoIP)

---

## 🛠 Example troubleshooting

**Scenario:** A user says Zoom calls drop frequently.  
**Action:** Run `pathping google.com`  
**Result:** High packet loss detected at a specific hop  
**Conclusion:** Problem is likely at that ISP or router

---

<img width="606" height="517" alt="image" src="https://github.com/user-attachments/assets/3fd7bf65-f3e9-451f-b548-9437045f4a0c" />
