# 🚨 Incident Response using Splunk

## 📌 Objective
This project simulates a real-world SOC investigation of an SSH brute-force attack using Splunk.

## 📌 Note
This incident response project is based on Splunk log analysis, where SSH authentication logs were investigated to identify brute-force attacks and potential system compromise.

---

## ⚙️ Tools Used
- Splunk SIEM  
- SSH Logs (JSON)

---

## 🧪 Investigation Steps

### Step 1: Attacker Identification
Identified IP with highest failed login attempts.

📸  
![Attacker Identification](screenshots/1_ir__attacker.jpg)

---

### Step 2: Brute Force Detection
Detected repeated failed authentication attempts.

📸  
![Brute Force Detection](screenshots/2_ir_bruteforce_attacker.jpg)

---

### Step 3: Compromise Check
Observed successful login after multiple failed attempts.

📸  
![Compromise Check](screenshots/3_ir_compromise_check.jpg)

---

### Step 4: Timeline Analysis
Tracked attack progression using log timestamps.

📸  
![Timeline Analysis](screenshots/4_ir_timeline.jpg)

---

## 🚨 Findings

- Attacker IP: 10.0.0.30  
- Failed Attempts: 11  
- Successful Logins: 6  
- Attack Type: SSH Brute Force  

---

## ⚠️ Conclusion

The attacker successfully gained unauthorized access after multiple failed login attempts, confirming a brute-force compromise.

---

## 🛡️ Recommendations

- Enable Multi-Factor Authentication (MFA)  
- Implement account lockout policies  
- Monitor login attempts  
- Block malicious IP addresses  


