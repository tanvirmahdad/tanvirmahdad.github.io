

# **Authentication Security**  
In these works, we primarily analyze the security of state-of-the-art authentication systems and their vulnerabilities against well-designed attacks. The scope of these projects includes designing novel attack frameworks, evaluating the security of authentication systems using technical assessments and real-world user studies, and finally, securing these systems by mitigating the identified vulnerabilities with the help of modern AI/ML techniques.

### **FIDOLA**

<div style="float: right; width: 45%; margin-left: 20px; margin-bottom: 10px;">
  <img src="/assets/files/windows_security_attack.png" 
       style="width:100%; border: 2px solid #000; border-radius: 3px;">
</div>

This research examines the security of FIDO2 hardware security keys used in two-factor and passwordless authentication systems. We develop an attack framework called **FIDOLA (FIDO2 Deception Attack via Overlays exploiting Limited Display Authenticators)**, which injects hidden login sessions and deceives users into approving malicious requests through limited authenticator displays. 

Our analysis of FIDO2 protocols and OS-level security, combined with practical demonstrations, reveals a critical vulnerability not addressed in current specifications or prior research. A user study shows that **95.55% of participants** approved cross-service attacks when presented with deceptive overlays, highlighting a serious real-world threat to account security.


### **Notification-based Authentication**

<div style="float: right; width: 45%; margin-left: 20px; margin-bottom: 10px;">
  <img src="/assets/files/push_2fa.png" 
       style="width:100%; border: 2px solid #000; border-radius: 3px;">
</div>

This work evaluates the security of notification-based authentication systems, a popular 2FA and passwordless solution using mobile notifications, when a user’s computer is compromised by malware such as keyloggers or malicious extensions. We show that limited information in the authentication workflow can lead users to approve fraudulent requests, enabling cross-service attacks where an attacker authenticates to Service B while the user intends to access Service A. Our proof-of-concept demonstrates vulnerabilities across multiple systems, and a user study reveals an 82.2% success rate for such attacks, highlighting a critical weakness that allows account compromise without breaching the possession-factor device.