# 🛠️ Network Troubleshooting

## 📌 Common Issues & Solutions

### ❌ No Internet Connection
- Check cables
- Check Wi-Fi connection
- Run ipconfig

---

### ❌ APIPA Address (169.254.x.x)
- DHCP server not reachable
- Solution:
  - ipconfig /release
  - ipconfig /renew

---

### ❌ Cannot Reach Website
- Check DNS using nslookup
- Try pinging IP instead of domain

---

### ❌ Slow Network
- Check bandwidth usage
- Run tracert to detect delays

---

## 🧠 Troubleshooting Steps

1. Identify the problem
2. Establish a theory
3. Test the theory
4. Implement solution
5. Verify functionality
6. Document the issue