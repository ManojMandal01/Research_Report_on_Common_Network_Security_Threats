# 🚨 Network Security Threats Report

**Assessment Performed By:** Manoj Mandal  
**Date:** 2025-06-11

---

## 🎯 Objective

This report explores **common network security threats** with a focus on:

- Denial of Service (DoS) Attacks
- Man-in-the-Middle (MITM) Attacks
- Spoofing Attacks

Each threat is explained in terms of how it works, its impact, real-world examples, and mitigation strategies.

---

## 1️⃣ Denial of Service (DoS) Attacks

### 🔍 How It Works
DoS attacks flood a server, network, or system with illegitimate requests, causing it to become slow or completely unresponsive.  
**DDoS** (Distributed DoS) involves multiple compromised systems amplifying the attack.

### 💥 Impact
- Server downtime  
- Loss of revenue and customer trust  
- High recovery costs  

### 🧠 Real-World Example
**GitHub DDoS Attack (2018):** GitHub experienced a 1.35 Tbps DDoS attack—the largest at the time—using exposed memcached servers.

### 🛡️ Mitigation Strategies
- Use a **Web Application Firewall (WAF)**
- Implement **rate limiting** and **traffic analysis**
- Employ cloud-based DDoS services like **Cloudflare** or **Akamai**

---

## 2️⃣ Man-in-the-Middle (MITM) Attacks

### 🔍 How It Works
In MITM attacks, attackers secretly intercept and possibly modify communication between two parties.

### 💥 Impact
- Theft of sensitive data (e.g., credentials, financial info)  
- Session hijacking  
- Privacy violations  

### 🧠 Real-World Example
**Superfish MITM (2015):** Lenovo laptops shipped with adware that injected HTTPS traffic using forged certificates.

### 🛡️ Mitigation Strategies
- Enforce **end-to-end encryption** (HTTPS/TLS)  
- Use **VPNs** for secure communication  
- Educate users about risks of public Wi-Fi  

---

## 3️⃣ Spoofing Attacks

### 🔍 How It Works
Spoofing involves impersonation of trusted devices or users. Common types include:

- **IP Spoofing** – Faking IP addresses  
- **Email Spoofing** – Forging sender information  
- **ARP Spoofing** – Redirecting traffic by poisoning ARP tables  

### 💥 Impact
- Unauthorized network access  
- Data theft or tampering  
- Gateway to MITM or DoS attacks  

### 🧠 Real-World Example
**Stuxnet (2010):** Used ARP spoofing to deceive network devices and target industrial control systems.

### 🛡️ Mitigation Strategies
- Deploy **packet filtering firewalls**  
- Use **Intrusion Detection Systems (IDS)**  
- Enable **Dynamic ARP Inspection (DAI)** on switches and routers  

---

## ✅ Conclusion

Cyber threats like **DoS**, **MITM**, and **Spoofing** are growing in sophistication.  
Organizations can strengthen defenses by combining:

- Technical controls (e.g., firewalls, encryption)  
- User education  
- Continuous monitoring

> 🔐 A layered and proactive security approach is the best defense in today’s threat landscape.

---
