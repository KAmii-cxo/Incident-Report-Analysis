# Incident Report Analysis

## Summary
This morning, an intern reported to the IT department that she was unable to access her internal network account. However, access logs show that her account has been actively retrieving records from the customer database, despite her being locked out. The intern mentioned receiving an email earlier today instructing her to visit an external website and log in with her internal network credentials to access a message.

It is believed that this phishing email enabled a malicious actor to gain unauthorized access to the network and customer database. Additionally, other employees have observed that several customer records are missing or contain inaccurate information. This suggests that not only was customer data exposed to the attacker, but some of it was also deleted or manipulated.

---

## 1. Identify
The incident management team conducted an audit of the systems, devices, and access policies associated with the attack to identify security gaps. Their investigation revealed that a malicious actor had obtained an intern's login credentials and used them to access the customer database. Preliminary findings indicate that some customer data was deleted from the database during the attack.

---

## 2. Protect
The team has introduced new measures to strengthen authentication and prevent future attacks. These include:
- Implementing multi-factor authentication (MFA)
- Limiting login attempts to three tries
- Providing training for all employees on safeguarding their login credentials  

Furthermore, the team plans to enhance network security by:
- Deploying a new protective firewall configuration
- Investing in an intrusion prevention system (IPS)

---

## 3. Detect
To detect potential unauthorized access attempts in the future, the team will:
- Utilize a firewall logging tool
- Deploy an intrusion detection system (IDS)  

These tools will monitor all incoming traffic from the internet, help identify suspicious activity, and provide real-time alerts to mitigate any threats promptly.

---

## 4. Respond
The team has taken the following actions:
1. Disabled the intern's network account to prevent further unauthorized access.
2. Conducted training sessions for interns and employees on better protecting their login credentials.
3. Notified upper management of the incident.
4. Ensured that management will inform customers about the data breach via mail.
5. Initiated notifications to law enforcement and other relevant organizations in compliance with local laws.

---

## 5. Recover
The team will:
1. Restore the deleted data by recovering the database from last night’s full backup.
2. Inform staff that any customer information entered or modified this morning will not be included in the backup.
3. Require staff to manually re-enter that information into the database once the restoration is complete.

---

## 6. Reflections/Notes
-
