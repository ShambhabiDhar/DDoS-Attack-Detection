# DDoS-Attack-Detection
DS3 project- Shambhabi Dhar, B21022

Distributed Denial of Service attack (DDoS) is the most dangerous
attack in the field of network security. DDoS attack halts normal functionality of critical
services of various online applications. Systems under DDoS attacks remain busy with false
requests (Bots) rather than providing services to legitimate users. These attacks are
increasing day by day and have become more and more sophisticated. So, it has become
difficult to detect these attacks and secure online services from these attacks.

DDoS attacks are carried out with networks of Internet-connected machines. These networks consist of computers and other devices (such as IoT devices)which have been infected with malware, allowing them to be controlled remotely by an attacker. These individual devices are referred to as bots (or zombies), and a group of bots is called a botnet. Once a botnet has been established, the attacker is able to direct an attack by sending remote instructions to each bot. When a victim’s server or network is targeted by the botnet, each bot sends requests to the target’s IP Address, potentially causing the server or network to become overwhelmed, resulting in a denial-of-service to normal traffic. Because each bot is a legitimate Internet device, separating the attack traffic from normal traffic can be difficult.

HOW TO IDENTIFY A DDoS ATTACK?
The most obvious symptom of a DDoS attack is a site or service suddenly becoming slow or unavailable. But since a number of causes — such a legitimate spike in traffic — can create similar performance issues, further investigation is usually required. Traffic analytics tools can help you spot some of these tell-tale signs of a DDoS attack: Suspicious amounts of traffic originating from a single IP address or IP range
A flood of traffic from users who share a single behavioural profile, such as device type, geolocation, or web browser version. An unexplained surge in requests to a single page or endpoint. Odd traffic patterns such as spikes at odd hours of the day or patterns that appear to be unnatural (e.g. a spike every 10 minutes). There are other, more specific signs of DDoS attack that can vary depending on the type of attack.

METHOLOGY:
Dataset Used: 
SDN Dataset 
(https://www.kaggle.com/code/aikenkazin/ddos-attack-detection-classification/data)

Algorithms used: 
Random Forest
KNN 
Logistic Regression 
Comparison of algorithms is done using:
Accuracy Score
Confusion Matrix
F1- Score



