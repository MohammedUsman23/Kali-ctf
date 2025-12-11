# Network Setup — Kali CTF VM

To ensure safe and predictable behavior, use **Host-Only Adapter** mode.

---

## 🌐 VirtualBox Configuration

1. Settings → Network  
2. Adapter 1 → Enable Network Adapter  
3. Attached to: **Bridged Adapter**  
4. Advanced → Allow All  

---

## 🌐 VMware Configuration

1. VM Settings → Network Adapter  
2. Select **Host-Only**  
3. Save  

---

## 📝 Notes

- The VM will not have internet access  
- Ideal for isolated penetration testing  
- IP address stays consistent  
