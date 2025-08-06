# ✅ nslookup

`nslookup` is a command-line tool used to query DNS servers and retrieve domain name or IP address mapping information.

It's useful for checking if a domain resolves correctly and which DNS server is providing the response.

---

## 🔍 What it does

- Translates a domain name (like `google.com`) into its IP address
- Shows which DNS server is used for the lookup
- Useful for troubleshooting DNS issues or delays

---

## 📈 What the output shows

- **Server:** The DNS server used to resolve the query (in this example: `192.168.0.1`)
- **Name:** The queried domain (e.g. `google.com`)
- **Addresses:** The resulting IP addresses (both IPv4 and IPv6 if available)
- Indicates whether the response is authoritative or not

---

## 🧠 When to use it

Use `nslookup` when:

- A domain isn’t loading, and you suspect DNS issues
- You want to verify which IP a domain resolves to
- You're testing custom or alternative DNS settings

---

## 🛠 Example troubleshooting

**Scenario:** A user can’t access a website.  
**Action:** Run `nslookup website.com`  
**Result:** No IP returned or wrong IP.  
**Conclusion:** Likely a DNS misconfiguration or outage.

---

## 📷 Screenshot

![nslookup example](https://github.com/user-attachments/assets/fb9c6d5d-363f-434e-8b98-c5384756a308)
